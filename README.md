# Server-Performance-Stats-Script

This script provides basic server performance statistics including CPU usage, memory usage, disk usage, and the top 5 processes by CPU and memory usage.

## Features

The script provides real-time information about:
- Total CPU usage percentage
- Memory usage (Used vs Free) with percentages
- Disk usage (Used vs Free) with percentages
- Top 5 processes consuming CPU
- Top 5 processes consuming memory

## Prerequisites

- Linux-based operating system
- Bash shell
- Standard Linux utilities: `top`, `free`, `df`, `ps`, `awk`, `sed`

## Usage

1. Make sure the script has execute permissions:
    ```bash
    chmod +x server-stats.sh
    ```

2. Run the script:
    ```bash
    ./server-stats.sh
    ```

## Output

The script will output the following information:
- Total CPU usage
- Total memory usage (Free vs Used including percentage)
- Total disk usage (Free vs Used including percentage)
- Top 5 processes by CPU usage
- Top 5 processes by memory usage

## Example

```bash
Server Performance Stats
Total CPU Usage:
15.3%
Total Memory Usage:
Used: 2048MB (50.00%), Free: 2048MB (50.00%)
Total Disk Usage:
Used: 20GB (40.00%), Free: 30GB (60.00%)
Top 5 Processes by CPU Usage:
  PID  PPID CMD                         %MEM %CPU
  1234  567  /usr/bin/python3 script.py  1.2  20.0
  2345  678  /usr/bin/java -jar app.jar  2.5  15.0
  ...
Top 5 Processes by Memory Usage:
  PID  PPID CMD                         %MEM %CPU
  2345  678  /usr/bin/java -jar app.jar  2.5  15.0
  1234  567  /usr/bin/python3 script.py  1.2  20.0
  ...
```

## Project Repository

You can find more project repository at:
[https://roadmap.sh/projects/server-stats](https://roadmap.sh/projects/server-stats)
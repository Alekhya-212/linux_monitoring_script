# Linux Server Monitoring & Audit Script

## Overview
This Bash script monitors key system metrics on a Linux machine:
- CPU and memory usage
- Disk usage
- Top 5 memory-consuming processes
- Failed login attempts

All results are stored in timestamped log files for easy auditing and troubleshooting.

## Features
- CPU and memory snapshot
- Disk usage in human-readable format
- Top 5 processes sorted by memory
- Failed login attempts
- Timestamped logs stored in `/var/log/custom_monitor/`

## Usage
1. Clone the repository:
   ```bash
   git clone https://github.com/Alekhya-212/linux_monitoring_script.git
   cd linux_monitoring_script

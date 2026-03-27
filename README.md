# Log Analysis Tool

## Overview
This tool analyzes log files and detects suspicious failed login attempts.

## Features
- Detect failed login attempts
- Count IP addresses
- Detect suspicious IPs (failed attempts >= 3)

## Usage
python3 log_analysis.py <logfile>

Example:
python3 log_analysis.py log.txt

## Sample Log
192.168.1.10 login success
192.168.1.20 login failed
192.168.1.20 login failed
192.168.1.20 login failed

## Sample Output
Suspicious IP: 192.168.1.20  Failed attempts: 3

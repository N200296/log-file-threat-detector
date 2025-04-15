# log-file-threat-detector
A Python script to detect suspicious access patterns in server log files and generate a PDF security report.

# Log File Threat Detector 🕵️‍♂️

A Python script that analyzes server log files for suspicious access patterns  
and generates a PDF security report.

## Features
- Detects high-frequency IP access.
- Identifies potential brute-force attempts.
- Generates a professional PDF security report.

## Requirements
- Python 3.x
- `fpdf` library (`pip install fpdf`)

## How to Use
1. Place your log file in the project folder and name it `access.log`.
2. Run the script:
```bash
python log_threat_detector.py

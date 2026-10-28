# EWB Phishing URL Awareness Checker

## Overview
Phishing is a trick where criminals use fake links to steal passwords or personal data. This project is a Python tool that checks the text of a URL for six common warning signs. It does not visit the website; it only reads the text.

## Features
- Detects an @ symbol in the URL.
- Flags unusually long URLs (over 100 characters).
- Flags IP-address hostnames.
- Flags many hostname segments (5 or more parts).
- Flags punycode-style hostnames (xn--).
- Flags the HTTP scheme.
- **Improvement 1**: Added a continuous loop so the user can check multiple URLs without restarting.
- **Improvement 2**: Added a try/except block to handle malformed URLs without crashing.

## Requirements
Python 3.10 or later. No extra packages are needed.

## How to Run
Windows: `python phishing_checker.py`
Mac/Linux: `python3 phishing_checker.py`

## Example Output
```text
Enter a sample URL to inspect: http://192.0.2.10/account

Result:
- Uses an IP address instead of a familiar domain.
- Uses HTTP. HTTPS alone does not prove trust.

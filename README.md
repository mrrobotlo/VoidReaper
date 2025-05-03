# VoidReaper

**VoidReaper** is a high-intensity HTTP stress testing tool built with Node.js. It is designed for security researchers and system administrators to simulate traffic floods and test the resilience of their infrastructure under load.

> ⚠️ **Extreme Warning:**
> This tool is **extremely dangerous** if misused. VoidReaper can flood and severely disrupt online services.  
> **Unauthorized use** against any system you do not own or do not have explicit permission to test is **illegal**, unethical, and strictly forbidden.  
> The developer is not responsible for any misuse, damages, or consequences resulting from this tool.

## Features

- Supports both HTTP and HTTPS protocols
- Default configuration for quick stress simulation
- High-frequency GET requests sent in parallel
- Lightweight and fast execution

## Requirements

- [Node.js](https://nodejs.org/) v14 or higher

## Installation

git clone https://github.com/mrrobotlo/VoidReaper.git

cd VoidReaper

node VoidReaper.js

How to Use

node VoidReaper.js

When executed, the script will prompt you to enter:

1. The target URL (e.g., https://example.com)


2. The number of threads (e.g., 100)



Example session:

Target: https://example.com
Threads: 100
Starting VoidReaper attack on https://example.com with 100 threads...

Intended Use

VoidReaper was created solely for:

Educational purposes

Load testing of systems you own or have explicit authorization to test

Evaluating the effectiveness of firewalls, WAFs, and DDoS protection services


Legal

License: MIT

You are fully responsible for how you use this tool.

Do not use VoidReaper for illegal activities.

By using this tool, you agree to use it responsibly and legally.



---

Author: mrrobotlo

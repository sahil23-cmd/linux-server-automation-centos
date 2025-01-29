Linux Automation Scripts for Server Management
This repository contains automation scripts for managing CentOS-based servers.

## Features
- Automated user account creation from a file
- Disk usage monitoring with email alerts
- Scheduled cron jobs for automated task execution

### Scripts
1. **userscript.sh**: Creates users from a provided file (`userlist.txt`).
2. **diskmonitor.sh**: Monitors disk usage and sends email alerts if usage exceeds a defined threshold.

### Usage
- Ensure scripts have execution permissions:  
  `chmod +x userscript.sh diskmonitor.sh`
- Run `userscript.sh` with a user list:  
  `./userscript.sh userlist.txt`
- Configure `diskmonitor.sh` in a cron job for hourly execution.

### Requirements
- CentOS 7+
- `mailx` or `sendmail` for email alerts

---

This project will demonstrate your practical Linux skills and readiness to handle real-world challenges, making it a valuable addition to your resume and interview preparation. Let me know if you need additional details!

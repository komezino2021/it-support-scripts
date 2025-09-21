# IT Support Automation Scripts

A collection of PowerShell and Batch scripts designed to streamline common 1st Level IT Support tasks.  
These scripts help IT technicians quickly diagnose, troubleshoot, and resolve issues in Windows environments.  

---

## Available Scripts

### 1. Network Connectivity Check (Batch)
Description: Pings key network endpoints and saves the results in a log file.  
Usage:  
```bash
ping_check.bat

Log file will be generated in the same directory.
2. Network Connectivity Check (PowerShell)

Description: Pings key network endpoints with advanced logging options.
Usage:

./ping_check.ps1

3. Service Status Checker (PowerShell)

Description: Checks and restarts essential Windows services (e.g., Windows Update, Print Spooler).
Usage:

./service_status_checker.ps1

4. Password Reset (PowerShell)

Description: Resets user passwords for local accounts.
Usage:

./password_reset.ps1

5. System Information (PowerShell)

Description: Displays basic system information, including disk space and OS version.
Usage:

./sys_info.ps1

6. Active Process List (PowerShell)

Description: Lists all active processes with CPU and memory usage.
Usage:

./active_process.ps1

Getting Started

    Clone this repository:

git clone https://github.com/komezino2021/it-support-scripts.git

    Navigate into the folder:

cd it-support-scripts

    Run scripts in PowerShell (Admin mode) or Command Prompt depending on file type.

Notes

    Some scripts require Administrator privileges.

    Tested on Windows 10/11.

    Modify endpoints/services in scripts to fit your environment.

Author

Maintained by komezino2021

Email: clementsadjere@gmail.com

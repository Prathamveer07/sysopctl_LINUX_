# sysopctl_LINUX_
ysopctl is a powerful, custom Bash utility created to streamline and automate common system administration tasks on Linux systems. This tool empowers system administrators to efficiently manage services, monitor system health, analyze logs, and perform backups — all through a simple command-line interface. With its range of features, sysopctl is designed to save time and improve the ease of managing system resources, from process monitoring to disk usage and service control.

# Features
-**System Management Operations:**
List, start, and stop system services.
View system load averages.
Check disk usage statistics.
Monitor real-time process activity.
Analyze system logs for critical entries.
Backup system files with rsync.

-**Help and Documentation:**
Access comprehensive usage documentation via the --help flag.
View version information with --version.

# Commands

### Basic Usage
- `sysopctl --help`: Displays help and usage information.
  
 ![image](https://github.com/user-attachments/assets/060c1bb4-f803-43ce-baf5-d0cc633093cf)

- `sysopctl --version`: Displays the version of sysopctl.

 ![image](https://github.com/user-attachments/assets/178f81a0-4645-4866-909d-a6f0a3bd61e9)

### Service Management
- `sysopctl service list`: Lists all active services.
  
 ![image](https://github.com/user-attachments/assets/3ffe2a59-dce5-4540-9550-4666829c217a)

- `sysopctl service start <service-name>`: Starts a specified service.
  
 ![image](https://github.com/user-attachments/assets/47d2dd82-57bf-4898-b1ca-76b60c7e3803)

- `sysopctl service stop <service-name>`: Stops a specified service.
  
 ![image](https://github.com/user-attachments/assets/f80217f0-b05c-407f-bb22-a82e695075b9)


### System Monitoring
- `sysopctl system load`: Displays current system load averages.

  ![image](https://github.com/user-attachments/assets/907faf7b-25a7-44fd-bf30-a4eda72692f0)

- `sysopctl disk usage`: Displays disk usage statistics.
  
 ![image](https://github.com/user-attachments/assets/b14fd1b6-884a-4d3e-9297-8ebd4672ebc7)


### Advanced Operations
- `sysopctl process monitor`: Monitors real-time process activity.
  
- ![image](https://github.com/user-attachments/assets/04340d4c-f07b-46cf-a57a-d898886e6a68)

- `sysopctl logs analyze`: Analyzes recent critical log entries.
  
- ![image](https://github.com/user-attachments/assets/f545c5fa-6ff9-4b5a-8209-0ce9cd6ce470)

- `sysopctl backup <path>`: Backs up specified system files.
 
## Installation

To use **sysopctl**, clone the repository and follow the installation instructions:

```bash
git clone <repository-url>
cd sysopctl
chmod +x sysopctl.sh

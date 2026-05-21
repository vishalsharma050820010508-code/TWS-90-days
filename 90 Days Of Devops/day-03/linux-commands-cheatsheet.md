## Day 03 – Linux Commands  Cheatsheet

<img width="706" height="805" alt="image" src="https://github.com/user-attachments/assets/4bc84635-288e-453a-badb-581abbab707b" />

## File & Directory Commands
- pwd                 # Show current working directory
- ls                  # List files and folders
- ls -la              # List all files with permissions and hidden files
- cd /path            # Change directory
- mkdir test          # Create a new directory
- rmdir test          # Remove empty directory
- touch file.txt      # Create empty file
- cp file.txt bkp.txt # Copy file
- mv bkp.txt new.txt  # Move or rename file
- rm file.txt         # Delete file
- find /home -name "*.txt"   # Find all .txt files

## File Viewing & Editing
- cat file.txt        # Display full file content
- less file.txt       # View file page by page
- head -5 file.txt    # Show first 5 lines
- tail -5 file.txt    # Show last 5 lines
- tail -f logs.txt    # Monitor file logs in real time
- vim file.txt        # Open file in vim editor

## User & Permission Commands
- whoami              # Show current logged-in user
- id                  # Show user ID and group details
- sudo su             # Switch to root user
- passwd              # Change user password
- useradd devuser     # Create new user
- userdel devuser     # Delete user
- chmod 755 script.sh # Change file permissions
- chown ubuntu:ubuntu file.txt   # Change file owner

## Process Management
- ps -aux             # Show all running processes
- top                 # Monitor system processes live
- htop                # Interactive process viewer
- kill PID            # Stop process using PID
- kill -9 PID         # Force kill process
- pgrep nginx         # Find PID of process

## Service Management (systemd)
- systemctl status nginx    # Check service status
- systemctl start nginx     # Start service
- systemctl stop nginx      # Stop service
- systemctl restart nginx   # Restart service
- systemctl enable nginx    # Enable service at boot
- journalctl -u nginx       # View service logs

## Networking Commands
- ip a                      # Show IP address details
- ping google.com           # Test network connectivity
- curl google.com           # Fetch webpage data
- wget https://example.com/file.zip   # Download file
- netstat -tulnp            # Show open ports and services
- ss -tulnp                 # Display listening ports
-traceroute google.com     # Trace network route

## Disk & Memory Commands
- df -h               # Show disk space usage
- du -sh *            # Show folder sizes
- free -m             # Display memory usage
- lsblk               # List block storage devices
- mount               # Show mounted filesystems

## Archive & Compression
- tar -cvf backup.tar folder/    # Create tar archive
- tar -xvf backup.tar            # Extract tar archive
- gzip file.txt                  # Compress file
- gunzip file.txt.gz             # Decompress gzip file
- zip -r project.zip project/    # Create zip archive
- unzip project.zip              # Extract zip file

## Package Management (Ubuntu/Debian)
- apt update             # Update package list
- apt upgrade            # Upgrade installed packages
- apt install nginx      # Install package
- apt remove nginx       # Remove package
- dpkg -l                # List installed packages


## Why is this Important 

- Troubleshooting
- To quickly check logs and network 
- Useful in real production issues

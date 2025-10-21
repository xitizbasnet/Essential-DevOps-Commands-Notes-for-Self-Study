## 🐧 Linux Commands

```bash
1. uname -a                          # Show system information
2. uptime                            # Show system uptime
3. hostname                          # Show hostname
4. whoami                            # Show current user
5. ls -lah                           # List directory contents with permissions
6. pwd                               # Show current directory
7. cd /path                          # Change directory
8. mkdir -p /path                    # Create a directory (with parent if needed)
9. rm -rf /path                      # Remove directory recursively
10. cp -r source target              # Copy files/directories recursively
11. mv oldname newname              # Move/Rename file
12. ps aux                           # Show running processes
13. top                              # Show real-time system performance
14. kill -9 PID                      # Kill a process forcefully
15. pkill -f process_name            # Kill process by name
16. df -h                            # Show disk space usage
17. du -sh /path                     # Show directory size
18. netstat -tulnp                   # Show listening ports
19. ss -tulnp                        # Show listening ports (alternative)
20. who                              # Show logged-in users
21. adduser username                 # Create a new user
22. passwd username                  # Change user password
23. usermod -aG group user           # Add user to a group
24. grep "text" file.txt             # Search for a string in a file
25. find /path -name "*.log"         # Find files matching pattern
26. chmod 755 file.sh                # Change file permissions
27. chown user:group file            # Change file owner
28. tar -czf archive.tar.gz directory/  # Compress files
29. tar -xzf archive.tar.gz          # Extract compressed file
30. cat file.txt                     # View file contents
31. tail -f /var/log/syslog          # View real-time log updates
32. echo "text" >> file.txt          # Append text to file
33. history                          # Show command history
34. clear                            # Clear terminal screen
35. alias ll='ls -lah'               # Create an alias
36. df -Th                           # Show file system disk space
37. wc -l file.txt                   # Count number of lines in a file
38. cut -d':' -f1 /etc/passwd        # Extract first column from file
39. awk '{print $1}' file.txt        # Print first column of text
40. sed -i 's/old/new/g' file.txt    # Replace text in a file
41. crontab -e                       # Edit cron jobs
42. cron -l                          # List scheduled cron jobs
43. rsync -av source/ target/        # Sync files
44. scp user@host:/path/to/file .    # Secure copy file
45. ssh user@host                    # SSH into a server
46. exit                             # Logout from shell
47. uptime                           # Show system uptime
48. free -m                          # Show memory usage
49. top                              # Show system performance
50. vmstat                           # Show CPU/memory stats
```


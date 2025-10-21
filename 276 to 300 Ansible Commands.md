## ⚙️ Ansible Commands

```bash
276. ansible --version                                      # Check Ansible version
277. ansible all -m ping                                    # Ping all hosts in the inventory
278. ansible-playbook playbook.yml                          # Run a playbook
279. ansible-inventory --list                               # Show inventory
280. ansible all -a "uptime"                                # Run a command on all hosts
281. ansible-playbook -i inventory.ini playbook.yml         # Specify inventory file
282. ansible-playbook -e "variable=value" playbook.yml      # Pass extra variables
283. ansible-playbook --syntax-check playbook.yml           # Check for syntax errors
284. ansible-vault encrypt file.yml                         # Encrypt a file
285. ansible-vault decrypt file.yml                         # Decrypt a file
286. ansible-vault create secret.yml                        # Create a new encrypted file
287. ansible all -m setup                                   # Gather system facts
288. ansible all -m shell -a "df -h"                        # Run shell commands
289. ansible all -m service -a "name=nginx state=started"   # Manage services
290. ansible all -m yum -a "name=httpd state=present"       # Install packages
291. ansible all -m copy -a "src=file.txt dest=/tmp/file.txt"  # Copy files
292. ansible all -m file -a "path=/tmp/test mode=0755 state=directory"  # Create a directory
293. ansible-playbook -i inventory.yml site.yml --tags web  # Run specific tags
294. ansible-galaxy install role_name                       # Install a role
295. ansible-galaxy list                                    # List installed roles
296. ansible-playbook -i inventory playbook.yml --check     # Run in dry-run mode
297. ansible-doc -l                                         # List all available Ansible modules
298. ansible-playbook -i inventory playbook.yml --start-at-task="task_name"  # Start playbook from a specific task
299. ansible -i inventory -m ping all                       # Ping all hosts
300. ansible-galaxy init myrole                             # Create a new Ansible role
```


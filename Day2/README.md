# Day 2 – DevOps Learning Journey

## 📖 Topics Covered
- Linux user and group management  
- File permissions and ownership  
- Basics of shell scripting and automation  

---

## 🛠️ Practical Experience
- Created and managed Linux users and groups  
- Assigned users to groups and switched between accounts  
- Modified file and directory permissions using `chmod`  
- Changed ownership of files with `chown`  
- Wrote and executed simple shell scripts for automation  

---

## 📂 Command Examples
```bash
# User & Group Management
whoami               # Show current user
id                   # Display user ID and groups
sudo adduser devops  # Add a new user
sudo groupadd admins # Create a new group
groups devops        # Show groups for a user
su devops            # Switch user
sudo userdel devops  # Delete a user

# Permissions & Ownership
ls -l                       # View file permissions
chmod 755 script.sh         # Change permissions (rwxr-xr-x)
chmod u+x script.sh         # Add execute permission for user
sudo chown devops:admins file.txt   # Change ownership

# Shell Basics
echo "Hello DevOps"         # Print text
DATE=$(date)                # Store current date in variable
echo "Today is $DATE"
nano script.sh              # Create/edit script
chmod +x script.sh          # Make script executable
./script.sh                 # Run script
```


## 📜 Example Shell Script
```bash
#!/bin/bash
echo "Hello DevOps 🚀"
echo "Today is $(date)"
echo "Logged in as $(whoami)"
```

## 💡 Key Insights

* User and group management is essential for controlling access in Linux systems.

* Permissions (r, w, x) ensure security and prevent unauthorized actions.

* Shell scripting introduces automation, which is a cornerstone of DevOps practices.
## 🔗 Daily Progress

This repository documents my 90-Day DevOps Journey, including daily notes, scripts, and hands-on exercises.
Follow my progress on LinkedIn: #100DaysOfDevOps #LearningInPublic

---

👉 Do you want me to also plan **Day 3 (Linux networking basics: IP, ping, curl, netstat, SSH, etc.)** with a LinkedIn draft + README template so you’ll be ready in advance?

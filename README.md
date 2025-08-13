# Linux File Permissions Project

## 📌 Project Overview
This project demonstrates my ability to work with file and directory permissions in a Linux environment.  
The tasks include checking current permissions, interpreting permission strings, and applying the correct security changes using the `chmod` command.

The final deliverable is a documented report (PDF) with:
- Screenshots of terminal commands
- Explanations of each step
- Before/after permission changes
- Security rationale for each modification

---

## 📂 Repository Contents
- **File_permissions_in_Linux_completed.pdf** → Final project report in PDF format
- **File_permissions_in_Linux_completed.docx** → Editable Word version of the report

---

## 🛠️ Skills Demonstrated
- Navigating the Linux file system
- Using `ls -la` to view file and directory permissions
- Understanding the Linux permission string format
- Modifying file permissions with `chmod`
- Securing hidden files and restricting directory access

---

## 📜 Key Commands Used
```bash
# List all files (including hidden) with permissions
ls -la /home/researcher2/projects

# Remove write permission from 'others'
chmod o-w project_k.txt

# Set read-only permissions for owner and group
chmod 440 .project_x.txt

# Remove execute permission for group on a directory
chmod g-x drafts

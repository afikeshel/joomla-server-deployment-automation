
# Joomla Final Project – DevOps

## 📘 Overview

This project is the final assignment for the DevOps course, implementing a full deployment, backup, and restore process for a Joomla-based web server.  
It demonstrates working knowledge of bash scripting, Linux administration, Git, containerized environments, and collaborative development practices.

---

## 👥 Team Members

- **Yair Koren** – [yair-koren](https://github.com/yair-koren)
- **Afik Eshel** – [afikeshel](https://github.com/afikeshel)

---

## 📂 Project Structure

```bash
.
├── backup.sh        # Backs up Joomla site files and MySQL database
├── cleanup.sh       # Retains only latest backups and removes old ones
├── restore.sh       # Restores full site and DB from the most recent backup
├── setup.sh         # Initializes environment and installs dependencies
├── joomla-files*.tar.gz  # Tarball of the Joomla site
├── my-joomla*.sql.gz     # Compressed SQL dump of the Joomla database
└── README.md        # This file

Terms Dictionary
This project includes articles explaining key terms from the course, available on the Joomla site under the glossary section. Each student contributed articles on terms such as:

git, chmod, curl, docker, nano, vim, grep, sudo, etc.

🧪 How to Use
Clone the repository:
git clone https://github.com/afikeshel/joomla-server-deployment-automation.git
cd joomla-final-devops

Run the setup (optional):
./setup.sh

To create a backup:
./backup.sh

To restore from backup:
./restore.sh

To clean old backups:
./cleanup.sh

Notes
The system uses compressed files (.tar.gz, .sql.gz) to optimize storage and transfer.
Backup/restore scripts include full error checking and modular function usage.
Project files are compatible with Ubuntu-based Linux VMs.




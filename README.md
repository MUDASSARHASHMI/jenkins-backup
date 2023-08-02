# Jenkins Backup
## Description
This is jenkins master node backup script. It will backup all the jobs, plugins, users, and global configurations.
## Usage
### Backup
```bash
./jenkins-backup.sh backup
```
### Restore
```bash
./jenkins-backup.sh restore
```
## Configuration
### Backup
```bash
# Jenkins URL
JENKINS_URL="http://localhost:8080"

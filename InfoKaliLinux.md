# Linux Commands for Beginners - Complete Cheat Sheet
## ![PDF](./images/Kali Chat Sheet.pdf)

## 1. File and Directory Management
- `ls` – List directory contents  
- `cd` – Change directory  
- `pwd` – Print working directory  
- `cp` – Copy files and directories  
- `mv` – Move or rename files and directories  
- `rm` – Remove files or directories  
- `mkdir` – Make directories  
- `rmdir` – Remove empty directories  
- `touch` – Create empty files or update timestamps  
- `find` – Search for files in a directory hierarchy  
- `locate` – Find files by name  
- `tree` – Display directories in a tree-like format  
- `chmod` – Change file permissions  
- `chown` – Change file owner and group  
- `chgrp` – Change group ownership  
- `stat` – Display file or file system status  

---

## 2. File Viewing and Editing
- `cat` – Display file content  
- `tac` – Display file content in reverse  
- `more` – View file content page by page  
- `less` – Scrollable file viewer  
- `head` – Show first lines of a file  
- `tail` – Show last lines of a file  
- `nano` – Simple text editor  
- `vim` / `vi` – Advanced text editor  
- `emacs` – Text editor  
- `grep` – Search text using patterns  
- `sed` – Stream editor for filtering and transforming text  
- `awk` – Pattern scanning and processing language  
- `cut` – Remove sections from each line  
- `sort` – Sort lines of text files  
- `uniq` – Omit repeated lines  

---

## 3. Process Management
- `ps` – Snapshot of current processes  
- `top` – Display Linux tasks  
- `htop` – Interactive process viewer  
- `kill` – Terminate a process  
- `killall` – Terminate processes by name  
- `bg` – Resume a job in background  
- `fg` – Bring job to foreground  
- `jobs` – List active jobs  
- `nice` – Run program with modified priority  
- `renice` – Alter priority of running processes  
- `uptime` – Show system uptime  
- `time` – Measure program running time  

---

## 4. Disk Management
- `df` – Report disk space usage  
- `du` – Estimate file space usage  
- `fdisk` – Partition table manipulator  
- `lsblk` – List block devices  
- `mount` – Mount a file system  
- `umount` – Unmount a file system  
- `parted` – Partition manipulation program  
- `mkfs` – Create a file system  
- `fsck` – File system check and repair  
- `blkid` – Print block device attributes  

---

## 5. Networking
- `ifconfig` – Configure network interfaces  
- `ip` – Show/manipulate routing, devices, tunnels  
- `ping` – Send ICMP Echo requests  
- `netstat` – Network statistics  
- `ss` – Socket statistics  
- `traceroute` – Trace route packets take  
- `nslookup` – Query DNS servers  
- `dig` – DNS lookup utility  
- `wget` – Download files  
- `curl` – Transfer data with URLs  
- `scp` – Secure copy between hosts  
- `ssh` – Secure shell login  
- `ftp` – File Transfer Protocol client  

---

## 6. User and Group Management
- `useradd` – Add user  
- `usermod` – Modify user  
- `userdel` – Delete user  
- `groupadd` – Add group  
- `groupdel` – Delete group  
- `passwd` – Change password  
- `chage` – Change password expiry info  
- `whoami` – Show current user  
- `who` – Show logged-in users  
- `w` – Show users and activity  
- `id` – Display user/group info  
- `groups` – Show user’s groups  

---

## 7. System Information and Monitoring
- `uname` – Print system info  
- `hostname` – Show/set hostname  
- `uptime` – Show system uptime  
- `dmesg` – Boot/system messages  
- `free` – Display memory usage  
- `top` – Display tasks  
- `vmstat` – Virtual memory statistics  
- `lscpu` – CPU info  
- `lsusb` – USB devices  
- `lspci` – PCI devices  
- `lshw` – Hardware configuration  

---

## 8. Archiving and Compression
- `tar` – Archive files  
- `tar -czf` – Compress with gzip  
- `tar -xzf` – Extract gzipped tarball  
- `zip` – Compress into ZIP  
- `unzip` – Extract ZIP  
- `gzip` – Compress with gzip  
- `gunzip` – Decompress gzip  
- `bzip2` – Compress with bzip2  
- `bunzip2` – Decompress bzip2  
- `xz` – Compress with xz  
- `unxz` – Decompress xz  

---

## 9. Package Management (Debian/Red Hat)
- `apt-get install <pkg>` – Install package  
- `apt-get update` – Update package list  
- `apt-get upgrade` – Upgrade packages  
- `apt-get remove <pkg>` – Remove package  
- `apt-cache search <pkg>` – Search package  
- `yum install <pkg>` – Install package (Red Hat)  
- `yum update` – Update packages  
- `dnf install <pkg>` – Install package (Fedora)  
- `rpm -i <pkg.rpm>` – Install RPM  
- `dpkg -i <pkg.deb>` – Install Debian package  

---

## 10. Scheduling Tasks
- `cron` – Scheduled commands  
- `crontab -e` – Edit cron jobs  
- `crontab -l` – List cron jobs  
- `crontab -r` – Remove cron jobs  
- `at` – Run commands at specified time  
- `batch` – Run when system load is low  
- `sleep` – Delay execution  

---

## 11. File Permissions and Security
- `chmod` – Change file permissions  
- `chown` – Change file owner/group  
- `chgrp` – Change group ownership  
- `umask` – Set default permissions  
- `setfacl` – Set ACLs  
- `getfacl` – Get ACLs  
- `sudo` – Run command as root  
- `visudo` – Edit sudoers file  
- `passwd` – Change password  

---

## 12. System Backup and Restore
- `rsync` – Synchronize files  
- `cpio` – Copy files to/from archives  
- `dd` – Low-level copy/backup  
- `dd if=/dev/sda of=backup.img` – Backup disk  
- `dd if=backup.img of=/dev/sda` – Restore disk  

---

## 13. System Diagnostics and Troubleshooting
- `dmesg` – Kernel messages  
- `journalctl` – View system logs  
- `strace` – Trace system calls  
- `lsof` – List open files  
- `vmstat` – Virtual memory stats  
- `iostat` – CPU/I/O stats  
- `mpstat` – CPU usage stats  
- `pidstat` – Process stats  
- `free` – Memory usage  
- `uptime` – System uptime  
- `watch` – Run command periodically  
- `htop` – Interactive process viewer  
- `netstat` – Network stats  
- `ss` – Socket stats  

---

## 14. Networking & Remote Management
- `ip addr` – Show IP addresses  
- `ip link` – Show/manipulate interfaces  
- `ip route` – Show routing tables  
- `nmap` – Network exploration  
- `telnet` – Telnet protocol  
- `nc` – Netcat utility  
- `iptables` – Packet filtering/NAT  
- `ufw` – Uncomplicated firewall  
- `tcpdump` – Packet analyzer  
- `scp` – Secure copy  
- `rsync` – Remote sync  

---

## 15. Text Processing Utilities
- `grep` – Search patterns  
- `sed` – Stream editor  
- `awk` – Text processing  
- `cut` – Remove sections  
- `sort` – Sort lines  
- `uniq` – Remove duplicates  
- `tee` – Write to file/stdout  
- `tr` – Translate/delete chars  
- `paste` – Merge lines  
- `wc` – Word/line/char count  

---

## 16. System Shutdown and Reboot
- `shutdown -h now` – Shutdown immediately  
- `shutdown -r now` – Reboot immediately  
- `reboot` – Reboot system  
- `halt` – Halt system  
- `poweroff` – Power off  
- `init 0` – Shutdown  
- `init 6` – Reboot  

---

## 17. Filesystem Mounting and Management
- `mount /dev/sda1 /mnt` – Mount partition to a directory  
- `umount /mnt` – Unmount a file system  
- `/etc/fstab` – Persistent mount configuration file  
- `blkid` – Display block device attributes  
- `fsck /dev/sda1` – Check and repair filesystem  

---

## 18. Filesystem Permissions and Security
- `chmod 755 file.txt` – Owner: read/write/execute, Others: read/execute  
- `chown user:group file.txt` – Change owner and group of a file  
- `chgrp group file.txt` – Change group ownership  
- `umask 022` – Default permissions for new files (755)  
- `setfacl` – Set access control lists (ACL)  
- `getfacl` – Get access control lists (ACL)  

---

## 19. Containerization and Orchestration

### Docker
- `docker run <image>` – Run a container from an image  
- `docker ps` – List running containers  
- `docker ps -a` – List all containers (including stopped)  
- `docker build -t <image_name> .` – Build an image from Dockerfile  
- `docker exec -it <container_id> bash` – Shell inside container  
- `docker stop <container_id>` – Stop a container  
- `docker rm <container_id>` – Remove a container  
- `docker logs <container_id>` – View container logs  
- `docker images` – List images  
- `docker rmi <image_name>` – Remove an image  
- `docker network ls` – List Docker networks  
- `docker-compose up` – Start multi-container environment  
- `docker-compose down` – Stop/remove containers  
- `docker-compose logs` – View logs  

### Kubernetes
- `kubectl get pods` – List pods  
- `kubectl get nodes` – List nodes  
- `kubectl get services` – List services  
- `kubectl apply -f file.yaml` – Apply configuration  
- `kubectl create -f file.yaml` – Create resource  
- `kubectl delete -f file.yaml` – Delete resource  
- `kubectl exec -it pod -- bash` – Shell inside pod  
- `kubectl logs pod` – View pod logs  
- `kubectl describe pod pod_name` – Pod details  
- `kubectl scale deployment <name> --replicas=N` – Scale deployment  
- `kubectl rollout restart deployment <name>` – Restart deployment  
- `kubectl port-forward pod <pod> local:remote` – Forward port  

### Helm
- `helm install <release> <chart>` – Install chart  
- `helm upgrade <release> <chart>` – Upgrade release  
- `helm list` – List releases  
- `helm delete <release>` – Delete release  
- `helm search <chart>` – Search chart  

---

## 20. Automation and Configuration Management

### Ansible
- `ansible all -m ping` – Ping all hosts  
- `ansible-playbook playbook.yml` – Run playbook  
- `ansible -m command -a 'cmd' host` – Run command on host  
- `ansible-playbook --check playbook.yml` – Dry-run playbook  
- `ansible-playbook --limit host playbook.yml` – Run on specific host  
- `ansible-playbook --extra-vars "key=value"` – Pass variables  

### Terraform
- `terraform init` – Initialize directory  
- `terraform plan` – Preview changes  
- `terraform apply` – Apply changes  
- `terraform destroy` – Destroy infrastructure  
- `terraform validate` – Validate configs  
- `terraform show` – Show current state  

### Puppet
- `puppet apply manifest.pp` – Apply manifest locally  
- `puppet agent --test` – Test Puppet agent  
- `puppet resource` – Show current state of resources  

---

## 21. CI/CD Tools

### Jenkins
- `java -jar jenkins.war` – Start Jenkins  
- Access Jenkins at `http://localhost:8080`  

### GitLab CI
- `.gitlab-ci.yml` – Pipeline config file  
- `gitlab-runner register` – Register runner  
- `gitlab-runner run` – Run jobs  

### GitHub Actions
- `.github/workflows/` – Workflow config files  
- `actions/checkout@v2` – Checkout repo code  
- `actions/setup-node@v2` – Setup Node.js  
- `docker/setup-buildx-action@v1` – Setup Docker Buildx  

---

## 22. Cloud Services

### AWS CLI
- `aws configure` – Configure credentials  
- `aws s3 cp file.txt s3://bucket` – Upload file to S3  
- `aws ec2 describe-instances` – List EC2 instances  
- `aws ec2 start-instances --instance-ids <id>` – Start EC2  
- `aws ec2 stop-instances --instance-ids <id>` – Stop EC2  
- `aws s3 sync local/ s3://bucket` – Sync directories  

### Azure CLI
- `az login` – Log in  
- `az vm list` – List VMs  
- `az vm start --name vm --resource-group group` – Start VM  
- `az storage blob upload` – Upload to blob storage  
- `az group create` – Create resource group  

### Google Cloud SDK
- `gcloud auth login` – Log in  
- `gcloud compute instances list` – List instances  
- `gcloud compute instances stop <name>` – Stop VM  
- `gcloud app browse` – Open App Engine  

---

## 23. Logging and Monitoring

### Prometheus
- `prometheus` – Start server  
- `prometheus --config.file=config.yml` – Start with config  

### Grafana
- `grafana-cli plugins install <plugin>` – Install plugin  

### ELK Stack
- `elasticsearch` – Start Elasticsearch  
- `curl -XGET 'localhost:9200/_cluster/health?pretty'` – Cluster health  
- `logstash -f config_file` – Run Logstash  
- `kibana` – Start Kibana (http://localhost:5601)  

---

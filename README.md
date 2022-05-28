```bash
sudo vim /etc/fstab 
ls -l /swapfile  
ls -lh /swapfile
-sudo swapoff -a
free -h
-sudo fallocate -l 6G /swapfile
-sudo mkswap /swapfile
-sudo swapon --show
```

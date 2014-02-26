Linux-Kernel-Tuning-and-Hardening
=================================

Bash script for optimizing performance and hardening Linux kernel. Use it with caution. 

### Usage

###### 1. Download the script to a folder on your Linux machine (eg.: /root/scripts/), then make it executable

```bash
wget https://raw.github.com/minhdanh/Linux-Kernel-Tuning-and-Hardening/master/kernel_hardening_tuning.sh
chmod +x kernel_hardening_tuning.sh
./kernel_hardening_tuning.sh
```

###### 2. Allow the script to run everytime the system starts

````bash
vim /etc/rc.local

# Add the following line:
/root/scripts/firewall-script.sh
````

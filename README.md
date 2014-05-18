Linux-Kernel-Tuning-and-Hardening
=================================

Bash script for optimizing performance and hardening Linux kernel by adjusting the kernel parameters. It is self-explained and not supposed to be a one-thing-fit-all script. You should see the script for yourself and adjust the values for your need. Use it with caution. 

### Usage

###### 1. Download the script to a folder on your Linux machine (eg.: /root/scripts/), then execute it

```bash
wget https://raw.github.com/minhdanh/Linux-Kernel-Tuning-and-Hardening/master/kernel_hardening_tuning.sh
chmod +x kernel_hardening_tuning.sh
./kernel_hardening_tuning.sh
```

###### 2. Allow the script to run everytime the system starts

````bash
vim /etc/rc.local

# Add the following line:
/root/scripts/kernel_hardening_tuning.sh
````

### References

I made the script using the following sources:

1. http://docs.oracle.com/cd/E19644-01/817-5051/pt_tuningos.html#wp62221
2. http://www.netadmintools.com/art295.html
3. https://cs.uwaterloo.ca/~brecht/servers/openfiles.html
4. http://www.nateware.com/linux-network-tuning-for-2013.html
5. http://www.lognormal.com/blog/2012/09/27/linux-tcpip-tuning/
6. http://aiscaler.com/wiki/linux-tuning-for-high-performance
7. http://www.cyberciti.biz/faq/linux-tcp-tuning/
8. https://www.frozentux.net/ipsysctl-tutorial/ipsysctl-tutorial.html
9. http://www.susegeek.com/networking/network-performance-fine-tuning-in-opensuse-suse/

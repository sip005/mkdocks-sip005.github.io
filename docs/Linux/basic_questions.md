### 1. How to see which kernel version a system is running?

```plain text
- uname ["uname" prints out system information]
- uname -a ["uname" with "-a" flag will give us everything it has on the system]
- uname -v [It will print out kernel version]
- uname -r [it will print out kernel release]
- 
```

### 2. How can we check our current ip address?

```plain text
- ifconfig [it will printout everything, IPv4, IPv6, broadcast, subnetmask(mask), loopback(lp)]
- ip addr show [it will give us all the information]
- ip addr show eth0 [this will give us all the information regarding eth0]
```

### 3. How do we check for free disk space?

```plain text
- df -ah [disk free, all files, human readble] [this will give us read of all the files on our system]
the above command will show us the root partition and the hard drive partition

```

### 4. How do we manages services on a system? (how do we know if a service is running, how do we start and stop service)

```plain text
- systemctl status _name_of_the_service 
```

### 5. How would we check the size of a directories content on the disk?

```plain text
- du -sh name_of_directory [to print the size occupied in the disk]
```

### 6. How would we check for open ports in the linux machine?

```plain text
- netstat [gives all the information]
- netstat -tulpn [t- TEC, u- UDP, l- lisening, pn- port number]
- sudo netstat -tulpn [running as root will show us all the PID/Processes]
```

### 7. How would we check CPU usage of a given process?

```plain text
- ps aux | grep name_of_the_process
- top
- htop [required to be installed]
```

### 8. How would we deal with mount of new memory?

```plain text
- ls /mnt
- mount /dev/sda2/ /mnt [mount address and mount point]
- mount [check for any mount, pass the keyword "mount" without any arguments]
```

### 9. If we want to mount a volume at the boot what file would we look in ?

```plain text
- less etc/fstab
```

### 10. How to look up mannual in linux system?

```plain text 
- man _name_of_the_command_we_are_looking_for
```

### 11. 
# Stealth-Kernel-Module
This Linux Kernel module is meant to be hidden from all searches

## Steps to run

#### Build this kernel module:

```bash
$ make
```
#### Load lkm-hidden:

```bash
$ sudo insmod hidden.ko
```
#### Then, you can NOT figure out the kernel module.

```bash
$ cat /proc/modules | grep hidden
$ ls -l /sys/module/ | grep hidden
```

![image](https://github.com/Het-Joshi/Stealth-Kernel-Module/assets/96608251/2460e821-a899-4f83-8c85-4109d346b4e8)


------
Made as a hands-on project for the course "Linux Kernel Programming" ~ CSE633
- Het Joshi 1MS21CS053
- Laya Arun 1MS21CS067
- Piyush Khodbole 1MS21CS091
------

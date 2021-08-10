# born2beroot 👶

This project aims to introduce me to the wonderful world 🌍 of virtualization.

## Requisites

![image](https://user-images.githubusercontent.com/52896719/128854847-b51e2052-17cb-40ff-ba7a-7355eb441fca.png)

## Files 📁
- 📝**signature.txt** -> This document contains a hash from VM *(.vdi format)*

- 💿**born2beroot.vdi** -> Virtual Disk Image *(Not uploaded)*

## Summary ⏬

This project consists of having you set up your first server by following specific rules 🔽

- 🖌️ No graphic interface 
- 💻 **Debian** Buster 10 
- 🛡️ **AppArmor** activated
- 🔐 2 encrypted partitions using **LVM**
___
![Console Snapshot](snapshots/vbox_snap1)
___
- 🔏 **SSH** service on port 4242, it is impossible to connect as root
- 🔥 **UFW** firewall leave only port 4242 open
- 🚹 **Hostname** personalizated
- 🛑 Strong password policy
- 🦸 ***Sudo*** configured following strict rules
- 👫 Adding many users and groups
- 📄 **Script** that display some hardware and software information on all terminals every 10 minutes 🔽
___
![Script](snapshots/vbox_snap2.png)
___

***In case you would like to try this VM, please contact me!***

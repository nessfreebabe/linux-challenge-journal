# linux-challenge-journal
# My Linux Upskill Challenge Journal
BITA Kernel Crew · Cohort 1 · Sept 2026

## Day 0
- Set up my server (DigitalOcean / Killercoda) — it's alive 🐧
- Problems I hit and how I fixed them:
  **commands not working>>>reboot terminal and server**
## Day 1
- SSH using a passwordless connection
- I learned commands/shortcuts on how to use my server
- I learned how to change my password, about my server's status, memory, CPU, storage, and network (ex: netstat -i, Ifcongig, ip addr, ip add)
1. username command: whoami
   **root@nessafbaby**
2. Linux distribution name and version command: cat /etc/os-release
   **Ubuntu 24.04.4 LTS**
3. Server's uptime command: uptime
   **up 1 week, 1 day, 16 hours, 37 minutes**
4. Version of the Linux kernel currently running on the server command: uname -r
   **6.8.0-142-generic**
5. Number of active login sessions and usernames command: who | wc -l
   **1, root@nessfbaby**
6. CPU architecture command: uname -m, logical CPU count command: nproc
   **x86_64, 1**
7. Names of the block devices and approx sizes command: lsblk
   **NAME    MAJ:MIN RM  SIZE RO TYPE MOUNTPOINTS
vda     253:0    0   10G  0 disk 
├─vda1  253:1    0    9G  0 part /
├─vda14 253:14   0    4M  0 part 
├─vda15 253:15   0  106M  0 part /boot/efi
└─vda16 259:0    0  913M  0 part /boot
vdb     253:16   0  490K  1 disk**
8. Total memory and available memory command: free -h
   **total        used        free      shared  buff/cache   available
Mem:           458Mi       164Mi        35Mi       4.0Mi       282Mi       294Mi
Swap:             0B          0B          0B**
9. Total capacity, used capacity, available capacity, and percentage used command: df -h /
    **Filesystem      Size  Used Avail Use% Mounted on
/dev/vda1       8.7G  2.3G  6.4G  26% /**
10. The interface name and IPv4 address command: ip -4 -br addr
    **lo               UNKNOWN        127.0.0.1/8 
eth0             UP             159.223.100.202/20 10.10.0.5/16 
eth1             UP             10.116.0.2/20**
## Day 2
- Learned how to navigate the file system, create files and directories, RTFM
- /home & /ubuntu most common directories used during challenge
- cd=change directory to check other directories
- I learned how to change my password, about my server's status, memory, CPU, storage, and network (ex: netstat -i, Ifcongig, ip addr, ip add)

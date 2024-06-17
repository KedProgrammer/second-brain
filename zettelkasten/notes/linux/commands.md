---
date: 2024-05-14
tags:  
    - linux 
hubs:
    - [[]]
urls:
    - https://www.pluralsight.com/blog/it-ops/linux-file-permissions
---

# commands

## add executable permission to file

- **chmod 777** foldername will give read, write, and execute permissions for everyone.


## remove files with patter
- rm * (remove all files in a folder directory)
- rm *pattern* (removes all files with that pattern)


## generate ssh key:
    ssh-keygen -t ed25519 -C "your_email@example.com"

## check system memory capacity
- df -h


## ls -lh
- check all files in folder with permissions and weight

## create link
- ln original_file destiny


## list files with relative paths
- ls -l

## search files with name
- find /etc/ -iname ".conf"

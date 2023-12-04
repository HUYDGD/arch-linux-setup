# arch-linux-setup
HUYDGD's Arch Linux Setup

# ArchWiki
```https://wiki.archlinux.org/```

# Backup
```
sudo rsync -aAXHvP --delete --exclude=/dev/* --exclude=/proc/* --exclude=/sys/* --exclude=/tmp/* --exclude=/run/* --exclude=/mnt/* --exclude=/media/* --exclude=/lost+found --exclude=/home/haruto/.local/share/Trash/* --exclude=home/haruto/Personal/Resources/Games/* / /mnt/Storage2/Personal/Backups/ArchLinux/
```

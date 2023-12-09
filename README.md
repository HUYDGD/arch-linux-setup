# arch-linux-setup
HUYDGD's Arch Linux Setup

# ArchWiki
```https://wiki.archlinux.org/```

# Backup
```
sudo rsync -aAXHvP --delete --exclude=/dev --exclude=/proc --exclude=/sys --exclude=/tmp --exclude=/run --exclude=/mnt --exclude=/media --exclude=/lost+found --exclude=/home/haruto/.local/share/Trash/* --exclude=home/haruto/Personal/Resources/Games/* / '/run/media/haruto/Storage 2/Personal/Backups/ArchLinux/'
```

# Rdesktop
```
rdesktop -g 1366x768 -P -z -x l -r sound:off -u huy 192.168.100.3:3389
```

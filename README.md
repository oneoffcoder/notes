# Notes

## Mount Network Drives

To mount.

```bash
mkdir ./me
mkdir ./all

mount_smbfs -t smbfs //[username]@192.168.0.5/Users/[username] ./me
mount_smbfs -t smbfs //[username]@192.168.0.5/All ./all
```

To unmount.

```bash
umount ./me
umount ./all
```



- [Mount Error when attempting to mount a network server](https://apple.stackexchange.com/questions/129753/mount-error-when-attempting-to-mount-a-network-server)
- [command line: unmount a smb network drive](https://apple.stackexchange.com/questions/256209/command-line-unmount-a-smb-network-drive)

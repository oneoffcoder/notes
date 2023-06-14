# Notes

## Mount

```bash
mkdir ./me
mkdir ./all

mount_smbfs -t smbfs //[username]@192.168.0.5/Users/[username] ./me
mount_smbfs -t smbfs //[username]@192.168.0.5/All ./all
```

- [Mount Error when attempting to mount a network server](https://apple.stackexchange.com/questions/129753/mount-error-when-attempting-to-mount-a-network-server)

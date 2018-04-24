# key
```
wget https://raw.github.com/tank142/repo/master/tank.gpg -P /tmp/
sudo pacman-key --add /tmp/tank.gpg
sudo pacman-key --lsign-key 0FE04E8C39E79FB0
rm /tmp/tank.gpg
```

# /etc/pacman.conf
```
[xfce412]
Server = https://raw.github.com/tank142/repo/master/xfce412/$arch

[tank]
Server = https://raw.github.com/tank142/repo/master/tank/$arch

[nvidia304]
Server = https://raw.github.com/tank142/repo/master/nvidia304/$arch

[xorg119]
Server = https://raw.github.com/tank142/repo/master/xorg119/$arch

[sysvinit]
Server = https://raw.github.com/tank142/repo/master/sysvinit/$arch
```

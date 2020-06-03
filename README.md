# keys
```
wget https://raw.github.com/tank142/repo/master/tank142.gpg -P /tmp/
sudo pacman-key --add /tmp/tank142.gpg
sudo pacman-key --lsign-key DE3DD480FC8128933C95C9E05A5C8538A49C6812
rm /tmp/tank142.gpg
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

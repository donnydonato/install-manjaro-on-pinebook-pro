# Install Manjaro On Pinebook Pro
A tutorial on how to install Manjaro on a Pinebook Pro

Download Image
```
wget https://osdn.net/projects/manjaro-arm/storage/pbpro/xfce/20.08/Manjaro-ARM-xfce-pbpro-20.08.img.xz
```

Extract Image
```
tar xvf Manjaro-ARM-xfce-pbpro-20.08.img.xz
```

Write Image
```
sudo dd bs=4M if=Manjaro-ARM-xfce-pbpro-20.08.img of=/dev/mmcblk2 status=progress oflag=sync
```

# hamonikr-plymouth-theme

grub theme for HamoniKR 

# Developer

Kevin Kim <root@hamonikr.org>

# Installation

```
$ wget https://github.com/ivsteam/grub-theme-hamonikr/archive/1.0.tar.gz
$ tar -xvzf 1.0.tar.gz
$ cd grub-theme-hamonikr
$ sudo ./install
```

# Issues

https://github.com/ivsteam/grub-theme-hamonikr/issues

# change font

grub 폰트는 크기를 미리 정한 폰트가 있어야 하므로 사용할 폰트는 아래와 같이 생성해야 한다.

```
sudo grub-mkfont -s 10 -o /boot/grub/themes/hamonikr/Monaco-10.pf2 /usr/share/fonts/truetype/hamonikr-custom/Monaco_Linux.ttf 
```
# Grub2 Theme Vimix
###### AUTHOR: [vinceliuice](http://gnome-look.org/content/show.php/Grub-themes-vimix?content=169954)

# Installation
### Arch Linux
##### install packages form AUR :
```shell
$ yaourt -S grub2-theme-vimix-git
```
##### Edit /etc/default/grub :
```shell
GRUB_THEME="/boot/grub/themes/Vimix/theme.txt"
```
##### Update grub :
```shell
$ grub-mkconfig -o /boot/grub/grub.cfg
```
### Fedora 28/29/32
##### install packages:
```shell
$ cd Downloads/
$ git clone https://github.com/Se7endAY/grub2-theme-vimix.git && cd grub2-theme-vimix
$ sudo cp -r Vimix/ /boot/grub2/themes/ 
$ sudo nano /etc/default/grub
```
#### Copy this at the bottom 
```shell
$ GRUB_THEME="/boot/grub2/themes/Vimix/theme.txt"
```
#### Place # marker in front 
```shell
$ GRUB_TERMINAL_OUTPUT="console"
```
##### Update grub:
```shell
$ sudo grub2-mkconfig -o /etc/grub2.cfg
```

##### Update grub for UEFI boot:
```shell
$ sudo grub2-mkconfig -o /etc/grub2-efi.cfg
```

# Screenshot
![screenshot](/preview.jpg?raw=true)

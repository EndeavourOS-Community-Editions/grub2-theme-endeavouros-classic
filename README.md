# Grub2 Theme EndeavourOS – Old Theme

###### Classic fork created by LeSnake04
###### Original AUTHOR: [vinceliuice](http://gnome-look.org/content/show.php/Grub-themes-vimix?content=169954)
###### AUTHOR: [EndeavourOS-team](https://github.com/endeavouros-team)
###### forked from Se7endAY/grub2-theme-vimix
git clone repo, cd into it and build and install using makepkg:
```
git clone https://github.com/EndeavourOS-Community-Editions/grub2-theme-endeavouros-classic.git
cd grub2-theme-endeavouros-classic
makepkg -si
```
To make it used:
#### Edit /etc/default/grub :
```shell
GRUB_THEME="/boot/grub/themes/EndeavourOS/theme.txt"
```

#### Update grub :
```shell
sudo grub-mkconfig -o /boot/grub/grub.cfg
```
#### Preview
![preview](https://raw.githubusercontent.com/lesnake04/grub2-theme-endeavouros/master/preview.png "preview")

# SkyBase - GRUB theme
Custom visual theme for a GRUB bootloader screen

## Instalation
### Download

Just clone my repo by:
```
git clone https://github.com/ArchAngel776/skybase-grub-theme.git
```
### Copy into GRUB themes dir (optional)
After that copy all repo into **/boot/grub/themes/skybase** (if directory **themes** doesn't exist in **/boot/grub** just create them):
```
sudo cp -r <repo_dir> /boot/grub/themes/skybase
```
### Bind theme into the GRUB config file
Open a GRUB config file located as **/etc/default/grub** and make sure there is a line placed like:
```
GRUB_BACKGROUND=""
GRUB_THEME=/boot/grub/themes/skybase/theme.txt
```
Of course, the path specified in **GRUB_THEME** should be pointed on your theme directory
### Update GRUB
In the end just type a command:
```
sudo update-grub
```
That's all!

## Warning
I only tested it in Full HD (1920x1080) resolution and only a few (4) system choice options. I don't how it behave on another configuration (it may be changed in the future).

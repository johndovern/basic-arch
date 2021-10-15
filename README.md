# basic-arch
This script was made by Ermanno Ferrari and can be found [here](https://gitlab.com/eflinux/arch-basic/-/tree/master). I have adapted it to suit my needs and I don't have a gitlab account, otherwise I would have just forked it there and would not be bothering with writing all this shit.
```
pacman -S wget
wget -O https://raw.githubusercontent.com/johndovern/basic-arch/master/base-uefi.sh
sh base-uefi.sh
```
Edit the script for your needs, if you are familiar with arch it should be clear what this script is doing.
This should be run after formating and mounting your drive, using pacstrap to install the basics (base linux linux-firmware git wget neovim intel-ucode), running genfstab, and finally arch-chroot into your system where you can run the above to configure the rest of your system.

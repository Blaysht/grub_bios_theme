# GRUB THEME "BIOS boot device"
![image](./preview.png)
Ladies and gentlemen, the GRUB design theme for all fans of old computer software design is coming to your attention. The theme is inspired by the bootable device selection menu on the old BIOS. Also, such a design can surprise or confuse outsiders who will try to do something with your GRUB without your knowledge. In addition, the theme looks good together with [Chicago95](https://github.com/grassmunk/Chicago95) and [Windoze95](https://github.com/Liftu/Windoze95-1080-Plymouth-theme).

## To install:
___

### Step 1
Copy the *OldBIOS* folder to the directory `/boot/grub/themes`

### Step 2
Edit your `/etc/default/grub` file to include `GRUB_THEME="/boot/grub/themes/OldBIOS/theme.txt"`

### Step 3
Finalize your changes with `sudo update-grub`
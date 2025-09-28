# Valheim Grub Theme [ValGrub]

A GRUB theme inspired by the Valheim main menu.

**Exemple**
![](resources/Exemple1.png)

## Install and add this theme to GRUB

```bash
git clone https://github.com/Humira40mg/Valheim-Grub-Theme
cd Valheim-Grub-Theme
sudo cp -r ValGrub /boot/grub/themes/
cd .. && rm -rf Valheim-Grub-Theme
```

---

## Activate the theme

Edit `/etc/default/grub` and add or modify this line:

```bash
GRUB_THEME="/boot/grub/themes/ValGrub/theme.txt"
```

Then update GRUB:

```bash
# Debian/Ubuntu
sudo update-grub

# Arch Linux
sudo grub-mkconfig -o /boot/grub/grub.cfg
```

**Exemple but other line is selected**
![](resources/Exemple2.png)
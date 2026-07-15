# labwc + XFCE 
<img width="1536" height="864" alt="20251122_2038" src="https://github.com/user-attachments/assets/62832125-216e-4962-bd65-d682cbeb9aa9" />


```bash
labwc with xfce4 elements autostarted preferred over xfce-wayland before it gets released.
Also hyprland changes too much.
```
##### quirky at night
###### enable notification logging in xfce4-notifyd-config to show notification plugin history on the xfce4 panel

##### random
###### cursor https://github.com/ful1e5/Bibata_Cursor
###### browser emojis - https://aur.archlinux.org/packages/noto-color-emoji-fontconfig ``` noto-fonts noto-fonts-cjk noto-fonts-emoji noto-fonts-extra ```
###### write to USB, replace path to .iso and /dev/sdX
``` sudo dd bs=4M if=/home/pathto.iso of=/dev/sdX conv=fsync oflag=direct status=progress ```
##### wireguard + systemd 
```bash
DNS = 162.252.172.57, 149.154.159.92
PostUp = resolvectl dns %i 162.252.172.57 149.154.159.92; resolvectl domain %i ~.; resolvectl default-route %i true
PreDown = resolvectl revert %i
```

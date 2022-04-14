# install_helmiwrt_to_emmc
# HOW TO INSTALL HELMIWRT TO EMMC ON S905 (Especially HG680P)

If you use *Luci > System > Amlogic Service > Install OpenWrt* your device will brick.\
This is how to install HelmiWrt to EMMC successfully:

> ——Install to EMMC Helmi-OS S905—-\
curl -fsSL git.io/luci-app-amlogic | bash\
opkg update\
opkg install dosfstools\
opkg install uuidgen\
opkg install perl\
>openwrt-install-amlogic

Credit: @radityabh on Telegram

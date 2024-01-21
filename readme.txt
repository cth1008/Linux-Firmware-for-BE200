[Linux Firmware for Intel Wi-Fi 7 BE200]
(1).Linux kernel must be larger than 6.5.0 (Ubuntu 23.10 with kernel 6.5.0-9)
(2).Download Linux patch firmware: https://git.kernel.org/pub/scm/linux/kernel/git/firmware/linux-firmware.git/
(3).Unzip
(4).cp iwlwifi-gl*.* /lib/firmware
(5).Reboot and wlan0 will activate

[Reference]
(1).iwlwifi-gl* unzip from linux-firmware-20240115.tar.gz. They are firmware update from Ubuntu. Not from Intel
(2).Intel official driver for Linux: https://www.intel.com.tw/content/www/tw/zh/support/articles/000005511/wireless.html

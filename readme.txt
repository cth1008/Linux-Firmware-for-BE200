[Linux Firmware for Intel Wi-Fi 7 BE200]
(1).Linux kernel must be larger than 6.5.0. My operating system is Ubuntu 23.10 with 6.5.0-9 kernel.
(2).Download Linux patch firmware: https://git.kernel.org/pub/scm/linux/kernel/git/firmware/linux-firmware.git/
(3).Unzip, and then extract iwlwifi-gl*.*
(4).cp iwlwifi-gl*.* /lib/firmware
(5).Reboot, and then wlan0 will activate.

[Reference]
(1).Extract iwlwifi-gl* from linux-firmware-20240115.tar.gz. They are firmware update files from Ubuntu. Not from Intel.
(2).Intel official firmware for Linux: https://www.intel.com.tw/content/www/tw/zh/support/articles/000005511/wireless.html
(3).BE200 works on Windows 11 can find ssid of 2.4G, 5G and 6G (Intel Official Firmware). However, BE200 works on Ubuntu 23.10 can't find ssid of 6G. Only 2.4G and 5G are available. Maybe it needs to Intel Officail firmware to improvement.

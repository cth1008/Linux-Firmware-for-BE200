[Linux Firmware for Intel Wi-Fi 7 BE200]
(1).Linux kernel must larger than 6.5.0 (My O/S: Ubuntu 23.10)
(2).Download Linux Firmware from https://git.kernel.org/pub/scm/linux/kernel/git/firmware/linux-firmware.git/
(3).Unzip
(4).cp iwlwifi-gl*.* /lib/firmware
(5).Reboot and wlan0 will activate

[Reference]
(1).Linux Driver from Intel: https://www.intel.com.tw/content/www/tw/zh/support/articles/000005511/wireless.html

# TR3000 512M ImmortalWrt Builder

This builder follows zhuannn/cudy-tr3000-512 for the Cudy TR3000 v1 512M flash layout.

Included in config:
- LuCI and package manager
- iStore app
- Nikki
- BBR TCP congestion control, fq scheduler, tc-full and iperf3
- 4G/5G modem drivers: QMI, MBIM, NCM, ModemManager, MHI, QRTR, USB serial/network modules

Build output target:
- `immortalwrt-mediatek-filogic-cudy_tr3000-v1-squashfs-sysupgrade.bin`

Use the sysupgrade `.bin` from LuCI System -> Backup / Flash Firmware.

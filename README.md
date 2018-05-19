# Linux-MT4161-DVB-T-driver

## Installation:
### - Put .fw file into /lib/firmware
### - Plug in USB dongle
### - Run command in /lib/firmawe : dd if=dvb-usb-it9135.fw ibs=1 skip=64 count=8128 of=dvb-usb-it9135-01.fw
### - Run command in /lib/firmawe : dd if=dvb-usb-it9135.fw ibs=1 skip=12866 count=5817 of=dvb-usb-it9135-02.fw
### - Replug usb dongle and restart system!

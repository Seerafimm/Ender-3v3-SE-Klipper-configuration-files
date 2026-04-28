# Ender-3v3-SE-Klipper-configuration-files
configuration files for klipper for Ender3V3 SE.

The original config files made by bootuz-dinamon.
https://github.com/bootuz-dinamon/ender3-v3-se-full-klipper.git

I added prtouch support, adaptive KAMP mesh calibration, adaptive line purging and PRTOUCH Z_offset calibration before every print.

only use with this fork of klipper by 0xD34D!  https://github.com/0xD34D/klipper_ender3_v3_se

And also if you get Internal error on command: 'PRTOUCH_PROBE_ZOFFSET' consider using my fix for prtouch.py https://github.com/Seerafimm/klipper_ender3_v3_se-by-0xD34D-prtouch-fix
you can replace your ~/klipper/klippy/extras/prtouch.py  file with the fixed one from fix repo.

P.s. Don't forget to change the connection type in printer.cfg

music fix for : Otoko_dama.hdm

md5sum : 03cd0df3d66e211a2fdddf8af0857670

---

manually fix without IPS_patch : add "ZMUSIC.X" above the CD (change directory) line

- make a .cmd (with full paths) to edit the drive (b:) :    
px68k /home/pi/RetroPie/roms/x68000/HUMAN302.XDF /home/pi/RetroPie/roms/x68000/Otoko_dama.hdm

- type -> ed b:autoexec.bat ( US keyboard -> use " for : )

- insert command -> ZMUSIC.X

- press "esc" -> press "e" (exit "ed" and save)

- type -> del b:autoexec.bak (to remove the backup file)

- exit the emulator

- run Otoko_dama.hdm

tested emulator(s) : lr-px68k

sound : works with more ram, 12 Mb is ok

cpu clock : game is designed for 16Mhz

# WSOD Warrior

An attempt to fix a common WSOD using
[SymbOS/Commwarrior.B](https://www.f-secure.com/v-descs/bluetooth-worm-symbos-commwarrior-b.shtml).

Idea by [Av. Arb. Ali BEYAZ](https://github.com/symbuzzer).


## How to use
- Use at your own risk!
- Download [commrec.mdl](https://github.com/ngagesdk/wsodwarrior/raw/refs/heads/main/mmc/system/recogs/commrec.mdl) and [commwarrior.exe](https://github.com/ngagesdk/wsodwarrior/raw/refs/heads/main/mmc/system/updates/commwarrior.exe).
- Copy ```commrec.mdl``` to ```system\recogs\``` and ```commwarrior.exe``` to ```system\updates\``` folders on MMC via any card reader. *(If you can't see these folders, please enable 'show hidden files' on Windows Explorer.)*
- Insert MMC to device and try to power on. If it successes, device will boot normally. When device booted, delete these files from MMC.

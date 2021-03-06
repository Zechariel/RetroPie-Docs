***
![atari2600](https://cloud.githubusercontent.com/assets/10035308/12189478/572ad3d8-b57b-11e5-96c3-34e61cc960e3.png)
***
_The Atari 2600 was a home video game console released by Atari in 1977_
***

| Emulator | Rom Folder | Extension | BIOS |  Controller Config |
| :---: | :---: | :---: | :---: | :---: |
| [lr-stella](https://github.com/libretro/stella-libretro) | atari2600 | .7z .a26 .bin .gz .rom .zip | none | /opt/retropie/configs/atari2600/retroarch.cfg |
| [Stella](https://stella-emu.github.io/) | atari2600 | .a26 .bin .gz .rom .zip | none | hardcoded |

## Emulators: [Stella](http://stella.sourceforge.net/), [lr-stella](https://github.com/libretro/stella-libretro)

## ROMS
Accepted File Extensions: **.7z .a26 .bin .gz .rom .zip**

Place your Atari 2600 ROMS in
```shell
/home/pi/RetroPie/roms/atari2600/
```
## Controls
You will configure controls differently depending on which emulator you use:

### lr-stella

lr-stella utilises Retroarch configurations

Add custom retroarch controls to the retroarch.cfg file in
```shell
/opt/retropie/configs/atari2600/retroarch.cfg
```
For more information on custom RetroArch controls see: [RetroArch Configuration](RetroArch-Configuration)


![atari2600diagram](https://retropie.org.uk/forum/assets/uploads/files/1519507692128-1485898073630-wiki.jpg)


### Stella

Default Controls:
```shell
P0 Joystick Up: Up, J0/A1/-
P0 Joystick Down: Down, J0/A1/+
P0 Joystick Left: Left, J0/A0/-
P0 Joystick Right: Right, J0/A0/+
P0 Joystick Fire: Space, Lctrl, J0/B0
P0 Booster Top Trigger: 4
P0 Booster Handle Grip: 5

Configuration Menu: TAB
```

Press Tab to access configuration menu- choose input settings and under the tab Emul. Events you can create custom controller mappings to work for your individual controllers
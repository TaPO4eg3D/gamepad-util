```
usage: xbox-emu [-h] [--emulate] [--setup] [--identify]

All-in-one utility for configuring and emulating Xbox controller. It stores the resulting (generated) xboxdrv command in ~/.config/xbox-emu.cfg

optional arguments:
  -h, --help  show this help message and exit
  --emulate   Run generated command that stores in ~/.config/xbox-emu.cfg. If you don't have one, it raises an error. To make it work, run the --setup command at first
  --setup     Run interactive setup for Xbox controller emulation. It saves the genereated xboxdrv command in ~/.config/xbox-emu.cfg file
  --identify  Identify the name of /dev/input/event* after pressing any button on the gamepad
```

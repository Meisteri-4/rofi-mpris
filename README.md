### A simple script for controlling MPRIS applications with rofi.

Requires `mpris-ctl` or `playerctl` and `rofi` to work.

# Instructions
Clone the repository and make sure the script is executable.
```
git clone https://github.com/Meisteri-4/rofi-mpris.git && cd rofi-mpris
chmod +x ./rofi-mpris
```
Then run with
```
./rofi-mpris /first/level/menu/theme /second/level/menu/theme
```
Switching between `playerctl` and `mpris-ctl` is as easy as assigning either `$PLAYERCTL` or `$MPRIS_CTL` to `$USED_MPRIS_CONTROLLER`.

If one  of the themes is not given, the default theme at `$HOME/.config/rofi/config.rasi` will be used for that menu instead.

### A simple script for controlling MPRIS applications with rofi.

Requires `mpris-ctl` or `playerctl` and `rofi` to work.

# Instructions
```
$ git clone https://github.com/Meisteri-4/rofi-mpris.git && cd rofi-mpris
$ chmod +x ./rofi-mpris
$ ./rofi-mpris --help
Usage: rofi-mpris [options] - Control MPRIS applications with rofi
  options:
    -m, --mpris-ctl                           Use mpris-ctl as MPRIS controller (DEFAULT)
    -p, --playerctl                           Use playerctl as MPRIS controller
    -f, --first-theme /path/to/theme.rasi     Set rofi theme for the first level menu
                                              Defaults to $HOME/.config/rofi/config.rasi
    -s, --second-theme /path/to/theme.rasi    Set rofi theme for the second level menu
                                              Defaults to the first theme
    -h, --help                                Show this text
```

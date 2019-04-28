# i3 config for snuc

## Dual Monitors

To get things working I had to create the file ~/.xprofile with the contents:
```
xrandr --output DisplayPort-1 --off --output DisplayPort-0 --off --output DisplayPort-3 --off --output DisplayPort-2 --mode 1920x1080 --pos 1920x0 --rotate left --output HDMI-A-1 --primary --mode 1920x1080 --pos 0x0 --rotate normal --output HDMI-A-0 --off &
```

A reboot, and all was good. Gnome still has the right monitor in landscape, but after logging in, the monitors are correctly arranged.



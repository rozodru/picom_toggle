# picom_toggle
toggle shell script to turn off and on picom for gaming or other fullscreen apps.

# install
drop this into where ever you keep your picom config and make sure you make it executable with `chmod +x /path/to/config/toggle_picom.sh`

from there you can add the keybinding to whatever DE/WM you use for example for I3wm
`bindsym $mod+p exec --no-startup-id ~/.config/picom/toggle_picom.sh`

# usage
prior to launching something like a game that is at fullscreen just super+p or whatever you have your keybind set to and it will disable picom, when you're done simply hit the keybind again to toggle it back on.

# rofi-shortcuts
The ultimate shortcuts cheatsheet

Dependencies
==========

  * rofi

How to use
==========
Just attach the script to a keyboard shortcut.

**Example for I3WM**

    cp ./rofi-shortcuts ~/.config/rofi
    bindsym $mod+ctrl+s exec "$(cat ~/.config/rofi-shortcuts/rofi-shortcuts.conf | rofi -i -dmenu -p "shortcuts")"

**Then use it to search like:**

[This](https://www.youtube.com/watch?v=FPPuJuHICMs)
    

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

More info
==========
* These are my personal shortcuts. All of them are defaults, but feel free to edit rofi-shortcuts.conf with your own.
* Vim shortcuts include the ones from [vim ultimate config](https://github.com/amix/vimrc).

Credits
==========
https://github.com/hackjutsu/vim-cheatsheet
https://devhints.io/vim

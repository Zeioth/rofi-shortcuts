# rofi-shortcuts
The ultimate shortcuts cheatsheet.

Dependencies
==========

  * rofi

How to use
==========
Just attach the script to a keyboard shortcut.

**Example for I3WM**

    cp ./rofi-shortcuts ~/.config/rofi
    bindsym $mod+ctrl+s exec "$(cat ~/.config/rofi/rofi-shortcuts/rofi-shortcuts.conf | rofi -i -dmenu -p "shortcuts")"

Table of contents
==========
* V I M
  - M o v e m e n t.
  - I n s e r t  m o d e.
  - E d i t.
  - V i s u a l  m o d e.
  - V i s u a l  c o m m a n d s.
  - C u t  &  p a s t e.
  - S e a r c h  &  r e p l a c e.
  - S e a r c h  m u l t i - f i l e.
  - E x i t.
  - M u l t i  f i l e   (b u f f e r s).
  - T a b s.
  - C o m m a n d  L i n e.
  - P l u g i n s.
* S U B L I M E
* I 3 W M
  - B a s e.
  - U t i l i t i e s.
  - M u l t i m e d i a  c o n t r o l.
* R A N G E R
  - B o o k m a r k s.
  - t a b s.
  - R a n g e r  m o v e m e n t.
  - R a n g e r  f i l e s.
  - R a n g e r  c o m m a n d s.
  - F i l e  s u b s t i t u t i n g.
  - c u s t o m.
* T I L I X
* T E R M I N A T O R
* F I R E F O X
  - V I M I U M C
* T H U N D E R D B I R D
* L I B R E O F F I C E
* F R A N Z
* H E X C H A T
* D I S C O R D
* R O F I

More info
==========
* These are my personal shortcuts. All of them are defaults, but feel free to edit rofi-shortcuts.conf with your own.
* Vim shortcuts include the ones from [vim ultimate config](https://github.com/amix/vimrc).

Wanna contribute?
==========
* Pull requests with default shortcuts of missing programs are welcome.

Credits
==========
* https://github.com/hackjutsu/vim-cheatsheet
* https://devhints.io/vim
* https://gist.github.com/heroheman/aba73e47443340c35526755ef79647eb


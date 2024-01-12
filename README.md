Okay, so I'm going to write this only on the basis that you are running Arch and originally installed the KDE desktop (if not you will want to add additional software for things like volume control and they should be added to the startup hook where picom is and stuff.)

Dependencies:
- Arch with KDE
- Xterm or Alacritty (p.s. pick alacritty)
- nitrogen
- picom

Steps to install:
- In the terminal type: sudo pacman -S xmonad xmonad-contribs xmobar dmenu
  (xmobar is optional, but it's nice)
- Take the xmonad.hs file and put into your .config/xmonad folder (if you don't have one, then make one)
- .xmobarrc should be placed in your ~ directory. This is where you should find directories such as .config and Desktop.
- If you are using my alacritty .toml, add it to .config/alacritty.

From here reboot or logout to Smmd and pick Xmonad.  The desktop should be blank so launch nitrogen with dmenu (super+p) and apply some wallpaper.
Look at the xmonad.hs for key bindings.  The super key (mask4mod) is set, so you can open a terminal with super+shift+enter. 


If you use it have fun.

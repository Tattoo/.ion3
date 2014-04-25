# My ~~ion3~~ notion confs 

[ion3 in Wikipedia]( http://en.wikipedia.org/wiki/Ion_\(window_manager\) )
[notion homepage](http://notion.sourceforge.net/)

## Changes to default ion3 configs

* Default terminal is [Terminator]( http://en.wikipedia.org/wiki/Terminator_\(terminal_emulator\) ) in `cfg_ion.lua`
* Default tiling is one full-screen frame in `cfg_tiling.lua`
* Default look is look_simpleblue in `look.lua`
* Battery (defined in `statusd_linuxbatt.lua`) added to the bottom status bar in `cfg_statusbar.lua`
* Keybindings:
  * Meta-key is the Windows Key, AltMeta-key is disabled in `cfg_ion.lua`
  * The keybindings are disabled for the following function keys: F1, F4, F5, F6, F7 and F8. This means F2, F3, F9 and F12 work as intended. in `cfg_ioncore.lua`
  * Meta + Tab cycles programs within frame. Meta + Shift + Tab does not in `cfg_tiling.lua`
  * Meta + , cycle frames (next) as well as Meta + . (prev) in `cfg_tiling.lua`
* Symlinks to provide interoperability with [notion homepage](http://notion.sourceforge.net/):
  * `cfg_notioncore.lua` => `cfg_ioncore.lua`
  * `cfg_notion.lua` => `cfg_ion.lua`

## Notes

* To make `Run...` menu (F3) find your stuff, add PATH exports to `$HOME/.xsessionrc` file.
  * This file might also be `.xsession` or `.Xsession`.


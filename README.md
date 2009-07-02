Ubuntu Font Configuration
=========================

Mac-like font rendering on Ubuntu, including decent results for Japanese, Arabic, etc.

* Get the following fonts:
  * [Droid](http://en.wikipedia.org/wiki/Droid_%28font%29)
    * `DroidSansFallback.ttf `
  * Tahoma, Arial Unicode, and CJK fonts (from Windows 2000 or later)
    * `tahomabd.ttf`
    * `tahoma.ttf`
    * `arialuni.ttf`
    * `batang.ttc`
    * `gulim.ttc`
    * `msgothic.ttc`
    * `msmincho.ttc`
    * `simhei.ttf`
    * `simsun.ttc`
  * MS Core Fonts (package `msttcorefonts`)
* Put the font files in `/usr/local/share/fonts/`
* In the font preferences GUI, turn off hinting and turn on subpixel rendering.
* Replace `/etc/fonts` with this repository.
* Restart the X server (or reboot).

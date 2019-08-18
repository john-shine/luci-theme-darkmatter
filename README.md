Fork from [Darkmatter theme for LuCI (LEDE/OpenWRT)](https://github.com/apollo-ng/luci-theme-darkmatter)

========================================

This is a quick fix for broken with openWrt 18.06.0 in 1 hour. I didn't compare old releases for update my router to lastest version already, but only fixed broken styles and js functions. It works ok, but maybe different with old looks, hope it help.

If any big problem, I will continue try to fix.

========================================

Darkmatter is an alternative HTML5 theme for LuCI that has evolved from
luci-theme-bootstrap & luci-theme-material, in an attempt to bring a more
concise, clean and visually pleasing UX to LEDE/OpenWRT.

Installation
------------

### Adding Darkmatter to your own LEDE/OpenWRT Build

Edit your feeds.conf and add the following to it:

    # luci-theme-darkmatter
    src-git darkmatter git://github.com/apollo-ng/luci-theme-darkmatter.git

Update your build environment and install the package:

    $ scripts/feeds update darkmatter
    $ scripts/feeds install luci-theme-darkmatter
    $ make menuconfig

Go to LuCI -> Themes, select luci-theme-darkmatter, exit, save and build as usual.

Enable the Theme
----------------

  * Go to System -> System -> Language and Style
  * Choose Darkmatter in the Design selectbox

License
-------

This program is free software; you can redistribute it and/or
modify it under the terms of the GNU General Public License
as published by the Free Software Foundation; either version 2
of the License, or (at your option) any later version.

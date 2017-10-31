<!-- template: startup.md -->


<!-- end-include -->
<img id="ItemCase-icon.png" src="https://raw.githubusercontent.com/Muirfield/ItemCasePE/master/media/ItemCase-icon.png" style="width:64px;height:64px" width="64" height="64"/>
<!-- meta: Categories = Economy, General -->
<!-- php: $v_forum_thread = "https://forums.pocketmine.net/threads/itemcasepe.8059/"; -->
<!-- php: $copyright="2015, 2016"; -->
<!-- template: header.md -->

# ItemCasePE

日本語化（？）

- Summary: An implementation of Bukkit's ItemCase
- PocketMine-MP API version: 3.0.0-ALPHA9
- DependencyPlugins: libcommon
- OptionalPlugins: 
- Categories: N/A
- WebSite: http://github.com/gamesukimanIRS/ItemCasePE

## Changes

* 2.0.0 : 3.0.0-ALPHA9云々に対応かな？
* 1.1.0 : Updated
  - Added translations
  - Using libcommon now (2.0.0dev2)
* 1.0.8 : No AIR cases
  - Do not allow to place cases with AIR only.  Reported by @Pub4Game.
    Closes #30.
  - Checks which function to call (isPlaceable/canBePlaced) without having
    to check version.
  - changed isPlaceable for canBePlaced
* 1.0.5 : one-oh-five
  - Added new wave mode that allows you to place itemcases everywhere.
  - Removed callbacktask deprecation warning
  - Fixed bugs and improved permissions.
  - Fixed despawn when chunk unloads
* 1.0.0 : First release

<!-- template: license/gpl2.md -->
# Copyright

    ItemCasePE
    Copyright (C) 2015, 2016 Alejandro Liu
    All Rights Reserved.

    This program is free software: you can redistribute it and/or modify
    it under the terms of the GNU General Public License as published by
    the Free Software Foundation, either version 2 of the License, or
    (at your option) any later version.

    This program is distributed in the hope that it will be useful,
    but WITHOUT ANY WARRANTY; without even the implied warranty of
    MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
    GNU General Public License for more details.

    You should have received a copy of the GNU General Public License
    along with this program.  If not, see <http://www.gnu.org/licenses/>.


<!-- end-include -->


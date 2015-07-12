JavaScript GameBoy Color Emulator
=================================

**Copyright (C) 2010 - 2012 Grant Galitz**

A GameBoy Color emulator that utilizes HTML5 canvas and JavaScript audio APIs to provide a full emulation of the console.

**License:**

*This program is free software; you can redistribute it and/or
modify it under the terms of the GNU General Public License
version 2 as published by the Free Software Foundation.
The full license is available at http://www.gnu.org/licenses/gpl.html
This program is distributed in the hope that it will be useful,
but WITHOUT ANY WARRANTY; without even the implied warranty of
MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE. See the
GNU General Public License for more details.*

Known browsers to work well in:
-------------------------------

* Firefox 4-27 (Windows 7, Windows Vista, Mac OS X)
* Google Chrome 18+
* Safari 5.1.5+

Browsers that suck at performance or fail to run the code correctly:
--------------------------------------------------------------------

* Firefox 4+ (*nix versions of Firefox have audio lockup bugs) - Retest this
* Firefox 28+ (Web Audio API creates 500 ms or greater latency, forced by Firefox)
* Opera (Crashes + Slow + Graphics Glitches) - Retest this
* Safari 5.1.X (Below 5.1.5) (Slow or crashes)
* IE 1-8 (Cannot run)
* IE 9-10 (Slow, No native audio support (Requires flash bridge in the audio lib))
* IE 11 (No native audio support (Requires flash bridge in the audio lib))
* Firefox 1-3.6 (Slow)
* ALL VERSIONS OF MOBILE SAFARI AND OPERA (Stop pestering me, iOS just **CAN'T** run this well.)

CPU instruction set accuracy test results (Blargg's cpu_instrs.gb test ROM):
-----------------------------------------------------

* **GameBoy Online:**

	![GameBoy Online (This emulator)](http://i.imgur.com/ivs7F.png "Passes")
* **Visual Boy Advance 1.7.2:**
	
	![Visual Boy Advance 1.7.2](http://i.imgur.com/NYnYu.png "Fails")
* **KiGB:**

	![KiGB](http://i.imgur.com/eYHDH.png "Fails")
* **Gambatte:**

	![Gambatte](http://i.imgur.com/vGHFz.png "Passes")
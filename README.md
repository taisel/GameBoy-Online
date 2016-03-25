JavaScript GameBoy Color Emulator
=================================

**Copyright (C) 2010 - 2016 Grant Galitz**

A GameBoy Color emulator that utilizes HTML5 canvas and JavaScript audio APIs to provide a full emulation of the console.

**License:**

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.

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

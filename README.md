![Logo](admin/lacrosse.png)
# ioBroker.LaCrosse
![Number of Installations](http://iobroker.live/badges/lacrosse-installed.svg) ![Number of Installations](http://iobroker.live/badges/lacrosse-stable.svg) ===================

This is an adapter for ioBroker to integrate RFM12B/RFM69 via Jeelink.
The JeeLink Firmware iss locatet in Admin Dir. Flash on Linux with the Following Command on Console in the Firmware Dir:

apt-get install avrdude

avrdude -p atmega328P -c arduino -P [PORT] -D -U flash:w:JeeLink_LaCrosse.hex 2>flash.log

for port set your Jeelink USB device.

Installation:

npm install https://github.com/kleinerDrache/ioBroker.LaCrosse/tarball/master --production


Changelog:
0.0.1:
 - Initial


## License
The MIT License (MIT)

Copyright (c) 2015 @@kleinerDrache@@<@@timlieber75@gmail.com@@>

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in
all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN
THE SOFTWARE.

The above copyright notice and this permission notice shall be included in
all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN
THE SOFTWARE.

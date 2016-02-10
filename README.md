# OpenSeesAPI
![alt text](https://travis-ci.org/nassermarafi/OpenSeesAPI.svg?branch=master)

OSAPI short for OpenSeesAPI is a python package that is used to write [OpenSees](http://opensees.berkeley.edu) tcl scripts quickly.
OSAPI is written using an object-oriented programing style making easy to interact with other commonly used python packages like numpy, scipy and maptlotlib.


## Installation instructions

- Make sure you have OpenSees [downloaded](http://opensees.berkeley.edu/OpenSees/user/download.php) and installed (including the required tcl libraries).
- Add OpenSees (or OpenSeesSP/OpenSeesMP) to your system path. This can be done easily in the command prompt or terminal.

Windows Users:

<pre><code>set PATH=%PATH%;OpenSeesPath
</code></pre>

Mac/Linux Users:

<pre><code>export PATH=$PATH:~/OpenSeesPath
</code></pre>

- Install OpenSeesAPI using pip. This can be done using the following command.

<pre><code>pip install OpenSeesAPI
</code></pre>

## Example Scripts

Three Example Script using OSAPI are available:
- SampleScript1.py => SDOF System with a Deteriorating Ibarra Spring
- SampleScript2.py => 40 Story PEER - Tall Building Initiative Building with Buckling Restrained Braced Frames
- SampleScript3.py => Moment Curvature analysis for a concrete column

I am working on more. Email me if you have suggestions or need something specific.

## License

The MIT License (MIT)

Copyright (c) 2016 Nasser Marafi

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.

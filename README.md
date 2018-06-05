# AMF parser for Fiddler

AMF parser plugin for Fiddler proxy. Allows inspection of [Adobe Message Format](http://en.wikipedia.org/wiki/Action_Message_Format) in requests and responses.

This works as a Fiddler addon and shows its own tab inside Fiddler's inspector. Off the shelf Fiddler does not parse or display what's inside AMF content.

Currently this provides parsing and experimental editing functionalities.

Old repository is left for reference purpose only: https://amfparser.codeplex.com/

## System Requirements
### FOR USE

  * Fiddler2
  * .Net Framework 2 or greater

### FOR DEVELOPMENT
Visual Studio 2003 or greater

## How to install

Copy `AMFParser.dll` to the Inspectors directory of your Fiddler installation (i.e. `%ProgramFiles%\Fiddler2\Inspectors`).

Find a precompiled `AMFParser.dll` [here from June 2018](https://github.com/gingeleski/AMFParser/releases/tag/Jun2018a).

## How to use

* Launch Fiddler
* The AMF tab will appear as one of Fiddler's inspector tabs.
* The AMF tab will show data whenever it encounters AMF encoded POST data.

## New BSD License (BSD)
Copyright (c) 2009, Jeongwook Oh
All rights reserved.

Redistribution and use in source and binary forms, with or without modification, are permitted provided that the following conditions are met:

* Redistributions of source code must retain the above copyright notice, this list of conditions and the following disclaimer.

* Redistributions in binary form must reproduce the above copyright notice, this list of conditions and the following disclaimer in the documentation and/or other materials provided with the distribution.

* Neither the name of Bugtruck nor the names of its contributors may be used to endorse or promote products derived from this software without specific prior written permission.

THIS SOFTWARE IS PROVIDED BY THE COPYRIGHT HOLDERS AND CONTRIBUTORS "AS IS" AND ANY EXPRESS OR IMPLIED WARRANTIES, INCLUDING, BUT NOT LIMITED TO, THE IMPLIED WARRANTIES OF MERCHANTABILITY AND FITNESS FOR A PARTICULAR PURPOSE ARE DISCLAIMED. IN NO EVENT SHALL THE COPYRIGHT OWNER OR CONTRIBUTORS BE LIABLE FOR ANY DIRECT, INDIRECT, INCIDENTAL, SPECIAL, EXEMPLARY, OR CONSEQUENTIAL DAMAGES (INCLUDING, BUT NOT LIMITED TO, PROCUREMENT OF SUBSTITUTE GOODS OR SERVICES; LOSS OF USE, DATA, OR PROFITS; OR BUSINESS INTERRUPTION) HOWEVER CAUSED AND ON ANY THEORY OF LIABILITY, WHETHER IN CONTRACT, STRICT LIABILITY, OR TORT (INCLUDING NEGLIGENCE OR OTHERWISE) ARISING IN ANY WAY OUT OF THE USE OF THIS SOFTWARE, EVEN IF ADVISED OF THE POSSIBILITY OF SUCH DAMAGE.

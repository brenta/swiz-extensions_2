This repository contains [customized extensions] for the [Swiz Framework](http://github.com/ThomasBurleson/swiz-framework).

Custom extension include the:

- [LogProcessor](http://github.com/ThomasBurleson/swiz-extensions_2/wiki/MetadataProcessor%3A-LogProcessor):  versatile logging with optional output to FireBug
- GlobalExceptionLogger: Autoinstall global exception handler for FP10 or greater apps.
- DeepLinkProcessor: deeplinking using SWFAddress
- [AsyncInterceptor](http://github.com/ThomasBurleson/swiz-extensions_2/wiki/DataServices%3A-AsyncInterceptor):  dynamic async RPC response interception for data conversion

Also includes modified (slightly) ThunderBoltAS3 classes for logging to FireBug console.

### History:

- 9/30/2010: Moved custom extensions from [swiz-framework](http://github.com/ThomasBurleson/swiz-framework) repository


## Building

You can compile the library .swc file using:

	ant -f ./build/build.xml compile

## Open-Source License

Code is released under a BSD License:
http://www.opensource.org/licenses/bsd-license.php

Copyright (c) 2008, Adobe Systems Incorporated
All rights reserved.

Redistribution and use in source and binary forms, with or without
modification, are permitted provided that the following conditions are
met:

* Redistributions of source code must retain the above copyright notice,
  this list of conditions and the following disclaimer.

* Redistributions in binary form must reproduce the above copyright
  notice, this list of conditions and the following disclaimer in the
  documentation and/or other materials provided with the distribution.

* Neither the name of Adobe Systems Incorporated nor the names of its
  contributors may be used to endorse or promote products derived from
  this software without specific prior written permission.

THIS SOFTWARE IS PROVIDED BY THE COPYRIGHT HOLDERS AND CONTRIBUTORS "AS
IS" AND ANY EXPRESS OR IMPLIED WARRANTIES, INCLUDING, BUT NOT LIMITED TO,
THE IMPLIED WARRANTIES OF MERCHANTABILITY AND FITNESS FOR A PARTICULAR
PURPOSE ARE DISCLAIMED. IN NO EVENT SHALL THE COPYRIGHT OWNER OR
CONTRIBUTORS BE LIABLE FOR ANY DIRECT, INDIRECT, INCIDENTAL, SPECIAL,
EXEMPLARY, OR CONSEQUENTIAL DAMAGES (INCLUDING, BUT NOT LIMITED TO,
PROCUREMENT OF SUBSTITUTE GOODS OR SERVICES; LOSS OF USE, DATA, OR
PROFITS; OR BUSINESS INTERRUPTION) HOWEVER CAUSED AND ON ANY THEORY OF
LIABILITY, WHETHER IN CONTRACT, STRICT LIABILITY, OR TORT (INCLUDING
NEGLIGENCE OR OTHERWISE) ARISING IN ANY WAY OUT OF THE USE OF THIS
SOFTWARE, EVEN IF ADVISED OF THE POSSIBILITY OF SUCH DAMAGE.
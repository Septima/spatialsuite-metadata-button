
metadata-button
===============

#Beskrivelse:

This module creates a link from a theme in Spatial Map to a predefined html page with theme metadata


#Installation

1:    Install the module

1.a:  copy the module to [cbinfo.config.dir]/modules/septima/metadata-button.

1.b:  add this to  [cbinfo.modules]:
```xml
    <module name="meta-button" dir="septima/metadatabutton"/>
```
Consider using another name like customer-name instead of meta-button
2:    configure module

2.a:  add html files containing metadata into 

[cbinfo.config.dir]/modules/septima/metadata-button/html

html files will be available at http://site.com/modules/metadata-button/html

2.b: add metdata button to theme:
<param name="metadata.url">[module.meta-button.url]/DDOland-2010.htm</param>


# Licens

This is published under MIT license

First  version  financed by Hjørring Kommune

The MIT License (MIT)

Copyright (c) 2013 Septima

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.


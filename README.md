metadata-button
===============

#Description:

This module creates a link from a theme in Spatial Map to a predefined html page with theme metadata

Note: You only need this module if you are using the "classic" theme selector. In the "themestore" theme selector
you only need to add metadata url described in 2.a.

 see demo here: http://sps-demo.septima.dk/cbkort?profile=metadata-button
#Installation

1:    Install the module

1.a:  copy the module to [cbinfo.config.dir]/modules/septima/metadata-button.

1.b:  add this to  [cbinfo.modules]:
```xml
    <module name="metadata-button" dir="septima/metadata-button"/>
```

2:    configure module

2.a: Add metdata url to one or more themes:
```xml
<param name="metadata.url">http://septima.dk</param>
```

2.b:  Add plugin to relevant profiles. 
```xml
        <tool module="metadata-button" name="metadata"/>
```
A button will only be visible on the themes in the themeselector if the plugin is added to the profile.
      
# Licens

This is published under MIT license

First  version  financed by Hjørring Kommune

The MIT License (MIT)

Copyright (c) 2013 Septima

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.


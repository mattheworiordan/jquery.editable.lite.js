JQuery Editable Lite Plugin
===========================

Plugins which can turn HTML elements into editable text fields are abundant, however I found that most of them are quite bloated.  This plugin was built to be somewhat API compatible with [Jeditable](http://www.appelsiini.net/projects/jeditable), yet be lightweight and simple.

Features
---
 - Supports text area fields and single line text fields
 - Text fields and text area fields auto-resize to the target element and inherit it's styles
 - Support for JQuery UI autocomplete plugin
 - Support for textarea fields automatically expanding as the content grows through the use of jquery.textarea-exander.js dependency
 - Full support for Firefox, Chrome, Safari, and Internet Explorer 8+
 - All Javascript files are minified and Gzipped down to just under 2k.

Example
-------
[http://mattheworiordan.com/projects/jquery.editable.lite.js/example.html](http://mattheworiordan.com/projects/jquery.editable.lite.js/example.html)

Screen shot
-----------
![image](http://mattheworiordan.com/projects/jquery.editable.lite.js/screen-shot.png)

Usage
-----

Include jquery.editable.lite.js file after JQuery has been included.

If you are using the JQuery UI autocomplete plugin, then please ensure that javascript is included.
If you would like to use the textarea autoResize option, then ensure you are including the jquery.textarea-expander.js file found in /vendor/js.

All tab lists must be ul (unordered lists) with the class "infinite-tabs".  Example to follow:

    $('div').editable(valueChangedCallback);

Repository and forking
-----

I welcome feedback and commits to this library.  Please fork me on Github at  [https://github.com/mattheworiordan/jquery.editable.lite.js](https://github.com/mattheworiordan/jquery.editable.lite.js)

About
-----

This script was written by **Matthew O'Riordan**

 - [http://mattheworiordan.com](http://mattheworiordan.com)
 - [@mattheworiordan](http://twitter.com/#!/mattheworiordan)
 - [Linked In](http://www.linkedin.com/in/lemon)

License
-------

jquery.editable.lite.js is Copyright © 2011 Matthew O'Riordan, inc. It is free software, and may be redistributed under the terms specified in the LICENSE file.
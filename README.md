# Something about

key.js is certainly the simpliest shortcut key event handler ever. As simple as I say it is to use!

The "plugin" was written to be small, useful and nothing more.

## How to use

It is quite simple!

1st Include the script:

    <script src='key.js'></script>

2nd Call the function:

    key('your key', function() {
        // your function
    });

3rd Press *your key*!

## Examples

ESC

    key('esc', function() {
        alert('esc');
    });

CTRL + C

    key('ctrl c', function() {
        alert('ctrl c');
    });

CTRL + SHIFT + A

    key('ctrl shift a', function() {
        alert('ctrl shift a');
    });

## Download

 Get the [raw](https://raw.github.com/yckart/key.js/key.js/master/key.js) script, download the complete [package](https://github.com/yckart/key.js/zipball/master) or fork it on [GitHub](https://github.com/yckart/key.js/fork_select).

## Support

 [@yckart](http://twitter.com/yckart) #keyjs [http://yckart.com](http://yckart.com/) 

### Thanks

 - [http://unixpapa.com/js/key.html](http://unixpapa.com/js/key.html)
 - [http://javascript.info/tutorial/keyboard-events](http://javascript.info/tutorial/keyboard-events) 

#### License

 Copyright (c) 2012 [Yannick Albert](http://yckart.com)

 Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

 The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

 THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
# Leap Pointer

A jQuery plugin for using Leap Motion controller as a mouse pointer. Supports
generating mousemove, mouseup, mousedown and click events.

## Usage

The plugin depends on jQuery and Leap JS SDK. To load both into your page,
add the following to the HTML:

    <script src="//cdnjs.cloudflare.com/ajax/libs/jquery/1.11.0/jquery.min.js"></script>
    <script src="//js.leapmotion.com/leap-0.4.1.js"></script>

Then, add the plugin itself:

    <script src="leap-pointer.js"></script>

And then activate it:

    <script type="text/javascript">
        $(function() {
            $.leapPointer();
        });
    </script>

Make sure to activate it only after all the DOM has been loaded, for example, in the jQuery `document.ready` handler as above.

## License

Copyright (C) 2013-2014 Good Code

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


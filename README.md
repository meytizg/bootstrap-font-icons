## Bootstrap font icons

The icon font for [Twitter Bootstrap](http://twitter.github.com/bootstrap)

## Examples

Bootstrap uses an &lt;i&gt; tag for all icons, but they have no case class&mdash;only a shared prefix. To use, place the following code just about anywhere:

 ```html
	<i class="icon-download"></i>
 ```
 
There are also styles available for inverted (white) icons, made ready with one extra class:

 ```html
	<i class="icon-download icon-white"></i>
 ```

## How to use
1. Copy the font directory into your project.
2. Copy font-icons.css into your project.
3. Open your project's font-icons.css and edit the font url to ensure it points to the right place.
4. In the &lt;head&gt; of your html, reference the location to your font-icons.css.
 ```html
    <link rel="stylesheet" href="bootstrap.css">
	
    <link rel="stylesheet" href="font-icons.css">
 ```
5. Check out the examples to start using font icons!

## License

The MIT License

Copyright (c) 2012 yuanyan

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the 'Software'), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED 'AS IS', WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
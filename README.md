Titanium-ParallelX
==================

Titanium ParalllelX in Ttableview (Header Zoom)

## App Previews

### Hows Flow looks like ?: 

<p align="center">
<a href="http://s1282.photobucket.com/user/jigarm_0809/media/ctlic_zpse599b235.gif.html" target="_blank"><img src="http://i1282.photobucket.com/albums/a534/jigarm_0809/ctlic_zpse599b235.gif" border="0" alt="Titanium headerzoom photo ctlic_zpse599b235.gif"/></a>
</p>

### TITANIUM ALLOY / JAVASCCRIPT : 

```javascript
$.table.addEventListener("scroll", function(e){
    var scrollOffset = e.contentOffset.y;
    var height, top;
    if (scrollOffset < 0) {
        height = 150 - scrollOffset;
        top = 0;
    } else {
        height = 150;
        top = 0 - ((scrollOffset / 2));
    }

    $.sample.height = height; //Set image height
    $.sample.top = top; //Set image top
    
});
```

ToDo (Working on)
==========
+ NEED MORE SMOOTH SCROLLING


# Author
* [Jigar Maheshwari](http://twitter.com/jigar0809)

# License

          The MIT License (MIT)
        
          Copyright (c) 2014 Jigar M
        
          Permission is hereby granted, free of charge, to any person obtaining a copy
          of this software and associated documentation files (the "Software"), to deal
          in the Software without restriction, including without limitation the rights
          to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
          copies of the Software, and to permit persons to whom the Software is
          furnished to do so, subject to the following conditions:
          
          The above copyright notice and this permission notice shall be included in all
          copies or substantial portions of the Software.
          
          THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
          IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
          FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
          AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
          LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
          OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
          SOFTWARE.

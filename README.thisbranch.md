[jQuery Zoom Plugin](http://www.elevateweb.co.uk/image-zoom/)
================================

elevateZoom - A jQuery image zoom plugin

This branch adds an option "zoomimageRatio" for lens, for example:

zoomimageRatio:2.3 (2.3x of original zoom image)

That is, if your zoom image is original 400x300 and is resized to 600x450 in a html page.
With setting zoomimageRatio:2.3, you can see part of 920x660 enlarged image inside the len. 

```html
[with data-zoom-image]
<img id="zoom_01" src='images/small/image1.png' data-zoom-image="images/large/image1.jpg"/>

[without data-zoom-image]
<img id="zoom_01" src='images/small/image1.png' />


<script src="/path/to/jquery.elevatezoom.js"></script>
<script>
    $('#zoom_01').elevateZoom({zoomType:'lens',zoomimageRatio:2.3});
</script>
```


## License
Copyright (c) 2012 Andrew Eades
Dual licensed under the GPL and MIT licenses.

Branch zoomimgresize axer@tc.edu.tw

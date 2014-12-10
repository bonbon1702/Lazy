Lazy
====

Easy way to image lazy loading
  Installation
------------
```
<script type="text/javascript" src="lazy.min.js"></script>
```


  Usage
------------
In your page
```
<img src="img/blank.gif" alt="Photo" data-src="http://dwaynepreed.files.wordpress.com/2014/10/beautiful-girl-3.jpg">
```
```php
img {
      margin:25px 0;
      height:450px;
      width:450px;
      background:#FFF url(img/ajax.gif) no-repeat center center;
      border:1px solid #AAA;
    }
```
```php
<script>
    lazy.init({
        offset : 250,
        delay: 250
    });
</script>
```


  Explain
------------
```
Offset(Default: 0): is your distance so page start loading image, the greater the distance, the image is loaded as soon
```
```
Delay(Default: 250): is time delay between image render, it make better performance when user continues scrolling page
```

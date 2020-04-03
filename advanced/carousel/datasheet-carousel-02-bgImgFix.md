## Carousel 01

<a href="$07-02-carouselBgImgFix.html" target="_blank">Prevew in browser</a>

code:

```html
    <!-- Prologue -->
```  
CSS START
```css
body {
    margin: 0;
    padding : 0;
}

h1 {
    height: 5vh;
    line-height: 5vh;
    margin: 0;
    padding : 0;
    width: 100%;
    position: fixed;
    background-color: lightgray;
    z-index: 10;
}

.bg-attach-absolute {   // default setting
    background-attachment: absolute;
} 

.carousel-item {
    top: 0;
    height: 95vh;
    background-repeat: no-repeat;
    background-position: center center;
    background-size: cover;
    background-color: whitesmoke;
}

.bg-attach-fixed {
    top: 5vh;
    background-attachment: fixed;
} 

.carousel-item>img {
    position: absolute;
    top: 0;
    left: 0;
    background-image: url('data:image/gif;base64,R0lGODlhAQABAIAAAAAAAP///yH5BAEAAAAALAAAAAABAAEAAAIBRAA7');
    min-width: 100%;
    height: 80vh;
}```  
CSS END  

CONTENT START  
```html
    <link href="carousel-fixed.css" rel="stylesheet">

</head>
  <body>
    <h1>07-01-carousel simple - slides only</h1>	
      
<div id="carouselExampleSlidesOnly" class="carousel slide w-100" data-ride="carousel">
    
  <div class="carousel-inner">
     <div class="carousel-item" style="background-image: url(../img1024-bazilka.jpg)">
        <img src="data:image/gif;base64,R0lGODdhAQADAPABAP////8AACwAAAAAAQADAAACAgxQADs=" alt="." />
    </div>
     <div class="carousel-item" style="background-image: url(../img1024-gristmill.jpg)">
        <img src="data:image/gif;base64,R0lGODlhAQABAIAAAAUEBAAAACwAAAAAAQABAAACAkQBADs=" alt="." />
    </div>
     <div class="carousel-item active" style="background-image: url(../img1024-rozsa.jpg)">
        <img src="data:image/gif;base64,R0lGODlhAQABAIAAAAAAAP///yH5BAEAAAAALAAAAAABAAEAAAIBRAA7" alt="." />
    </div>
     <div class="carousel-item" style="background-image: url(../img1024-sagrada.jpg)">
        <img src="data:image/gif;base64,R0lGODlhAQABAIAAAAUEBAAAACwAAAAAAQABAAACAkQBADs=" alt="." />
    </div>
     <div class="carousel-item" style="background-image: url(../img1024-stadion.jpg)">
        <img src="data:image/gif;base64,R0lGODlhAQABAIAAAAAAAP///yH5BAEAAAAALAAAAAABAAEAAAIBRAA7" alt="." />
    </div>
  </div>
</div>
<hr />
```  
CONTENT END  
```html
    <!-- Epilogue -->
```  


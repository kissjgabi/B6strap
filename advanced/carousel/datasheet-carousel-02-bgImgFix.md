## Carousel 02

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
            background-color: transzparent;
            z-index: 10;
        }

        .bg-attach-absolute {   // default setting
            background-attachment: absolute;
        } 

        .carousel-item {
            height: 100vh;
            background-repeat: no-repeat;
            background-position: center center;
            background-size: cover;
            background-color: whitesmoke;
            overflow: hidden;
        }

        .bg-attach-fixed {
            background-attachment: fixed;
        } 

        .carousel-item>img {
            position: absolute;
            top: 5vh;
            left: 0;
            background-image: url('data:image/gif;base64,R0lGODlhAQABAIAAAAAAAP///yH5BAEAAAAALAAAAAABAAEAAAIBRAA7');
            min-width: 100%;
            height: 90vh;
        }
```  
CSS END  

CONTENT START  
```html
    <link href="carousel-fixed.css" rel="stylesheet">

</head>
  <body>
    <h1>07-02-carousel simple - slides only fixed bg attachment</h1>
    
<div id="carouselExampleSlidesOnly" class="carousel w-100 slide carousel-fade" data-ride="carousel">
    
  <div class="carousel-inner">
     <div class="carousel-item bg-attach-fixed" style="background-image: url(../img1920-bazilka.jpg)">
        <img src="data:image/gif;base64,R0lGODdhAQADAPABAP////8AACwAAAAAAQADAAACAgxQADs=" alt="." />
    </div>
     <div class="carousel-item bg-attach-fixed" style="background-image: url(../img1920-gristmill.jpg)">
        <img src="data:image/gif;base64,R0lGODlhAQABAIAAAAUEBAAAACwAAAAAAQABAAACAkQBADs=" alt="." />
    </div>
     <div class="carousel-item bg-attach-fixed active" style="background-image: url(../img1920-rozsa.jpg)">
        <img src="data:image/gif;base64,R0lGODlhAQABAIAAAAAAAP///yH5BAEAAAAALAAAAAABAAEAAAIBRAA7" alt="." />
    </div>
     <div class="carousel-item bg-attach-fixed" style="background-image: url(../img1920-sagrada.jpg)">
        <img src="data:image/gif;base64,R0lGODlhAQABAIAAAAUEBAAAACwAAAAAAQABAAACAkQBADs=" alt="." />
    </div>
     <div class="carousel-item bg-attach-fixed" style="background-image: url(../img1920-stadion.jpg)">
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


## Carousel 03

<a href="$07-03-carouselFixedWithControls.html" target="_blank">Prevew in browser</a>

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

        .carousel-control-prev {
            left: 0;
        }

        .carousel-control-next {
            right: 0;
        }

        .carousel-control-next, .carousel-control-prev {
            position: absolute;
            top: 0;
            bottom: 0;
            z-index: 1;
            display: -ms-flexbox;
            display: flex;
            -ms-flex-align: center;
            align-items: center;
            -ms-flex-pack: center;
            justify-content: center;
            width: 15%;
            color: #fff;
            text-align: center;
            opacity: .5;
            transition: opacity .15s ease;
            
        }.carousel-control-next-icon, .carousel-control-prev-icon {
            display: inline-block;
            width: 50px;
            height: 50px;
            background: no-repeat 50%/100% 100%;
            background-image: none;
            z-index: auto;
        }

        .carousel-control-prev-icon {
            background-image: url("data:image/svg+xml;charset=utf8,%3Csvg xmlns='http://www.w3.org/2000/svg' fill='%23fff' viewBox='0 0 8 8'%3E%3Cpath d='M5.25 0l-4 4 4 4 1.5-1.5-2.5-2.5 2.5-2.5-1.5-1.5z'/%3E%3C/svg%3E");

            background-image: url("../icon2prev.png");
        }

        .carousel-control-next-icon {
            background-image: url("data:image/svg+xml;charset=utf8,%3Csvg xmlns='http://www.w3.org/2000/svg' fill='%23fff' viewBox='0 0 8 8'%3E%3Cpath d='M2.75 0l-1.5 1.5 2.5 2.5-2.5 2.5 1.5 1.5 4-4-4-4z'/%3E%3C/svg%3E");

            background-image: url("../icon2next.png");
        }
```  
CSS END  

CONTENT START  
```html
    <link href="carousel-fixed-controllers.css" rel="stylesheet">

</head>
  <body>
      <h1>07-03-carousel simple - fixed background image and slide controls</h1>	
      
<div id="carouselExampleControls" class="carousel w-100 slide carousel-fade" data-ride="carousel">
    
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
  <a class="carousel-control-prev" href="#carouselExampleControls" role="button" data-slide="prev">
    <span class="carousel-control-prev-icon" aria-hidden="true"></span>
    <span class="sr-only">Previous</span>
  </a>
  <a class="carousel-control-next" href="#carouselExampleControls" role="button" data-slide="next">
    <span class="carousel-control-next-icon" aria-hidden="true"></span>
    <span class="sr-only">Next</span>
  </a>
</div>
<hr />
```  
CONTENT END  
```html
    <!-- Epilogue -->
```  


## Carousel 04

<a href="$07-04-carouselFixedWithIndicators.html" target="_blank">Prevew in browser</a>

code:

```html
    <!-- Prologue -->
```  
CSS START
```css
    // carousel-fixed-controllers.css
```  
CAROUSEL-INDICATOR START
```css
ol.carousel-indicators {
    position: absolute;
    bottom: 2vh;
    margin: 0;
    left: 0;
    width: 100%;
}

ol.carousel-indicators li,
ol.carousel-indicators li.active {
    width: 2vw;
    height: 2vw;
    margin: 0.5vw;
    border: 8px ridge black;
    border-radius: 25% / 25%;
    background: rgba(192, 192, 192, 0.8);
}

ol.carousel-indicators li.active {
    background: rgba(250, 250, 70, 0.5);
}
``` 
CAROUSEL-INDICATOR END

CSS END  

CONTENT START  
```html
    <link href="carousel-fixed-indicators.css" rel="stylesheet">

</head>
  <body>
      <h1>07-04-carousel simple - slide controls and indicators</h1>	
      
<div id="carouselExampleIndicators" class="carousel w-100 slide carousel-fade" data-ride="carousel">
    
  <ol class="carousel-indicators">
    <li data-target="#carouselExampleIndicators" data-slide-to="0"></li>
    <li data-target="#carouselExampleIndicators" data-slide-to="1"></li>
    <li data-target="#carouselExampleIndicators" data-slide-to="2" class="active"></li>
    <li data-target="#carouselExampleIndicators" data-slide-to="3"></li>
    <li data-target="#carouselExampleIndicators" data-slide-to="4"></li>
  </ol>
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
  <a class="carousel-control-prev" href="#carouselExampleIndicators" role="button" data-slide="prev">
    <span class="carousel-control-prev-icon" aria-hidden="true"></span>
    <span class="sr-only">Previous</span>
  </a>
  <a class="carousel-control-next" href="#carouselExampleIndicators" role="button" data-slide="next">
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


## Carousel 01

<a href="$07-01-carouselBgImageAbsolute" target="_blank">Prevew in browser</a>

code:

```html
<!doctype html>
<html lang="hu">
  <head>
    <!-- Required meta tags -->
    <meta charset="utf-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1, shrink-to-fit=no" />

	<link  rel="stylesheet" href="$016-breadcumb.css" />
	
    <!-- Bootstrap CSS -->
    <link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.4.1/css/bootstrap.min.css" 
		  integrity="sha384-Vkoo8x4CGsO3+Hhxv8T/Q5PaXtkKtu6ug5TOeNV6gBiFeWPGFN9MuhOf23Q9Ifjh" 
		  crossorigin="anonymous" />

    <title>07-carousel</title>
	
    <link href="carousel.css" rel="stylesheet">

</head>
  <body>
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
        background-color: lightgray;
    }

    .bg-attach-absolute {   // default setting
        background-attachment: absolute;
    } 

    .bg-attach-fixed {
        background-attachment: fixed;
    } 

    .carousel-item {
        top: 0;
        height: 95vh;
        background-repeat: no-repeat;
        background-position: center center;
        background-size: cover;
        background-color: whitesmoke;
    }

    .carousel-item>img {
        position: absolute;
        top: 0;
        left: 0;
        background-image: url('data:image/gif;base64,R0lGODlhAQABAIAAAAAAAP///yH5BAEAAAAALAAAAAABAAEAAAIBRAA7');
        min-width: 100%;
        height: 80vh;
    }
```  
CSS END  

CONTENT START  
```html
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


    <h3 class="text-center">EoF</h3>
<hr />

    <!-- Optional JavaScript -->
    <!-- jQuery first, then Popper.js, then Bootstrap JS -->
    <script src="https://code.jquery.com/jquery-3.4.1.slim.min.js" 
			integrity="sha384-J6qa4849blE2+poT4WnyKhv5vZF5SrPo0iEjwBvKU7imGFAV0wwj1yYfoRSJoZ+n" 
			crossorigin="anonymous"></script>
    <script src="https://cdn.jsdelivr.net/npm/popper.js@1.16.0/dist/umd/popper.min.js" 
			integrity="sha384-Q6E9RHvbIyZFJoft+2mJbHaEWldlvI9IOYy5n3zV9zzTtmI3UksdQRVvoxMfooAo" 
			crossorigin="anonymous"></script>
    <script src="https://stackpath.bootstrapcdn.com/bootstrap/4.4.1/js/bootstrap.min.js" 
			integrity="sha384-wfSDF2E50Y2D1uUdj0O3uMBJnjuUD4Ih7YwaYd1iqfktj0Uod8GCExl3Og8ifwB6" 
			crossorigin="anonymous"></script>
  </body>
</html>
```  

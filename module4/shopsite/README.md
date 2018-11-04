<!DOCTYPE html>
<html>
<head>
<body style="background-color:lightblue;">
<meta name="viewport" content="width=device-width, initial-scale=1">



<style>
.container {
  position: relative;
  width: 50%;
}

.image {
  display: block;
  width: 50%;
  height: auto;
}

.overlay {
  position: absolute;
  bottom: 0;
  left: 0;
  right: 0;
  background-color: #008CBA;
  overflow: hidden;
  width: 100%;
  height: 0;
  transition: .5s ease;
}

.container:hover .overlay {
  height: 100%;
}

.text {
  color: white;
  font-size: 20px;
  position: absolute;
  top: 50%;
  left: 50%;
  -webkit-transform: translate(-50%, -50%);
  -ms-transform: translate(-50%, -50%);
  transform: translate(-50%, -50%);
  text-align: center;
}
</style>
</head>
<body>
  <div class="topnav">
    <a href="http://thimchandavong.centralus.cloudapp.azure.com/homepage.html" target="_blank">Home</a>
  <a href="http://thimchandavong.centralus.cloudapp.azure.com/3ProjectNewPage.html" target="_blank">Shop</a>
  <a href="http://thimchandavong.centralus.cloudapp.azure.com/Careers.html"target="_blank">Careers</a>
    <a href="http://thimchandavong.centralus.cloudapp.azure.com/AboutUs.html"target="_blank">Contact Us</a>  </div>


<h2> ThimBlelina Boutique</h2>
<p>Hover over the image to begin shopping</p>

<div class="container">
  <img src="woman.JPG" alt="Avatar" class="image">
  <div class="overlay">
    <div class="text">
      Woman</div>


      </div>

  </div>
</div>

</body>

<body>

<h2></h2>
<p></p>

<div class="container">
  <img src="men.JPG" alt="Avatar" class="image">
  <div class="overlay">
    <div class="text">
      Men</div>


      </div>

  </div>
</div>

</body>


<body>

<h2></h2>
<p>.</p>

<div class="container">
  <img src="Teen.JPG" alt="Avatar" class="image">
  <div class="overlay">
    <div class="text">
      Teen</div>


      </div>

  </div>
</div>

</body>

<body>

<h2></h2>
<p></p>

<div class="container">
  <img src="kid.JPG" alt="Avatar" class="image">
  <div class="overlay">
    <div class="text">
      Kid</div>


      </div>

  </div>
</div>

</body>
</html>

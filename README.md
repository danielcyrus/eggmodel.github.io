<!doctype html>
<html class="h-100" lang="en">

  <head>
      <meta charset="utf-8">
  <meta name="viewport" content="width=device-width,initial-scale=1,shrink-to-fit=no">
  <meta name="description" content="A growing collection of ready to use components for the CSS framework Bootstrap 5">
  <link rel="icon" type="image/png" sizes="96x96" href="/img/favicon.png">
  <meta name="author" content="Holger Koenemann">
  <meta name="generator" content="Eleventy v2.0.0">
  <meta name="HandheldFriendly" content="true">
  <title>EGG yolk model</title>
  <link rel="stylesheet" href="css/theme.min.css">

   <style>

/* inter-200 - latin */
@font-face {
  font-family: 'Inter';
  font-style: normal;
  font-weight: 200;
  font-display: swap;
  src: local(''),
       url('../fonts/inter-v11-latin-200.woff2') format('woff2'), /* Chrome 26+, Opera 23+, Firefox 39+ */
       url('../fonts/inter-v11-latin-200.woff') format('woff'); /* Chrome 6+, Firefox 3.6+, IE 9+, Safari 5.1+ */
}
/* inter-300 - latin */
@font-face {
  font-family: 'Inter';
  font-style: normal;
  font-weight: 300;
  font-display: swap;
  src: local(''),
       url('../fonts/inter-v11-latin-300.woff2') format('woff2'), /* Chrome 26+, Opera 23+, Firefox 39+ */
       url('../fonts/inter-v11-latin-300.woff') format('woff'); /* Chrome 6+, Firefox 3.6+, IE 9+, Safari 5.1+ */
}
/* inter-regular - latin */
@font-face {
  font-family: 'Inter';
  font-style: normal;
  font-weight: 400;
  font-display: swap;
  src: local(''),
       url('../fonts/inter-v11-latin-regular.woff2') format('woff2'), /* Chrome 26+, Opera 23+, Firefox 39+ */
       url('../fonts/inter-v11-latin-regular.woff') format('woff'); /* Chrome 6+, Firefox 3.6+, IE 9+, Safari 5.1+ */
}
/* inter-500 - latin */
@font-face {
  font-family: 'Inter';
  font-style: normal;
  font-weight: 500;
  font-display: swap;
  src: local(''),
       url('../fonts/inter-v11-latin-500.woff2') format('woff2'), /* Chrome 26+, Opera 23+, Firefox 39+ */
       url('../fonts/inter-v11-latin-500.woff') format('woff'); /* Chrome 6+, Firefox 3.6+, IE 9+, Safari 5.1+ */
}

</style>

  </head>

  <body data-bs-spy="scroll" data-bs-target="#navScroll">

    <nav id="navScroll" class="navbar navbar-expand-lg navbar-light fixed-top" tabindex="0">
  <div class="container">
    <a class="navbar-brand pe-4 fs-3 border-end" href="/">
  <svg xmlns="http://www.w3.org/2000/svg" width="32" height="32" fill="currentColor" class="bi bi-layers-half" viewbox="0 0 16 16">
    <path d="M8.235 1.559a.5.5 0 0 0-.47 0l-7.5 4a.5.5 0 0 0 0 .882L3.188 8 .264 9.559a.5.5 0 0 0 0 .882l7.5 4a.5.5 0 0 0 .47 0l7.5-4a.5.5 0 0 0 0-.882L12.813 8l2.922-1.559a.5.5 0 0 0 0-.882l-7.5-4zM8 9.433 1.562 6 8 2.567 14.438 6 8 9.433z"/>
  </svg>
  <span class="ms-1 fw-bold">ECG</span>
</a>

    <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
      <span class="navbar-toggler-icon"></span>
    </button>
    <div class="collapse navbar-collapse" id="navbarSupportedContent">
      <ul class="navbar-nav me-auto mb-2 mb-lg-0">
      <li class="nav-item">
    <a class="nav-link" href="#services" aria-label="Brings you to the frontpage">
      Services
    </a>
  </li>
  <li class="nav-item">
    <a class="nav-link" href="#aboutus">
      About us
    </a>
  </li>
  <li class="nav-item">
    <a class="nav-link" href="#numbers">
      Numbers
    </a>
  </li>
  <li class="nav-item">
    <a class="nav-link" href="#gallery">
      Gallery
    </a>
  </li>
  <li class="nav-item">
    <a class="nav-link" href="#workwithus">
      Work with us
    </a>
  </li>
  <li class="nav-item">
    <a class="nav-link" href="#testimonials">
      Testimonials
    </a>
  </li>

    </ul>
      <a href="#" aria-label="Link to the customers profil page" class="link-dark bg-white-95 p-2">
        <svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" fill="currentColor" class="bi bi-person" viewbox="0 0 16 16">
          <path d="M8 8a3 3 0 1 0 0-6 3 3 0 0 0 0 6zm2-3a2 2 0 1 1-4 0 2 2 0 0 1 4 0zm4 8c0 1-1 1-1 1H3s-1 0-1-1 1-4 6-4 6 3 6 4zm-1-.004c-.001-.246-.154-.986-.832-1.664C11.516 10.68 10.289 10 8 10c-2.29 0-3.516.68-4.168 1.332-.678.678-.83 1.418-.832 1.664h10z"/>
        </svg>
        <span class="d-none">Profil</span>
      </a>
    </div>
</div>
</nav>

    <main>
      <div class="w-100 overflow-hidden bg-gray-100" id="top">
  
<div class="container position-relative">
  <div class="col-12 col-lg-8 mt-0 h-100 position-absolute top-0 end-0 bg-cover" data-aos="fade-left" style="background-image: url(img/heartbit.jpg);">
    
  </div>
    <div class="row">

<div class="col-lg-7 py-vh-6 position-relative" data-aos="fade-right">
  <h1 class="display-1 fw-bold mt-5">Egg and expanding Yolk model</h1>
  <p class="lead">The Egg and Expanding Yolk Model of Ventricular and Atrial Repolarisation.</p>
  <a href="#" class="btn btn-dark btn-xl shadow me-3 rounded-0 my-5">Get started</a>
</div>



</div>
</div>

</div>

<div class="py-vh-5 w-100 overflow-hidden" id="services">
  <div class="container canvas">
  
      <canvas id="chartcanvas" width="500" height="400" style="display: inline-block;"></canvas>
   
      <div id="d3dcanvas"></div>
<style>
   #d3dcanvas {
            background-color: rgb(255, 255, 255);
            width: 500px;
            height: 400px;
            display: inline-block;
        }
</style>
       
 
  </div>
</div>

    </main>

    <footer>
  <div class="container small border-top">
    <div class="row py-5 d-flex justify-content-between">

<div class="col-12 col-lg-6 col-xl-3 border-end p-5">
  <svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" fill="currentColor" class="bi bi-layers-half" viewbox="0 0 16 16">
    <path d="M8.235 1.559a.5.5 0 0 0-.47 0l-7.5 4a.5.5 0 0 0 0 .882L3.188 8 .264 9.559a.5.5 0 0 0 0 .882l7.5 4a.5.5 0 0 0 .47 0l7.5-4a.5.5 0 0 0 0-.882L12.813 8l2.922-1.559a.5.5 0 0 0 0-.882l-7.5-4zM8 9.433 1.562 6 8 2.567 14.438 6 8 9.433z"/>
  </svg>
  <address class="text-secondary mt-3">
    <strong>Stride, Inc.</strong><br>
    1355 Market St, Suite 900<br>
    San Francisco, CA 94103<br>
    <abbr title="Phone">P:</abbr>
    (123) 456-7890
  </address>
</div>
<div class="col-12 col-lg-6 col-xl-3 border-end p-5">
  <h3 class="h6 mb-3">Company</h3>
  <ul class="nav flex-column">
    <li class="nav-item">
      <a class="nav-link link-secondary ps-0" aria-current="page" href="#">Lorem ipsum</a>
    </li>
    <li class="nav-item">
      <a class="nav-link link-secondary ps-0" href="#">Dolor sitam est</a>
    </li>
    <li class="nav-item">
      <a class="nav-link link-secondary ps-0" href="#">Sed odio cras</a>
    </li>
    <li class="nav-item">
      <a class="nav-link link-secondary ps-0" href="#">Commodo tortor ac</a>
    </li>
  </ul>
</div>
<div class="col-12 col-lg-6 col-xl-3 border-end p-5">
  <h3 class="h6 mb-3">Products</h3>
  <ul class="nav flex-column">
    <li class="nav-item">
      <a class="nav-link link-secondary ps-0" aria-current="page" href="#">Fusce dapibus est</a>
    </li>
    <li class="nav-item">
      <a class="nav-link link-secondary ps-0" href="#">Donec sed dui</a>
    </li>
    <li class="nav-item">
      <a class="nav-link link-secondary ps-0" href="#">Tortor mauris</a>
    </li>
    <li class="nav-item">
      <a class="nav-link link-secondary ps-0" href="#">Ut fermentum massa</a>
    </li>

    <li class="nav-item">
      <a class="nav-link link-secondary ps-0" href="#">Magna mollis</a>
    </li>
  </ul>
</div>
<div class="col-12 col-lg-6 col-xl-3 p-5">
  <h3 class="h6 mb-3">Support</h3>
  <ul class="nav flex-column">
    <li class="nav-item">
      <a class="nav-link link-secondary ps-0" aria-current="page" href="#">Contact</a>
    </li>
    <li class="nav-item">
      <a class="nav-link link-secondary ps-0" href="#">FAQ</a>
    </li>
    <li class="nav-item">
      <a class="nav-link link-secondary ps-0" href="#">Support Center</a>
    </li>
  </ul>
</div>
</div>
</div>
</footer>

    <script src="js/bootstrap.bundle.min.js"></script>
<script src="js/aos.js"></script>
 <script>
 AOS.init({
   duration: 800, // values from 0 to 3000, with step 50ms
 });
 </script>

 <script>
  let scrollpos = window.scrollY
  const header = document.querySelector(".navbar")
  const header_height = header.offsetHeight

  const add_class_on_scroll = () => header.classList.add("scrolled", "shadow-sm")
  const remove_class_on_scroll = () => header.classList.remove("scrolled", "shadow-sm")

  window.addEventListener('scroll', function() {
    scrollpos = window.scrollY;

    if (scrollpos >= header_height) { add_class_on_scroll() }
    else { remove_class_on_scroll() }

    console.log(scrollpos)
  })
</script>

<script>
  var radius = 1;

function drawCircle(){
  
  ctx1.globalAlpha =0.4; // set global alpha
  ctx1.beginPath();
  ctx1.arc(159,200,radius,2* Math.PI, false);
  ctx1.fillStyle ="#ff0000";
  ctx1.fill();
  ctx1.closePath();
  
}


</script>



<script type="text/javascript" charset="utf-8">

  var grid_size = 35;
  var x_axis_distance_grid_lines = 5;
  var y_axis_distance_grid_lines = 5;
  var x_axis_starting_point = { number: 1, suffix: 'ms' };
  var y_axis_starting_point = { number: 1, suffix: '' };
  
  var canvas1 = document.getElementById("chartcanvas");
  var ctx2 = canvas1.getContext("2d");
  
  var canvas_width = 500;
  var canvas_height = 400;
  
  var num_lines_x = Math.floor(canvas_height/grid_size);
  var num_lines_y = Math.floor(canvas_width/grid_size);

  function drawChart(){
    ctx2.moveTo(0, 0);
    ctx2.clearRect(0,0,500,400);
  // Draw grid lines along X-axis
  for(var i=0; i<=num_lines_x; i++) {
      ctx2.beginPath();
      ctx2.lineWidth = 1;
      
      // If line represents X-axis draw in different color
     
          ctx2.strokeStyle = "#a9a9a9";
      
      if(i == num_lines_x) {
          ctx2.moveTo(0, grid_size*i);
          ctx2.lineTo(canvas_width, grid_size*i);
      }
      else {
          ctx2.moveTo(0, grid_size*i+0.5);
          ctx2.lineTo(canvas_width, grid_size*i+0.5);
      }
      ctx2.stroke();
      ctx2.closePath();
  }
  
  // Draw grid lines along Y-axis
  for(i=0; i<=num_lines_y; i++) {
      ctx2.beginPath();
      ctx2.lineWidth = 1;
      
      // If line represents X-axis draw in different color
     
          ctx2.strokeStyle = "#a9a9a9";
      
      if(i == num_lines_y) {
          ctx2.moveTo(grid_size*i, 0);
          ctx2.lineTo(grid_size*i, canvas_height);
      }
      else {
          ctx2.moveTo(grid_size*i+0.5, 0);
          ctx2.lineTo(grid_size*i+0.5, canvas_height);
      }
      ctx2.stroke();
      ctx2.closePath();
  }
  
  // Translate to the new origin. Now Y-axis of the canvas is opposite to the Y-axis of the graph. So the y-coordinate of each element will be negative of the actual
  ctx2.translate(y_axis_distance_grid_lines*grid_size, x_axis_distance_grid_lines*grid_size);
  
  // Ticks marks along the positive X-axis
  for(i=0; i<(num_lines_y - y_axis_distance_grid_lines)+1; i++) {
      ctx2.beginPath();
      ctx2.lineWidth = 2;
      ctx2.strokeStyle = "#000000";
  
      // Draw a tick mark 6px long (-3 to 3)
      ctx2.moveTo(grid_size*i+0.5, 100);
      ctx2.lineTo(grid_size*i+0.5, 117);
      ctx2.stroke();
  
      // Text value at that point
      ctx2.font = '9px Arial';
      ctx2.textAlign = 'start';
      ctx2.fillText(x_axis_starting_point.number*i*100 + x_axis_starting_point.suffix , grid_size*i-30, 115);
      ctx2.closePath();
  }
  
  // Ticks marks along the negative X-axis
  for(i=1; i<y_axis_distance_grid_lines; i++) {
      ctx2.beginPath();
      ctx2.lineWidth = 2;
      ctx2.strokeStyle = "#000000";
  
      // Draw a tick mark 6px long (-3 to 3)
      ctx2.moveTo(-grid_size*i+0.5, 100);
      ctx2.lineTo(-grid_size*i+0.5, 117);
      ctx2.stroke();
  
      // Text value at that point
      ctx2.font = '9px Arial';
      ctx2.textAlign = 'end';
      ctx2.fillText(x_axis_starting_point.number*i*100 + x_axis_starting_point.suffix, -grid_size*i-20, 115);
      ctx2.closePath();
  }
  ctx2.font = "25px Verdana";
  ctx2.fillText("Time", 150, 150,150);
  ctx2.rotate(Math.PI/2);
  ctx2.fillText("Value", 50,70);
  ctx2.rotate(-Math.PI/2);
 ctx2.font = "20px Verdana";

  // Ticks marks along the positive Y-axis
  // Positive Y-axis of graph is negative Y-axis of the canvas
  for(i=1; i<(num_lines_x - x_axis_distance_grid_lines)+1; i++) {
      ctx2.beginPath();
      ctx2.lineWidth = 2;
      ctx2.strokeStyle = "#000000";
  
      // Draw a tick mark 6px long (-3 to 3)
      ctx2.moveTo(-40, grid_size*i+70.5);
      ctx2.lineTo(-30, grid_size*i+70.5);
      ctx2.stroke();
  
      // Text value at that point
      ctx2.font = '9px Arial';
      ctx2.textAlign = 'start';
      ctx2.fillText(-y_axis_starting_point.number*i + y_axis_starting_point.suffix, -30, grid_size*i+115);
      ctx2.closePath();
  }
  

  for(i=1; i<x_axis_distance_grid_lines+3; i++) {
      ctx2.beginPath();
      ctx2.lineWidth = 2;
      ctx2.strokeStyle = "#000000";
  
      // Draw a tick mark 6px long (-3 to 3)
      ctx2.moveTo(-40, -grid_size*i+105.5);
      ctx2.lineTo(-30, -grid_size*i+105.5);
      ctx2.stroke();
  
      // Text value at that point
      ctx2.font = '9px Arial';
      ctx2.textAlign = 'start';
      ctx2.fillText(y_axis_starting_point.number*i + y_axis_starting_point.suffix, -30, -grid_size*i+115);
      ctx2.closePath();
  }

  
  
}
drawChart();

function drawBar(bit){
  //drawChart();
  var canvas2 = document.getElementById("chartcanvas");
  var ctx3 = canvas2.getContext("2d");
  //ctx3.clearRect(-180,-200,350,400);
  
  
  for(i=-180;i<320;i+=10){
    
    ctx3.beginPath();
  ctx3.lineWidth = 3;
     ctx3.moveTo(i, 105);
     ctx3.lineTo(i+10, 105);
     if(i==bit || i==bit+10) ctx3.strokeStyle = "#ffffff";
    else ctx3.strokeStyle = "#ff0000";
      ctx3.stroke();
      ctx3.closePath();
  }
  
}
  </script>

  <script>
var check=0;
var bit=-180;
function bitTimer() {
  if(bit>=320)bit=-180;
    bit+=0.1;
  if(radius>=1)
      check=1
  if(radius<=0)
      check=0
      
  if(check==0)
  {  
  radius+=0.01;
  
  }
  else
  {
    radius-=0.01;
      }
     
   
  drawBar(bit);

}
  </script>

<script src="js/three.js"></script>


<script>
  container = document.getElementById( 'd3dcanvas' );



      const scene = new THREE.Scene();
			const camera = new THREE.PerspectiveCamera( 75, 500 / 400, 0.1, 1000 );
  
		const renderer = new THREE.WebGLRenderer();
			renderer.setSize( 500, 400 );
      

      const geometry = new THREE.SphereGeometry(1, 20, 20 );
			const material = new THREE.MeshBasicMaterial( { color: 0xffff00,transparent: true, opacity: 0.5 });
			const sphere = new THREE.Mesh( geometry, material );
			scene.add( sphere );
///////////////////////////////////

const geometry1 = new THREE.BoxGeometry(1, 1, 1);

  const loader = new THREE.TextureLoader();
  
  const material1 = new THREE.MeshBasicMaterial({
    map: loader.load('img/heartbit.jpg'),
  });
  const cube = new THREE.Mesh(geometry1, material1);
  scene.add(cube);
////////////////////////////////////
			camera.position.z = 3;
 
			function animate() {
        
				requestAnimationFrame( animate );
      
        sphere.scale.x = radius;
        sphere.scale.y = radius;
       
				renderer.render( scene, camera );
     
        bitTimer();
			};

			animate();
container.appendChild( renderer.domElement );
</script>
  </body>
</html>

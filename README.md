# CookieOsLoL.github.io
### I am an artist and student. This is my portfolio site.
This is a "README" file for my repository. It is written using **markdown**
<!DOCTYPE html>
<html>
	<head>
		<meta charset="utf-8">
		<style>
			body {
				background-color: #ffffff;
				margin: 0;
				overflow: hidden;
			}
		</style>
	</head>
	<body>
		
		<script src="http://threejsplaygnd.brangerbriz.net/js/three.min.js"></script>
		<script src="http://threejsplaygnd.brangerbriz.net/js/Detector.js"></script>
		<script>

			if ( ! Detector.webgl ) Detector.addGetWebGLMessage();
			
			var camera, scene, renderer;
			var geometry, material, mesh;

			function setup() {

				var W = window.innerWidth, H = window.innerHeight;
				renderer = new THREE.WebGLRenderer();
				renderer.setSize( W, H );
				document.body.appendChild( renderer.domElement );

				camera = new THREE.PerspectiveCamera( 50, W/H, 1, 10000 );
				camera.position.z = 500;

				scene = new THREE.Scene();
				
				
				// paste your code from the geometryGUI here


			}

			function draw() {

				requestAnimationFrame( draw );
				
				// experiment with code from the snippets menu here

				renderer.render( scene, camera );

			}

			setup();
			draw();

		</script>
		
	</body>

<!DOCTYPE html>
<html>
		<head>
				<link href="https://fonts.googleapis.com/css?family=Lobster" rel="stylesheet" type="text/css">
				<style>
						body {
		    					margin: 0;
		    					overflow-x: hidden;
						}

						canvas {
								display: block;
						} 

						.topnav {
		  						overflow: hidden;
		  						background-color: #001;
		  						margin: auto;
						}

						.topnav a {
		  						float: right;
		  						color: #f2f2f2;
		  						text-align: center;
		 						padding: 14px 16px;
		  						text-decoration: none;
		  						font-size: 17px;
						}

						.topnav a:hover {
		  						background-color: #fff;
		  						color: black;
		  						border-radius: 12px;
						}

						.topnav a.active {
		 					 	background-color: #2C528C;
		  						color: white;
						}

						.topnav a.active:hover {
		  						background-color: #51A0D5;
		  						color: white;
						}

						#submit {
								background-color: lightblue;
								border-radius: 12px;
						}

						#search {
								border-radius: 12px;
						}

						header h4 {
								color: red;
								float: center;
								text-align: center;
								margin: 0px;
						    	text-decoration: none;
								font-family: Lobster;
								text-shadow: 2px 2px 5px white;
								font-size: 40px;
						}

						p {
								color: black;
								font-family: sans-serif;
						}

						.center {
								position: relative;
						    	margin: auto;
						   		display: block;
								background-color: black;
						}

						#box-container {
						    	display: flex;
						    	background-color: black;
						}

						header #searchbar {
								float: left;
								text-align: center;
						  		padding: 14px 16px;
						    	text-decoration: none;
						}

						.title-color {
								color: blue;
								float: center;
								text-align: center;
								margin-top: 20px;
						    	text-decoration: none;
								font-family: sans-serif;
								text-shadow: 2px 2px 5px gray;
								font-size: 40px;
						}

						.list-color {
								color: black;
								float: center;
								margin-left: 30px;
						    	text-decoration: none;
								font-family: serif;
								font-size: 20px;
								background-color: #00FFFF;
						}

						.black-background {
								box-shadow: 0 10px 20px rgba(0,0,0,0.19), 0 6px 6px rgba(0,0,0,0.23);
						}

						.text-color {
								color: red;
								text-align: center;
								float: center;
								margin: center;
						    	text-decoration: none;
								font-family: Lobster;
								text-shadow: 9px 2px 5px black;
								font-size: 40px;
								background-color: white;
						}

						.Gaming {
								position: absolute;
								top: 21.5em;
								left: 6.2em;
								font-family: 'Montserrat';
								font-size: 7em;
								text-transform: uppercase;
								width: auto;
								line-height: .8em;
								border: 5px solid white;
								padding: .2em;
								color: white;
						}

						.News {
								position: absolute;
								top: 32.5em;
								left: 6.9em;
								font-family: 'Montserrat';
								font-size: 7em;
								text-transform: uppercase;
								width: auto;
								line-height: .8em;
								border: 5px solid white;
								padding: .2em;
								color: white;
						}

						.Sports {
								position: absolute;
								top: 43.5em;
								left: 6.4em;
								font-family: 'Montserrat';
								font-size: 7em;
								text-transform: uppercase;
								width: auto;
								line-height: .8em;
								border: 5px solid white;
								padding: .2em;
								color: white;
						}

						.Entertainment {
								position: absolute;
								top: 54em;
								left: 3.8em;
								font-family: 'Montserrat';
								font-size: 7em;
								text-transform: uppercase;
								width: auto;
								line-height: .8em;
								border: 5px solid white;
								padding: .2em;
								color: white;
						}

						.thumbnail {
						    	box-shadow: 0 10px 20px rgba(0,0,0,0.19), 0 6px 6px rgba(0,0,0,0.23);
						 }

						 #blueDiv {
								position: absolute;
								top: 150px;
								background-color: blue;
								width: 250px;
								height: 250px;
						}

						.lol {
								position: absolute;
								top: 500px;
								left: 10px;
						}
				</style>
				<meta charset="ISO-8859-1">
				<script type="text/javascript"></script>
                <title>WeMars</title>
                
                <script src="https://cdnjs.cloudflare.com/ajax/libs/three.js/102/three.js"></script>
		        <script src="https://cdnjs.cloudflare.com/ajax/libs/gsap/2.1.2/TweenMax.min.js"></script>
		</head>
<body>
		<h1 class="Science">Science</h1>
		<h1 class="Gaming">Gaming</h1>
		<h1 class="News">News</h1>
		<h1 class="Sports">Sports</h1>
		<h1 class="Entertainment">Entertainment</h1>
		<!-- <header>
				<div class="topnav">
						<a class="active" href="#home">Home</a>
		        		<a href="#TV"><strong>TV</strong></a>
		    			<a href="#Stories"><strong>Stories</strong></a>
		    			<a href="#Photos"><strong>Photos</strong></a>
		    			<a href="#Messages"><strong>Messages</strong></a>
		    			<form id="searchbar">
		      					<input type="search" id="search" name="search" placeholder="Search Residents. .">
		      					<input type="submit" id="submit" name="submit" value="Go!">
		    			</form>
		    			<h4><em>WeMars</em></h4>
				</div>
		</header>

		<div class="thumbnail" id="box-container"><img src="http://www.digitaljournal.com/img/5/0/8/3/9/3/i/5/8/4/o/Mars-Schiaparelli.jpg" alt="Mars Pic." height="500" width="500" class="center"></div>
		<p><a href="JavaScript:void(0)" onClick="greet();"><strong>Greet the residents!</strong></a></p>

		<div class="black-background">
		   		<p class="title-color">Goals of the App:</p>
		    	<div class="list-color">
		     		 <p>Making social media far more interesting!</p>
		      		 <p>Getting creative people to their ultimate potential!</p>
		      		 <p>Giving users the opportunity to live the best social media experience!</p>
		    	</div>
		</div> -->
		<!-- <script src="https://cdnjs.cloudflare.com/ajax/libs/three.js/86/three.min.js"></script>
		<script src="https://cdnjs.cloudflare.com/ajax/libs/jquery/2.2.2/jquery.min.js"></script> -->

		<script type="text/javascript">
		function science() {

						var scene = new THREE.Scene();

						var camera = new THREE.PerspectiveCamera(50,window.innerWidth/window.innerHeight,0.1,1000)
						camera.position.z = 4;

						var renderer = new THREE.WebGLRenderer({antialias: true});
						renderer.setClearColor("#42f598");
						renderer.setSize(window.innerWidth,window.innerHeight);

						document.body.appendChild(renderer.domElement);

						window.addEventListener('resize', () => {
								renderer.setSize(window.innerWidth,window.innerHeight);
						 		camera.aspect = window.innerWidth / window.innerHeight;

						 		camera.updateProjectionMatrix();
						})

						var geometry = new THREE.SphereGeometry(1, 50, 50);
						var material = new THREE.MeshLambertMaterial({color: 0xFFD700});
						var mesh = new THREE.Mesh(geometry, material);
						scene.add(mesh);

						var light = new THREE.PointLight(0xFFFFFF, 1, 500)
						light.position.set(10, 0, 25);
						scene.add(light);

						var render = function() {
						 		requestAnimationFrame(render);

						 		/* mesh.rotation.x += 0.01; */
						 		mesh.rotation.y += 0.01;
						 		renderer.render(scene, camera);
						}
						render();
                        
                        var style = document.createElement('style');
                        style.innerHTML = `
                        .Science {
								position: absolute;
                                float: center;
								text-align: center;
								font-family: 'Montserrat';
								font-size: 7em;
								text-transform: uppercase;
								width: auto;
								line-height: .8em;
								border: 5px solid white;
								padding: .2em;
								color: white;
						}
                        `;
                        document.head.appendChild(style);
		};
		science();
		</script>
		<script type="text/javascript">
		function Gaming() {
						var scene = new THREE.Scene();
						var camera = new THREE.PerspectiveCamera(50,window.innerWidth/window.innerHeight,0.1,1000)
						camera.position.z = 4;
						var renderer = new THREE.WebGLRenderer({antialias: true});
						renderer.setClearColor("#e7e7e7");
						renderer.setSize(window.innerWidth,window.innerHeight);
						document.body.appendChild(renderer.domElement);
						window.addEventListener('resize', () => {
								renderer.setSize(window.innerWidth,window.innerHeight);
						 		camera.aspect = window.innerWidth / window.innerHeight;
						 		camera.updateProjectionMatrix();
						})
						var geometry = new THREE.SphereGeometry(1, 50, 50);
						var material = new THREE.MeshLambertMaterial({color: 0xE83861});
						var mesh = new THREE.Mesh(geometry, material);
						scene.add(mesh);
						var light = new THREE.PointLight(0xFFFFFF, 1, 500)
						light.position.set(10, 0, 25);
						scene.add(light);
						var render = function() {
						 		requestAnimationFrame(render);
						 		/* mesh.rotation.x += 0.01; */
						 		mesh.rotation.y += 0.01;
						 		renderer.render(scene, camera);
						}
						render();
		};
		Gaming();
		</script>
		<script type="text/javascript">
		function New() {
						var scene = new THREE.Scene();
						var camera = new THREE.PerspectiveCamera(50,window.innerWidth/window.innerHeight,0.1,1000)
						camera.position.z = 4;
						var renderer = new THREE.WebGLRenderer({antialias: true});
						renderer.setClearColor("#ccccff");
						renderer.setSize(window.innerWidth,window.innerHeight);
						document.body.appendChild(renderer.domElement);
						window.addEventListener('resize', () => {
								renderer.setSize(window.innerWidth,window.innerHeight);
						 		camera.aspect = window.innerWidth / window.innerHeight;
						 		camera.updateProjectionMatrix();
						})
						var geometry = new THREE.SphereGeometry(1, 50, 50);
						var material = new THREE.MeshLambertMaterial({color: 0x1363FA });
						var mesh = new THREE.Mesh(geometry, material);
						scene.add(mesh);
						var light = new THREE.PointLight(0xFFFFFF, 1, 500)
						light.position.set(10, 0, 25);
						scene.add(light);
						var render = function() {
						 		requestAnimationFrame(render);
						 		/* mesh.rotation.x += 0.01; */
						 		mesh.rotation.y += 0.01;
						 		renderer.render(scene, camera);
						}
						render();
		};
		New();
		</script>
		<script type="text/javascript">
		function Sports() {
						var scene = new THREE.Scene();
						var camera = new THREE.PerspectiveCamera(50,window.innerWidth/window.innerHeight,0.1,1000)
						camera.position.z = 4;
						var renderer = new THREE.WebGLRenderer({antialias: true});
						renderer.setClearColor("#ff5252");
						renderer.setSize(window.innerWidth,window.innerHeight);
						document.body.appendChild(renderer.domElement);
						window.addEventListener('resize', () => {
								renderer.setSize(window.innerWidth,window.innerHeight);
						 		camera.aspect = window.innerWidth / window.innerHeight;
						 		camera.updateProjectionMatrix();
						})
						var geometry = new THREE.SphereGeometry(1, 50, 50);
						var material = new THREE.MeshLambertMaterial({color: 0xBDFF42 });
						var mesh = new THREE.Mesh(geometry, material);
						scene.add(mesh);
						var light = new THREE.PointLight(0xFFFFFF, 1, 500)
						light.position.set(10, 0, 25);
						scene.add(light);
						var render = function() {
						 		requestAnimationFrame(render);
						 		/* mesh.rotation.x += 0.01; */
						 		mesh.rotation.y += 0.01;
						 		renderer.render(scene, camera);
						}
						render();
		};
		Sports();
		</script>
		<script type="text/javascript">
		function Entertainment() {
						var scene = new THREE.Scene();
						var camera = new THREE.PerspectiveCamera(50,window.innerWidth/window.innerHeight,0.1,1000)
						camera.position.z = 4;
						var renderer = new THREE.WebGLRenderer({antialias: true});
						renderer.setClearColor("#85e5e5");
						renderer.setSize(window.innerWidth,window.innerHeight);
						document.body.appendChild(renderer.domElement);
						window.addEventListener('resize', () => {
								renderer.setSize(window.innerWidth,window.innerHeight);
						 		camera.aspect = window.innerWidth / window.innerHeight;
						 		camera.updateProjectionMatrix();
						})
						var geometry = new THREE.SphereGeometry(1, 20, 20);
						var material = new THREE.MeshLambertMaterial({color: 0xE831B1 });
						var mesh = new THREE.Mesh(geometry, material);
						scene.add(mesh);
						var light = new THREE.PointLight(0xFFFFFF, 1, 500)
						light.position.set(10, 0, 25);
						scene.add(light);
						var render = function() {
						 		requestAnimationFrame(render);
						 		/* mesh.rotation.x += 0.01; */
						 		mesh.rotation.y += 0.01;
						 		renderer.render(scene, camera);
						}
						render();
		};
		Entertainment();
		</script>
</body>
</html>

# Amazon Side Bar Menu #

*Description:* This menu models itself after the side bar menu found on Amazon.com to provide a flexible, content-rich fold out menu. It supports infinite number of sub menus. In addition, the menu is responsive in smaller screen and mobile devices, by stacking the sub levels when revealed on top of its parent to conserve space. A robust menu this is, and across multiple platforms!

## Directions ##

*Step 1:* This script uses the following external files:

+ jQuery 1.4 or above (served via Google CDN)
+ amazonmenu.js
+ amazonmenu.css

*Step 2:* Add the below code to the HEAD section of your page:

	<meta name="viewport" content="width=device-width">
	<link rel="stylesheet" type="text/css" href="amazonmenu.css">
	<script src="http://ajax.googleapis.com/ajax/libs/jquery/1.10.2/jquery.min.js"></script>
	
	<script src="amazonmenu.js">
	
	/* =====================================
	 ** Amazon Side Bar Menu- by JavaScript Kit (www.javascriptkit.com)
	 ** Visit JavaScript Kit at http://www.javascriptkit.com/ for full source code
	===================================== */
	
	</script>
	
	
	<script>
	
	jQuery(function(){
		amazonmenu.init({
			menuid: 'mysidebarmenu'
		})
	})
	
	</script>

*Step 3:* Then, add the below sample markup to your page:

	<nav id="mysidebarmenu" class="amazonmenu">
		<ul>
		<li><a href="#">Item 1</a></li>
		<li><a href="#">Folder 0</a>
			<div>
				<p>Browse our spring collection of useful webmaster tools and resources! Everything from JavaScript, CSS to PHP are covered!</p>
	
			  <ul>
			  <li><a href="#">Sub Item 0.1</a></li>
			  <li><a href="#">Sub Item 0.2</a></li>
			  <li><a href="#">Sub Item 0.3</a>
			  <li><a href="#">Sub Item 0.4</a>
					<div>
						<p><h3><a href="#">Image Optimizer</a></h3>
						Use this tool to easily optimize regular gifs, animated gifs, jpgs, and pngs, so they load as fast as possible. 
						</p>
	
						<p><h3><a href="#">FavIcon Generator</a></h3>
						Generate a favicon using any regular image with this tool. 
						</p>
	
						<p><h3><a href="#">Animated Gif Generator</a></h3>
						Animated Gif Generator lets you easily create an animated gif by uploading a series of still images! 
						</p>
	
						<p><h3><a href="#">Gradient Image Maker</a></h3>
						Gradient images are used everywhere in web page design, such as the background of form buttons, DIVs, to act as shadows etc. This tool lets you easily generate a gradient image. 
						</p>
	
					</div>
		
			  <li><a href="#">Sub Item 0.5</a></li>
			  </ul>
			</div>
		</li>
		<li><a href="#">Folder 1</a>
		  <ul>
		  <li><a href="#">Sub Item 1.1</a></li>
		  <li><a href="#">Sub Item 1.2</a></li>
		  <li><a href="#">Sub Item 1.3</a>
				<ul>
					<li>Sub Item 1.3.1</li>
					<li>Sub Item 1.3.2</li>
					<li>Sub Item 1.3.3</li>
				</ul>
			</li>
		  <li><a href="#">Sub Item 1.4</a></li>
		  <li><a href="#">Sub Item 1.2</a></li>
		  <li><a href="#">Sub Item 1.3</a></li>
		  <li><a href="#">Sub Item 1.4</a></li>
		  </ul>
		</li>
		<li><a href="#">Item 3</a></li>
		<li><a href="#">Folder 2</a>
		  <ul>
		  <li><a href="#">Sub Item 2.1</a></li>
		  <li><a href="#">Sub Item 2.1</a></li>
		  <li><a href="#">Sub Item 2.1</a></li>
		  <li><a href="#">Sub Item 2.1</a></li>
		  <li><a href="#">Sub Item 2.1</a></li>
		  <li><a href="#">Sub Item 2.1</a></li>
		  </ul>
		</li>
		<li><a href="#style/">Item 4</a></li>
		</ul>
	</nav>

## Amazon Side Bar Menu set up ##

See script project page for additional details on setup and documentation: <http://www.javascriptkit.com/script/script2/amazonsidebarmenu.shtml>

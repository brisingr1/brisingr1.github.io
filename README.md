# brisingr1.github.io

<!DOCTYPE html>

<html lang="en">

<head>
	<meta charset="utf-8">

	<title>Homepage</title>
	<link rel="stylesheet" href="styles.css"> 

	<!-- I tried to use these to reset the li, ul, and ol 
		 for the nested list to original settings-->
	<style>

		body
		{
			background-color: #0B0C10;
		}

		p
		{
			color: #45A29E;
		}

		.myLi
		{
			color:#45A29E;
			float:none;
		}
	</style>

</head>
<body>

<nav>
<div id="nav_bar">
	<ul>
  		<li><a href="index.html" class="active-page">Home</a></li>
  		<li><a href="globalproblems.html">Global Issues</a></li>
  		<li><a href="sustainabledevelopment.html">Sustainable Development</a></li>
  		<li><a href="religion.html">Religion</a></li>
	</ul>
</div>
</nav>
	<!-- Maybe use another nav bar for the other sections of the webpage (like religions, different topics of sustainable development, etc)-->

	<!-- Make list with nested list -->
	<!-- How to reset this to normal without getting rid of above nav bar
	This didn't work
	 style=" list-style-type: initial;
    			margin:initial;
    			padding:initial;
    			overflow:initial;
    			background-color:initial;
				position:initial;
    			top:initial;
    			width:initial;"-->

    <!-- 
    	Striking & simple
    	#0B0C10: Black
    	#1F2833: Grey
    	#C5C6C7: Off White
    	#66FCF1: Light blue
    	#45A29E: Turquoise-->

    <br>
	<br>
	<br>

	<h1>
		An Outline Of Important Things
	</h1>

	<ol>
		<li class="myLi">Global Issues
			<ol>
				<li class="myLi">Human Labor and Sex Trafficking</li>
				<li class="myLi">Famine</li>
				<li class="myLi">Preventable Disease</li>
			</ol>
		</li>
		<li class="myLi">Sustainable Development
			<ol>
				<li class="myLi">Food</li>
				<li class="myLi">Water</li>
				<li class="myLi">Public Health and First Aid</li>
			</ol>
		</li>
		<li class="myLi">Religion
			<ol>
				<li class="myLi">Chrisianity</li>
				<li class="myLi">Other Major Religions</li>
			</ol>
		</li>
	</ol>
	<!-- This website will be about issues that I want to be a part of helping to solve
		 Human Evil
		 	Human Trafficking - labor & sex
		 Sustainable Development
			Medicine
			Farming
			Water
		Education
			Teaching
		God


	-->
	<br>
	<br>
	<br>
<footer>
	<a class="footer" href = "mailto:htherrell@harding.edu">Email me at htherrell@harding.edu</a>
</footer>


</body>
</html>

<DOCTYPE! HTML>
<html>
<head>
	<title> China Bakery </title>
<style>
	*{
	margin:0;
	}
	body{
	background-image:url("bread2.jpg");
	background-attachment:fixed;
	background-size:cover;
	}
	#nav{
	width:100%;
	height:70px;
	background-color: #0e0101;
	color:#ff8100;
	padding-top:10px;
	background-attachment:fixed;
	}
	p{
	float:left;
	font-size:45px;
	padding-right:60px;
	padding-top:5px;
	}
	.dropbtn {
	background-color: #0e0101;
	color:#ff8100;
	padding: 8px 15px 8px 15px ;
	font-size: 35px;
	cursor: pointer;
	border-radius:5px;
	margin-right:15px;
	text-decoration:none;
	}

	.dropdown {
	position: relative;
	display:inline-block;
	padding-top:10px;
	}

	.dropdown-content {
	display: none;
	position: absolute;
	background-color:#f1f1f1;
	color:#0e0101;
	min-width: 160px;
	box-shadow: 0px 8px 16px 0px rgba(0,0,0,0.2);
	border-radius:10px;
	z-index:1;
	text-align:center;
	}

	.dropdown-content a {
	color: black;
	padding: 12px 16px;
	text-decoration: none; 
	display: block;
	border-bottom: 1px solid #cfb53b;
	font-size:14;
	font-family:arial;
	}

	.dropdown-content a:hover {
	background-color: #f1f1f1
	}

	.dropdown:hover .dropdown-content {
	display: block;
	}

	.dropdown:hover .dropbtn {
	background-color: #111;
	}
	.div1{
	width:auto;
	height:80%;
	background-image:url("bread2.jpg");
	background-size:cover;
	padding:7em 10em 5em 5em;
	}
	.font_size6em{
	font-size:8em;
	color:#ff8100;
	}
	.div2{
	width:auto;
	height:50em;
	background-color:#ff8100;
	}
	#chef{
	width:40%;
	height:70%;
	padding-top:12em;
	float:left;
	padding-right:8em;
	}
	.div3{
	float:right;
	padding:20px 30px 0px 20px;
	border:0px solid white;
	}
	.font_size10em{
	font-size:9em;
	color:white;
	}
	.a_button {
	    background-color:#ff8100;
	    border: 2px solid white;
	border-radius:6px;
	    color: white;
	    padding: 15px 32px;
	    text-align: center;
	    text-decoration: none;
	    display: inline-block;
	    font-size: 22px;
	}
	.a_button:hover{
	 background-color:white;
	color:#ff8100;
	}
	.div4{
	width:100%;
	height:30em;
	padding-top:8em;
	
	}
	.font_size8em{
	font-size:6em;
	color:gold;
	}
	.a_button2 {
	    background-color:brown;
	    border: 2px solid white;
	border-radius:6px;
	    color: white;
	    padding: 15px 32px;
	    text-align: center;
	    text-decoration: none;
	    display: inline-block;
	    font-size: 22px;
	}
	.a_button2:hover{
	 background-color:white;
	color:#ff8100;
	}
	.div5{
	width:100%;
	height:40em;
	padding-top:8em;
	background-image:url("bread4.jpg");
	background-size:cover;
	}
	.font_size3em{
	font-size:3em;
	color:white;
	}
	.font_size3em:hover{
	color:gold;
	}
	.div6{
	width:45%;
	border:0px solid brown;
	border-radius:6px;
	padding: 20px 15px 0px 30px;
	}
	.div7{
	width:auto;
	height:55em;
	padding:5em 8em 0em 8em;
	background-color:#B03A2E  ;
	}
	.font_size13em{
	font-size:8em;
	color:gold;
	}
	.font_size12em{
	font-size:8em;
	color:white;
	}
	.font_size5em{
	font-size:6em;
	color:white;
	}
	.font_size7em{
	font-size:4em;
	color:white;
	}
	.div8{
	width:auto;
	height:55em;
	background-color:white;
	padding:10em 12em 8em 12em;
	}
	.font_size14em{
	font-size:5em;
	color:grey;
	}
	.a_span{
	color:black; 
	font-size:35px;
	text-decoration:none;
	}
	.a_span:hover{
	color:seagreen;
	}
	.div9{
	width:auto;
	height:7em;
	padding:10em 8em 8em 8em;
	}
	.div10{
	width:auto;
	height:10em;
	padding:5em 8em 8em 8em;
	background-image:url("map.png");
	background-size:cover;
	}
</style>
</head>
<body>
	<center>
	<div id="nav">
	
	<div class="dropdown">
		  <a class="dropbtn" href="china bakers.html">Home</a>
	 </div>
	
	<div class="dropdown">
	<a class="dropbtn" href="products.html">Products   </a>
	<div class="dropdown-content">
	<a href="products.html">Bread</a>
	<a href="products.html">Pizza</a>
	<a href="products.html">Biscuits</a>
	<a href="products.html">Drinks</a>
	<a href="products.html">Cakes</a>
	<a href="products.html">Snacks</a>
	</div>
	</div>
	
	

	<div class="dropdown">
		  <a class="dropbtn" href="about.html">About</a>
	</div>


	<div class="dropdown">
		  <a class="dropbtn" href="contact.html">Contact</a>
	</div>

	<a href="login.html" style="float:right;font-size:27px;color:gold;text-decoration: none;">Login</a>	
	</div>
	</center>
	<div class="div1">
	<h1 class="font_size6em">China Bakery</h1>
	<span class="font_size5em">We exclusively use sun ripened whole grains</span>
	</div>
	<div class="div2">
	<div class="div3">
	<img id="chef" src="chef.jpg">
	<h1 class="font_size10em">We are the Best</h1>
	<span style="font-size:25px;" > We exclusively use sun ripened whole grains to provide you with a source of power, stamina and health! Spoil yourself with our breads natural flavor! We use only the finest quality ingredients providing your body with important fiber and nutrients. For people who suffer from allergies we offer a delicious range of wheat and yeast free products.</span>
	<br><br><br>
	<a class="a_button" href="about.html"> Read more</a>
	</div>
	</div>
	<div class="div4">
	<center>
	<h1 class="font_size8em">Order your <br>Custom cakes</h1>
	<br><br><br>
	<a class="a_button2" href="products.html">Order Now</a>
	</center>
	</div> 
	<div class="div5">
	<br><br><br><br><br><br><br><br><br>
	<div class="div6"  style="float:left;">
	<span class="font_size3em">CHINA’S BAKERY 
			IS DEDICATED TO PRODUCING
			HANDMADE BREADS USING
			TRADITIONAL BAKING
			TECHNIQUES
	</span>
	</div>
	<div class="div6" style="float:right;">
	<span class="font_size3em">
		DELICIOUS DIABETIC BAKERY - CAKES AND DESSERTS WITH NATURAL AND ALTERNATIVE SWEETENERS WITH NO CARBOHYDRATES
	</span>s
	</div>
	</div>
	<div class="div7">
	<center>
	<span class="font_size13em">FAST  </span>    <span class="font_size12em">   CATERING</span>
	<br><br><br>
	<span class="font_size7em">Our well known and loved products come to you, impeccably arranged and ready to 	serve.</span>	
	<br><br><br><br>
	<a class="a_button2" href="products.html">Order Now</a>
	<br><br><br><br>
	<img src="bread7.png" >
	</center>
	</div>
	<div class="div8">
	<center>
	<h1 class="font_size14em">POPULAR RECIPES</h1>
	</center>
	<table style="border:0px solid brown;padding:0px;">
	<tr>
	<td style="padding-right:150px;">
	<img src="cupcake1.jpg" width="400px" height="400px">
	<br><br>
	<span style="color:seagreen; font-size:50px;dispaly:inline-block;">1) </span>
	<a href="recipes" class="a_span" >Go To Vanilla & Chocolate Cupcakes</a>
	<br><br>
	<span style="font-size:22px;">Moist, perfect cupcakes everyone will love. Recipes with photos and reviews for vanilla cupcakes, 	cupcake frosting, mini cupcakes<br> and more.</span>
	</td>
	<td style="padding-top:150px;">
	<img src="cupcake2.jpg" width="400px" height="400px">
	<br><br>
	<span style="color:seagreen; font-size:50px;dispaly:inline-block;">1) </span>
	<a href="recipes" class="a_span" >Crispy and Creamy Doughnuts</a>
	<br><br>
	<span style="font-size:22px;">We have tried so many versions of glazed American-style doughnuts, and this one 		finally came out perfect!	</span>
	<br><br><br>
	<a class="a_button2" href="products.html">More Recipes</a>
	</td>
	</tr>
	</table>
	</div>
	<div class="div9">
	<center>
	<div style="float:right;padding-right:20em;">
	<a href="http://www.facebook.com"><img src="fb logo.jpg"  width="70px height="70px"></a>
	<a href="http://www.twitter.com"><img src="twitter logo.jpg"  width="70px height="70px"></a>
	<a href="http://www.gmail.com"><img src="google+.png"  width="70px height="70px"></a>
	</div>
	</center>
	
	<span style="color:white;font-size:25px;">&copy 2016    |    Privacy Policy <span>
	 </div>
	<div class="div10">
	<span style="font-size:70px;color:brown;"> You can find us on MAP.</span>
	</div>
</body>
</html>

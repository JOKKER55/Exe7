<!DOCTYPE html>
<html>
<head>
	<title>WISKYBAZE</title>
	<style>
		/* CSS styles for Navigation Menu */
		nav {
			background-color: #333;
			overflow: hidden;
		}
		nav a {
			float: left;
			display: block;
			color: white;
			text-align: center;
			padding: 14px 16px;
			text-decoration: none;
		}
		nav a:hover {
			background-color: #ddd;
			color: black;
		}
		/* CSS styles for Skills and Portfolio sections */
		.skill, .portfolio-item {
			display: inline-block;
			width: 30%;
			margin: 0 1.5%;
			vertical-align: top;
		}
		.skill h3, .portfolio-item h3 {
			text-align: center;
		}
		.skill p {
			text-align: justify;
		}
	</style>
</head>
<body>
	<!-- Navigation menu -->
	<nav>
		<a href="#about-us">About us</a>
		<a href="#skills">Skills</a>
		<a href="#portfolio">Portfolio</a>
		<a href="#contact">Contact</a>
	</nav>

	<!-- About us section -->
	<section id="about-us">
		<h2>About us</h2>
		<p>At WISKYBAZE Computers, we pride ourselves on providing the latest and greatest in computer technology to our customers. Our mission is to make high-quality computers accessible to everyone, whether you're an avid gamer or a busy professional.

      Since our inception, we have been committed to excellence in both our products and customer service. Our team of experienced computer experts are always here to answer your questions and provide you with top-notch support.
      
      Whether you're looking for a powerful gaming rig or a sleek laptop for your daily use, we have the perfect solution for you. Our extensive range of high-quality computers caters to both entry-level and advanced users alike.
      
      Thank you for choosing WISKYBAZE Computers as your go-to destination for all your computer needs. We look forward to serving you and helping you achieve your goals!</p>
	</section>

	<!-- Skills section -->
	<section id="skills">
		<h2>Skills</h2>
		<div class="skill">
			<h3>Skill 1</h3>
			<p>This is some sample text for Skill 1.</p>
		</div><br>
		<div class="skill">
			<h3>Skill 2</h3>
			<p>This is some sample text for Skill 2.</p>
		</div><br>
		<div class="skill">
			<h3>Skill 3</h3>
			<p>This is some sample text for Skill 3.</p>
		</div><br>
		<div class="skill">
			<h3>Skill 4</h3>
			<p>This is some sample text for Skill 4.</p>
		</div>
	</section>

	<!-- Portfolio section -->
	<section id="portfolio">
		<h2 style="text-align: center;">Portfolio</h2>
		<div class="portfolio-item">
			<h3>Project 1</h3>
			<img src="https://hp.com/digmedialib/prodimg/lowres/c06148089.png" width="300" height="200" alt="hp spectre x360">
		</div>
		<div class="portfolio-item">
			<h3>Project 2</h3>
			<img src="https://shutterstock.com/image-photo/modern-desktop-computer-wireless-keyboard-260nw-55573504.jpg" width="300" height="200" alt="Modern desktop computer">
		</div>
		<div class="portfolio-item">
			<h3>Project 3</h3>
			<img src="https://www.cnet.com/a/img/resize/2bf625a27ed1feeb6d22fb5f50baebcb324ddd79/hub/2021/06/03/bc8e688c-87ca-44e2-8002-e630b8c7b77f/apple-imac-m1-colors-2021-cnet-2021-045.jpg?auto=webp&fit=crop&height=675&width=1200" width="300" height="200" alt="Apple Imac">
		</div><br>
	</section>

	<!-- Contact section -->
	<section id="contact">
		<h2>Contact</h2>
		<h3>Name and Surname</h3>
		<address>
			Street Address<br>
			City, State ZIP<br>
			Country
		</address>
		<form method="post" action="send-message.php">
			<label for="name">Name:</label>
			<input type="text" id="name" name="name" required><br>
			<label for="subject">Subject:</label>
			<input type="text" id="subject" name="subject" required><br>
			<label for="message">Message:</label>
			<textarea id="message" name="message" required></textarea><br>
			<input type="submit" value="Send">
		</form>
	</section>
</body>
</html> 


# HTML-BASICS
This is a repo for HTML
<DOCTYPE! html>
<html lang="en">
	<head>
		<title>VR Experience</title>
	</head>
	
	<body>
		<div> <!-- start wrapper div-->
			<header>
				<nav>
					<h1 style="font-size:60px;">Experience VR<h1>
					<p>A <em>simple</em> blog about virtual reality</p>
					
					<ul>
						<li><a href="#">Home</a></li>
						<li><a href="#About">About</a></li>
						<li><a href="#Articles">Articles</a></li>
						<li><a href="#Contact">Contact</a></li>
					</ul>
				</nav>
			</header>
			
			<div>
				<figure>
					<img src="img/featured.jpg"alt="Virtual reality everywhere"></img>
				</figure>
				<p><strong>Virtual reality</strong> is becoming well known as a form of entertainment, but it's also finding it's way into fields like education, 
				industrial design, healthcare and so much more!</p>
				<a href="https://fincloud.getbucks.com/GetFin/Account/Login" target="_blank">Start your Journey here!</a>
			</div>
			
			<main>
				<section id= "About">
					<h2>About this Site</h2>
					<p><span>Lorem ipsum dolor</span> sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. 
							Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. 
							Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. 
							Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.</p>
					<figure>
						<img src="img/vr-space.jpg"alt="You can explore space with VR simulation"></img>
						<figcaption>
							VR simulation
						</figcaption>
					</figure>
				</section>
				
				<section id="Articles">
					
					<h2>Latest VR Articles</h2>
						<article>
							<header>
								<h3>How schools use Virtual Reality to improve education?</h3>
								<p>Published by: John Doe</p>
								<p>Published Date: June 22, 2020</p>
							</header>	
							<p style="color:red">Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. 
							Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. 
							Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. 
							Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.</p>
							<a href="articles/2020/article.html#vr-article">Read more</a>
							<footer>Published date: November 30, 2019</footer>
						</article>
						
						<article>
							<header>
								<h3>The Advantages of VR Simulation</h3>
								<p>By: Niel Thomas Chitewe</p>
							</header>
							<p>Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. 
							Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. 
							Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. 
							Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.</p>
							<a href="articles/2020/article.html#vr-article">Read more</a>
							<footer>Published date: December 30, 2019</footer>
						</article>
				</section>
				
				<section id="Contact">
					<h2>Contact</h2>
					<p>Email us at:<a href="mailto:coolvrexperience@gmail.com">coolvrexperience@gmail.com</a></p>
					<address>
						11 shashi Flats <br>
						Quendon Mabelreign <br>
						Zimbabwe
					</address>
				</section>
			
			</main>
			<hr>
			<aside>
				<h3>Top VR Resources</h3>
				<ol>
					<li><a href="#">Learn to create educational experience in VR</a></li>
					<li><a href="#">Virtual reality in entertainment</a></li>
					<li><a href="#">Interact with buildings and products in VR</a></li>
					<li><a href="#">Use VR for teleconferencing and social media</a></li>
				</ol>
				<blockquote cite=>
					<footer>
						Virtual reality was once a dream of science fiction.But the Internet was once a dream, 
						and so were computers and smart phones.The future is coming.
						-<cite><a href="https://www.facebook.com/zuck/posts/10101319050523971" target="_blank">Mark Zuckerberg</a></cite>
					</footer>
				</blockquote>
			</aside>
			
      <footer>
				<p><small>&copy;2020 VR experience</small></p>
			</footer>
		</div> <!--end wrapper div-->
	</body>
</html>

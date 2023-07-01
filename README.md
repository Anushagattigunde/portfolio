# portfolio


//home.html//


<!DOCTYPE html>
<html lang="en">
  <head>
	<meta charset="UTF-8">
	<meta name="viewport" content="width=device-width, initial-scale=1">
     <title>My Portfolio</title>




     <!--Linking to the font-->
     <link href="<link rel="preconnect href="https://fonts.googleapis.com">
     <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
     <link href="https://fonts.googleapis.com/css2?family=Montserrat:wght@700&family=Playfair+Display&display=swap" rel="stylesheet">

     <!-- Linking to CSS style -->
     <link rel="stylesheet" type="text/css" href="style.css">
     <style type="text/css">
     	.img-container{
     		text-align: center;
     	}
     </style>
     <!-- Internal css -->
 
  </head>
	<body>

		<!-- Inline css -->
		
			<header>
				<nav>
					<div class="container">
					<ul class="menu">
						<li><a href="Home">Home</a> </li>
						<li><a href="resume.html">Resume</a></li>
						<li><a href="contact.html">Contact</a> </li>
						<li><a href="skills.html">Skills</a></li>
						<li><a href="#Home"></a></li>
					</ul>
				</div>
				</nav>
			</header>
			<section class="Home">


				<!--Gif-->
				<div class="container">
					<p><h1 alignment = "center" >Anusha's Portfolio</h1>
						<img src="vid.gif" alt="Animated GIF" width="1100" height="345"></p></div>
				</section>
			
			
			
	        <footer>
	        	<br>
	        	<br>

	                	<p>copyright &copy; My Portfolio All rights reserved</p>
	                	<p>Made with &hearts; in India </p>
	        </footer>
	      </form>
    </body>
</html>

//resume.html//


<!DOCTYPE html>
<html lang="en">
  <head>
	<meta charset="UTF-8">
	<meta name="viewport" content="width=device-width, initial-scale=1">
     <title>Resume</title>
     <link rel="stylesheet" href="resumecss.css">
     <style>
     header{
      background-color: rgb(18, 3, 3);
      color:hsl(0, 40%, 98%);
      text-align: center;
      
    }
  </style>
       
     </head>

     <body>
        <section id="Home">
            <ul class = "container" >
            <div style="text-align: center;" >
              <div style="background-color: black; color: rgb(242, 242, 245);">
                <h1>Resume</h1>
              </div>
            </ul>
              </section>
              
              <div class="resume">
               
             
              <section class="Education">
                <h2>Education</h2>
                <ul>
                    <li>
                        <h3>B.tech in Computer Science and Engineering</h3>
                        <p>BVRIT HYDERABAD college of Engineering for Women</p>
                        <p>2121-2025</p>
                       <li> <h3>Intermediate</h3></li>
                        <p>Narayana Junior college Hyderabad</p>
                        <p>Grade:93%</p>
                        <p>2019-2021</p>
                        <li><h3> School</h3></li>
                        <p>Narayana Best Foundation School</p>
                        <p>Grade:93%</p>
                        <p>2018-2019</p>
                        </li>
                </ul>
              </section>
              <hr>
              <section class="echjegku">
                <h2>Projects</h2>
                <ul>
                  
                  <li><h3>Python project</h3>
                  <p>Hangman Game</p></li>
                  <li><h3>Web Development Project</h3>
                  <p>Roll The Dice</p></li>
                </ul>
              </section>
              <hr>
              <section class="Exp">
                <h2>Experience</h2>
                <ul>
                  <li>Women in software Engineering Since 2 years</li>
                </ul>
              </section>
              <hr>
              <section class="Skills">
                <h2>Skills</h2>
                <ul>
                    <li>Python</li>
                    <li>C++</li>
                    <li>C</li>
                    <li>Java Beginner</li>
                </ul>
              </section>
            </div>
            </body>
            </html>
	    
//contact.html//

<!DOCTYPE html>
<html lang="en">
  <head>
	<meta charset="UTF-8">
	<meta name="viewport" content="width=device-width, initial-scale=1">
     <title>Contact</title>
     <link rel="stylesheet" href="contact.css">
     <style>
        img{
            float: right;
            margin: 10px;
        }
        header{
	background-color: rgb(18, 3, 3);
	color:hsl(0, 40%, 98%);
	text-align: center;
	
}
   
      
        </style>
     </head>
     <body>
        <header>
       
            <div class = "container" >
                <p><h1 alignment = "center" >Contact</h1>
                
              </div>
            </div>
            
              </header>
              
       <!----> <section class="contact">
            <div class ="container"><ul>
            <font size=6px;
            <h2>Contact Information</h2></font>
            <p>
               <font size="5px">
                <li><strong>Phone:</strong>+91 8688382771</li>
                <li><strong>Email:</strong>21wh1a0523@bvrithyderabad.edu.in</li>
                <li><strong>Address:</strong>3/112,Madhira,Khammam (dist),Telangana 507203</li>
                <li><strong>LinkedIn:<a href="#LinkedIn">anushagattigunde</strong></a></li></p>
            </div>
					
        </font>			
                        <img src="mail.gif" alt="Animated GIF"  width="550" height="345"></div>
            </ul>
          </section>
     </body>



     //style.css//

     
     h1{
	font-family:sans-serif;
	text-align: center;
	font-size: 30px;
	background-color:white;
	color:rgb(0, 116, 249);
	padding: 0px;
}
hr{
	border:2px solid black;
	width:50%;
}
p{
	font-family: Monsterrat;
	margin-left:100px;
	margin-right: 100px;
}
u{
	text-align: center;
}
body {
	font-family: sans-serif;
	background-color: white;
}
.container {
	max-width: 960px;
	margin: auto;
	padding: 20px;
}
header{
	background-color: white;
	color:black;
	text-align: center;
	
}
header .container{
	display:flex;
	justify-content: space-between;
	text-align: center;
}

ul{
	list-style:none;
	background-color: black;
}
li{
	display: inline;
	justify-content: space-between;
	margin: 80px;
}

li a {
	color: white;
	text-decoration: none;
}
footer {
	/* background-color: black;
	color: white;
	padding: 5px; */
	text-align: center;
}

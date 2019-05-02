## About the team

Cameron van Roon (s3382032) is a 25-year-old novelist and international dodgeball coach from Geelong now studying computing studies at RMIT University. With minimal experience in IT, but motivated by passions for gaming, futurism and gadgetry, he joined the Discord Town of Salem group to work on a project in a field he loves and tackle new and unique programming challenges.

Sue Si Han (s3743694) is an 18 year old Malaysian that is currently studying Information Technology at RMIT. His hobbies are playing and listening to music and also gaming. Si Han’s interests in IT started when he was young and got to interact with computers. He decided to join Discord Town of Salem since it’s based on a program that many people like himself that game uses to chat with other gamers. 


Jayden Dang (s3781022) is a 18 year old Vietnamese that is a first year university student studying Information Technology at RMIT. He enjoys going to the gym and going out with friends. He joined the discord town of salem group to work on a project that is required as an assignment for his course. 

Nikolas Grubits (s3786116) is a 18 year old, with have two brothers one older and the other younger. They’ve been in Melbourne their entire life. Although he comes from Australia and was born here he’s father is Hungarian. He currently has a part time job working at our local pizza shop. He’s always enjoying tinkering with technology and uncovering every little bit of information he can.


### Our personalities 

According to the personality types Jayden is a Consul which means delegating him to team 
Nik’s type is a meditator which means in a teamwork environment he helps keep up moral and encourage people to reach their potential.  Using the personality test to determine each person's role in a team is not the most accurate way of assigning roles, it can help take some of the guesswork when assigning people to roles. 

Cameron’s Myers-Briggs personality profile is that on an Architect (INTJ-A), his learning style is Visual, and his Big 5 Personality Test results returned 29% extroversion, 94% emotional stability, 35% agreeableness, 80% conscientiousness, and 76% Intellect/Imagination. These test results would indicate that he has a strong creative drive and conviction, which means he will be good at taking the lead in putting forward ideas, which can help give direction to the team. He will need to ensure he doesn’t push too hard and doesn’t interfere when other members of the group want to influence its direction.

According to the Myers-Briggs personality profile Si Han’s personality type is Virtuoso (ISTP-T). His Big 5 Personality test results were 

<html>
<!-- Slideshow container -->
<div class="slideshow-container">

  <!-- Full-width images with number and caption text -->
  <div class="mySlides fade">
    <div class="numbertext">1 / 4</div>
    <img src="https://discordtownofsalem.github.io/main/images/architect.png" style="width:200">
    <div class="text">Caption Text</div>
  </div>

  <div class="mySlides fade">
    <div class="numbertext">2 / 4</div>
    <img src="https://discordtownofsalem.github.io/main/images/meditator.png" style="width:200">
    <div class="text">Caption Two</div>
  </div>

  <div class="mySlides fade">
    <div class="numbertext">3 / 4</div>
    <img src="https://discordtownofsalem.github.io/main/images/consul.png" style="width:200">
    <div class="text">Caption Three</div>
  </div>
  
  <div class="mySlides fade">
    <div class="numbertext">4 / 4</div>
    <img src="https://discordtownofsalem.github.io/main/images/consul.png" style="width:200">
    <div class="text">Caption Four</div>
  </div>

  <!-- Next and previous buttons -->
  <a class="prev" onclick="plusSlides(-1)">&#10094;</a>
  <a class="next" onclick="plusSlides(1)">&#10095;</a>
</div>
<br>

<!-- The dots/circles -->
<div style="text-align:center">
  <span class="dot" onclick="currentSlide(1)"></span> 
  <span class="dot" onclick="currentSlide(2)"></span> 
  <span class="dot" onclick="currentSlide(3)"></span> 
  <span class="dot" onclick="currentSlide(4)"></span> 
</div>

<style>
* {box-sizing:border-box}

/* Slideshow container */
.slideshow-container {
  max-width: 1000px;
  position: relative;
  margin: auto;
}

/* Hide the images by default */
.mySlides {
  display: none;
}

/* Next & previous buttons */
.prev, .next {
  cursor: pointer;
  position: absolute;
  top: 50%;
  width: auto;
  margin-top: -22px;
  padding: 16px;
  color: white;
  font-weight: bold;
  font-size: 18px;
  transition: 0.6s ease;
  border-radius: 0 3px 3px 0;
  user-select: none;
}

/* Position the "next button" to the right */
.next {
  right: 0;
  border-radius: 3px 0 0 3px;
}

/* On hover, add a black background color with a little bit see-through */
.prev:hover, .next:hover {
  background-color: rgba(0,0,0,0.8);
}

/* Caption text */
.text {
  color: #f2f2f2;
  font-size: 15px;
  padding: 8px 12px;
  position: absolute;
  bottom: 8px;
  width: 100%;
  text-align: center;
}

/* Number text (1/4 etc) */
.numbertext {
  color: #f2f2f2;
  font-size: 12px;
  padding: 8px 12px;
  position: absolute;
  top: 0;
}

/* The dots/bullets/indicators */
.dot {
  cursor: pointer;
  height: 15px;
  width: 15px;
  margin: 0 2px;
  background-color: #bbb;
  border-radius: 50%;
  display: inline-block;
  transition: background-color 0.6s ease;
}

.active, .dot:hover {
  background-color: #717171;
}

/* Fading animation */
.fade {
  -webkit-animation-name: fade;
  -webkit-animation-duration: 1.5s;
  animation-name: fade;
  animation-duration: 1.5s;
}

@-webkit-keyframes fade {
  from {opacity: .4} 
  to {opacity: 1}
}

@keyframes fade {
  from {opacity: .4} 
  to {opacity: 1}
}
</style>
<script>
var slideIndex = 1;
showSlides(slideIndex);

// Next/previous controls
function plusSlides(n) {
  showSlides(slideIndex += n);
}

// Thumbnail image controls
function currentSlide(n) {
  showSlides(slideIndex = n);
}

function showSlides(n) {
  var i;
  var slides = document.getElementsByClassName("mySlides");
  var dots = document.getElementsByClassName("dot");
  if (n > slides.length) {slideIndex = 1} 
  if (n < 1) {slideIndex = slides.length}
  for (i = 0; i < slides.length; i++) {
      slides[i].style.display = "none"; 
  }
  for (i = 0; i < dots.length; i++) {
      dots[i].className = dots[i].className.replace(" active", "");
  }
  slides[slideIndex-1].style.display = "block"; 
  dots[slideIndex-1].className += " active";
} 
</script>
</html>


### Ideal Jobs


Cameron’s ideal job is a Polyglot Software Engineer in a small team at a small company.

Si Han’s ideal job is a being a Software Engineer in a cybersecurity company that works with large scale projects from governments and commercial customers. 

Nik’s ideal job is becoming a software engineer at a large corporation, working in a team based environment would be ideal conditions. A job application he found online is at fintech which requires employees to be forward thinking and have the ability to problem solve and think outside of the box. Salary isn’t a main concern for him, rather having enough spare time and enjoying the job is what matters more.

Jayden’s idea job is to be a software engineer as a configuration specialist for a small or large company that create softwares that expected to run for a long period of time. 



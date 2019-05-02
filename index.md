<html>
<head>
<style>
ul {
  list-style-type: none;
  margin: 0;
  padding: 0;
  overflow: hidden;
  background-color: #333;
}

li {
  float: left;
}

li a {
  display: block;
  color: white;
  text-align: center;
  padding: 14px 16px;
  text-decoration: none;
}

li a:hover {
  background-color: #111;
}
</style>
</head>
<body>

<ul>
  <li><a href="index">Home</a></li>
  <li><a href="page-2">Industry Data</a></li>
  <li><a href="page-3">IT Work</a></li>
  <li><a href="page-4">IT Technologies</a></li>
  <li><a href="page-5">Project ideas</a></li>
</ul>

</body>
</html>


## About the team

Cameron van Roon (s3382032) is a 25-year-old novelist and international dodgeball coach from Geelong now studying computing studies at RMIT University. With minimal experience in IT, but motivated by passions for gaming, futurism and gadgetry, he joined the Discord Town of Salem group to work on a project in a field he loves and tackle new and unique programming challenges.

Sue Si Han (s3743694) is an 18 year old Malaysian that is currently studying Information Technology at RMIT. His hobbies are playing and listening to music and also gaming. Si Han’s interests in IT started when he was young and got to interact with computers. He decided to join Discord Town of Salem since it’s based on a program that many people like himself that game uses to chat with other gamers. 


Jayden Dang (s3781022) is a 18 year old Vietnamese that is a first year university student studying Information Technology at RMIT. He enjoys going to the gym and going out with friends. He joined the discord town of salem group to work on a project that is required as an assignment for his course. 

Nikolas Grubits (s3786116) is a 18 year old, with have two brothers one older and the other younger. They’ve been in Melbourne their entire life. Although he comes from Australia and was born here he’s father is Hungarian. He currently has a part time job working at our local pizza shop. He’s always enjoying tinkering with technology and uncovering every little bit of information he can.


### Our personalities 

According to the personality types Jayden is a Consul which means delegating him to team 
Nik’s type is a meditator which means in a teamwork environment he helps keep up moral and encourage people to reach their potential.  Using the personality test to determine each person's role in a team is not the most accurate way of assigning roles, it can help take some of the guesswork when assigning people to roles. 

Cameron’s Myers-Briggs personality profile is that on an Architect (INTJ-A), his learning style is Visual, and his Big 5 Personality Test results returned 29% extroversion, 94% emotional stability, 35% agreeableness, 80% conscientiousness, and 76% Intellect/Imagination. These test results would indicate that he has a strong creative drive and conviction, which means he will be good at taking the lead in putting forward ideas, which can help give direction to the team. He will need to ensure he doesn’t push too hard and doesn’t interfere when other members of the group want to influence its direction. [CvR]

According to the Myers-Briggs personality profile Si Han’s personality type is Virtuoso (ISTP-T). His Big 5 Personality test results were 

<html>
<style>
#boat {
  margin-left: 0;
  cursor: pointer;
  transition: margin-left 3s ease-in-out;
}

/* flipping the picture with CSS */
.back {
  transform: scaleX(-1);
  filter: fliph;
}
</style>
<head>
  <meta charset="utf-8">
  <link rel="stylesheet" href="style.css">
</head>

<body>

  <img src="https://js.cx/clipart/boat.png" id="boat">

  <script>
    boat.onclick = function() {

      this.onclick = null; // only the first click should start the animation

      let times = 1;

      function go() {
        if (times % 2) {
          boat.classList.remove('back');
          boat.style.marginLeft = 100 + 200 + 'px';
        } else {
          boat.classList.add('back');
          boat.style.marginLeft = 100 - 200 + 'px';
        }

      }

      go();

      boat.addEventListener('transitionend', function() {
        times++;
        go();
      });
    }
  </script>


</body>

</html>


### Jekyll Themes

Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/discordtownofsalem/main/settings). The name of this theme is saved in the Jekyll `_config.yml` configuration file.

### Support or Contact

Having trouble with Pages? Check out our [documentation](https://help.github.com/categories/github-pages-basics/) or [contact support](https://github.com/contact) and we’ll help you sort it out.

<a href="https://discordtownofsalem.github.io/main/page-2">Page 2</a>

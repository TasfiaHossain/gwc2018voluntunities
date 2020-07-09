<!DOCTYPE html>
<html>
<head>
<title>Voluntunities</title>
<meta name="viewport" content="width=device-width, initial-scale=1">
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css">

<div>
  <link rel="icon"
  type="image/jpg"
  href="https://as2.ftcdn.net/jpg/00/86/87/65/500_F_86876581_D0v20hUhcmuripOCCY8JpwuKPu4srIWu.jpg"
</div>

<style>
* {box-sizing: border-box}

/* Set height of body and the document to 100% */
body, html {
    width: 100%;
    margin: 0;
    font-family: Arial;
}

/* Style tab links */
.tablink {
    background-color: #555;
    color: white;
    float: left;
    border: none;
    outline: none;
    cursor: pointer;
    padding: 14px 15px;
    font-size: 17px;
    width: 25%;
}

.tablink:hover {
    background-color: #777;
}

/* Style the tab content (and add height:100% for full page content) */
.tabcontent {
    color: white;
    display: none;
    padding: 100px 20px;
    height: 100%;
}

button {
    background-color: black;
    border: none;
    color: white;
    padding: 15px 32px;
    text-align: center;
    text-decoration: none;
    display: inline-block;
    font-size: 16px;
}

#Home {background-color: powderblue;}
#Opportunities {background-color: plum;}
#About {background-color: lightpink; width: 100%;}
#Contact {background-color: gainsboro;}

{
    box-sizing: border-box;
}

.row {
    display: flex;
}

/* Create three equal columns that sits next to each other */
.column {
    flex: 33.33%;
    padding: 5px;
}

.button {
    background-color: #4CAF50;
    border: none;
    color: white;
    padding: 16px 32px;
    text-align: center;
    text-decoration: none;
    display: inline-block;
    font-size: 16px;
    margin: 4px 2px;
    -webkit-transition-duration: 0.4s; /* Safari */
    transition-duration: 0.4s;
    cursor: pointer;
}

.button1 {
    background-color: black;
    color: white;

}

.button1:hover {
    border: 3px solid #ff0000;
    color: white;
}

.button2 {
    background-color: black;
    color: white;

}

.button2:hover {
    border: 3px solid #ff6600;
    color: white;
}

.button3 {
    background-color: black;
    color: white;

}

.button3:hover {
    border: 3px solid #ffff00;
    color: white;
}

.button4 {
    background-color: black;
    color: white;

}

.button4:hover {
    border: 3px solid #00ffff;
    color: white;
}

.button5 {
    background-color: black;
    color: white;

}

.button5:hover {
    border: 3px solid #cc00ff;
    color: white;
}

.fa {
  padding: 5px;
  font-size: 15px;
  width: 25px;
  text-align: center;
  text-decoration: none;
  margin: 5px 2px;
  border-radius: 50%;
}

.fa:hover {
    opacity: 0.7;
}

.fa-linkedin {
  background: #007bb5;
  color: white;
}

.buttonn {
  display: inline-block;
  padding: 10px 10px;
  font-size: 16px;
  cursor: pointer;
  text-align: center;
  text-decoration: none;
  outline: none;
  color: #000000;
  background-color: #F2FAFB;
  border: none;
  border-radius: 15px;
  box-shadow: 0 9px #999;
}

.buttonn:hover {background-color: #77F0F8}

.buttonn:active {
  background-color: #09CBD8;
  box-shadow: 0 5px #666;
  transform: translateY(4px);
}


</style>
</head>


<body>

<button class="tablink" onclick="openPage('Home', this, 'powderblue')" id="defaultOpen">Home</button>
<button class="tablink" onclick="openPage('Opportunities', this, 'plum')">Opportunities</button>
<button class="tablink" onclick="openPage('About', this, 'lightpink')">About</button>
<button class="tablink" onclick="openPage('Contact', this, 'gainsboro')">Contact</button>


<div id="Home" class="tabcontent">
  <p align="center"><font face="century gothic" size="9">Welcome to Voluntunities!</font></p>
  <p style="text-align:center;"><img src="pic1.jpg" alt="Homepgpic"></p>
  <p align="center"><font color="powderblue">...</p>
  <div>
  <p style="text-align:center;"><button class="buttonn"><img class="scroll">Featured Photos</button></p>
  <p align="center"><font color="powderblue">...</p>
  <div class="row">
    <div class="column">
      <img src="pic4.jpg" alt="Snow" style="width:100%">
    </div>
    <div class="column">
      <img src="pic3.png" alt="Forest" style="width:100%">
    </div>
    <div class="column">
      <img src="pic5.jpg" alt="Mountains" style="width:93%">
    </div>
  </div>

  <div class="row">
  <div class="column">
    <img src="pic9.jpg" alt="Snow" style="width:97%">
  </div>
  <div class="column">
    <img src="pic7.jpg" alt="Forest" style="width:100%">
  </div>
  <div class="column">
    <img src="pic8.jpg" alt="Mountains" style="width:100%">
  </div>
</div>

</div>
</div>

<div id="Opportunities" class="tabcontent">
<center>
<button class="button button1" button onclick="myHealth()">Health</button>
<button class="button button2" button onclick="myChildren()">Children</button>
<button class="button button3" button onclick="myAnimals()">Animals</button>
<button class="button button4" button onclick="myEnvironment()">Environment</button>
<button class="button button5" button onclick="myPantry()">Pantry</button>
</center>

<p align="center">...</p>
<h3 align="center">Directions</h3>
<p align="center">Here you will be able to search the volunteer opportunities under the topic of your choice.</p>
<p align="center">Choose from the categories above to find the potential areas you can volunteer in.</p>
<p align="center">Click one of the categories to be taken to the map of your area.</p>
<center>
<img src=map5.jpg>
</center>

</div>


<div id="About" class="tabcontent">
  <p align="center"><font face="century gothic" size="9">About Us & Our Project</font></p>

  <div class="row">
    <div class="column">
      <img src="flowers.gif" alt="Snow" style="width:100%">
    </div>
    <div class="column">
      <img src="happycoding.gif" alt="Forest" style="width:100%">
    </div>
    <div class="column">
      <img src="flowers.gif" alt="Mountains" style="width:100%">
    </div>
  </div>

  <p align="center">Michelle Saidov, Tasfia Hossain and Helina Rathod are creators of the website "Voluntunities". By learning the basics of coding in the program Girls Who Code, we were able to develop a website that allows the user to find opportunities to volunteer in around their area.</h5>
  <p align="center" color="white">...</p>
  <div id = "About">
  <h4 align="center"><font color="black">What inspired your group to do this project?</h4>
  <p align="center"><font color="white">When we were thinking of different project ideas, a common problem we had been trying to fulfill our required community service hours for school. However, we couldn't find events to take part in around our area. As a result, we created this website that will not only list the events people can volunteer in, but also around the area you live for your convenience. This is also a good way to give back to our community.</p>
  <h4 align="center"><font color="black">What programming languages were used to create your website?</h4>
  <p align="center"><font color="white">HTML, CSS, Java Script, API's ,and Data Sets.</p>
  <h4 align="center"><font color="black">Which Woman in Spotlight inspired your group?</h4>
  <p align="center"><font color="white">Ada Lovelace inspired us to make this project because she initially introduced the algorithim to computer programming to the world. By developing this, she gave women -centuries later- a chance to use this code to create various programs that can help the world. Using her initiative, we were able to create this website that would allow us to help people find other people to help. </p>
  </div>
</div>


<div id="Contact" class="tabcontent">
  <p align="center"><font face="century gothic" size="9">Contact Us</font></p>
  <p align="center">If you have any questions, concerns, or recommendations, feel free to contact us.</p>

  <div class="row">
    <div class="column">
      <img src="flowers2.gif" alt="Snow" style="width:100%">
    </div>
    <div class="column">
      <img src="phone2.gif" alt="Forest" style="width:80%">
    </div>
    <div class="column">
      <img src="flowers2.gif" alt="Mountains" style="width:100%">
    </div>
  </div>

  <div id = "Contact">
  <p align="center">Michelle Saidov: michelle.saidov@yuhsg.org</p>
    <center>
    <a href="#" class="fa fa-linkedin" onclick="window.location.href='https://www.linkedin.com/in/michelle-saidov-157a91146/'"></a>
  </center>
  <p align="center">Tasfia Hossain: tasfiahossain971@gmail.com</p>
  <center>
  <a href="#" class="fa fa-linkedin" onclick="window.location.href='https://www.linkedin.com/in/tasfia-hossain-0a4670168/'"></a>
</center>
  <p align="center">Helina Rathod: rathodh@bxscience.edu</p>
  <center>
  <a href="#" class="fa fa-linkedin" onclick="window.location.href='https://www.linkedin.com/in/helina-rathod-069670168/'"></a>
</center>

</div>

<script>
function openPage(pageName,elmnt,color) {
    var i, tabcontent, tablinks;
    tabcontent = document.getElementsByClassName("tabcontent");
    for (i = 0; i < tabcontent.length; i++) {
        tabcontent[i].style.display = "none";
    }
    tablinks = document.getElementsByClassName("tablink");
    for (i = 0; i < tablinks.length; i++) {
        tablinks[i].style.backgroundColor = "";
    }
    document.getElementById(pageName).style.display = "block";
    elmnt.style.backgroundColor = color;

}
// Get the element with id="defaultOpen" and click on it
document.getElementById("defaultOpen").click();

function myHealth() {
  window.open("https://www.google.com/maps/search/hospitals+to+volunteer+at+near+me/@40.7610601,-73.9230684,13z");
}

function myChildren() {
  window.open("https://www.google.com/maps/search/children+volunteering+near+me/@40.7330398,-73.9138646,13z");
}

function myAnimals() {
  window.open("https://www.google.com/maps/search/animal+shelter+volunteering+near+me/@40.733514,-74.0189316,11z");
}

function myEnvironment() {
  window.open("https://www.google.com/maps/place/GrowNYC/@40.7399425,-73.9184338,13z/data=!4m8!1m2!2m1!1senvironment+volunteering+near+me!3m4!1s0x89c25a221d8ae6b5:0xa45330a9300c9142!8m2!3d40.7101511!4d-74.0032345");
}

function myPantry() {
  window.open("https://www.google.com/maps/search/hospitals+to+volunteer+at+near+me/@40.7610601,-73.9230684,13z");
}


</script>


</body>
</html>

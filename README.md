# Ex.06 Book Front Cover Page Design
## Date:

## AIM:
To design a book front cover page using HTML and CSS.

## DESIGN STEPS:

### Step 1:
Create a Django Admin project.

### Step 2:
Create an app in the Django interface.

### Step 3:
Create a folder named 'static' in the app folder.

### Step 4:
Create a new HTML file in the static folder.

### Step 5:
Write the HTML code with relevant CSS properties.

### Step 6:
Choose the appropriate style and color scheme.

### Step 7:
Insert the images in their appropriate places.

### Step 8:
Publish the website in the LocalHost.

## PROGRAM:
<title>BOOK COVER</title> {
    <style> .bookpage{width: 400px;
height: 600px;
color:black;
margin-left: auto;
margin-right: auto;
padding: 20px;
font-family: ' Arial, sans-serif';
background-image: url(bcc.jpeg);
background-size: cover;
}


.insight{
color:azure;

}


.hrstyle{
width:100px;
}
.author{

display: inline;
position: relative;
color:rgb(255, 255, 255);
top:190px;

font-family:Georgia;
font-size: medium;
}
.booktitle{
color:blue;
font-family: Roquen;
font-size: larger;
text-align: center;
position: relative;
top: 30px;

}
.id {
width:400px;
position: relative;
top:180px;

}
.pub{
color:blue;
font-size: medium;
position: relative;
top:155px;
left:330px;
}
.ed{
color:blue;
font-size: medium;
font-family: Verdana;
position:relative;
top:85px;

}
.subtitle{
color:blue;
font-family:unicorn;
font-size: large;
position: relative;
top:40px;
text-align: center;
}
.myphoto {
position: relative;
margin-top: 20px; /* Adjust the margin-top to position the image below the subtitle */
margin-left: auto;
margin-right: auto;
left: 140px;
top: 185px;
width: 90px;
height: 90px;
border-radius: 50%;
overflow: hidden;
}

.myphoto img {
width: 100%;
height: 120%;
object-fit: cover;
}
</style>
<title>Book Cover Page</title>
</head>
<body>
<div class="bookpage">
<div class="insight">
    HACKER EDITION
</div>
<div class="hrstyle">
    <hr style="color:blanchedalmond">
</div>
<div class="booktitle">
    <h1>"ETHICAL HACKING:INTRO"</h1></div>
<div class="subtitle">
    "Discover what ethical hacking is, how it works, and why it's becoming increasingly important in today's digital age"
</div>
<div class="subtitle">
     
</div>

<br>
<br>
<br>
<br>

<div class="myphoto">
    <img src="my photo.jpg" width="120" height="120" >

</div>
<div class="id">
    <hr style="color:rgb(68, 24, 187)">
</div>
<div class="author">
   <p><b>FIRST EDITION </b></p>
</div>
<div class="pub">
    SEC
</div>
<div class="ed">
    <b>SABARINATH.R(212223100048)</b>
</div>
</div>
</body>

## OUTPUT:
![Screenshot 2024-04-27 223412](https://github.com/Sabari-2005/cover/assets/139338709/e89bd7f8-085f-499a-8f30-f8099418dc40)



## RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.

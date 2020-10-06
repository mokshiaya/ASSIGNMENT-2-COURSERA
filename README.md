# ASSIGNMENT-2-COURSERA
<html>
<head>
<meta charset="utf-8">
<title></title>
<meta charset="utf-8">
<meta name="viewport"
contetnt="width=device-width,initial-scale=1">
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css">
 <style>
body {
  font-family: Arial, Helvetica, sans-serif;
}

.mobile-container {
  width: 1024px;
  margin: 20px;
  background-color: #555;
  height: 521px;
  color: white;
  border-radius: 10px;
}

.topnav {
  overflow: hidden;
  background-color: #333;
  position: relative;
  align: center;
}

.topnav #myLinks {
  display: none;
}

.topnav a {
  color: white;
  padding: 14px 16px;
  text-decoration: none;
  font-size: 17px;
  display: block;
}

.topnav a.icon {
  background: black;
  display: block;
  position: absolute;
  right: 0;
  top: 0;
}

.topnav a:hover {
  background-color: #ddd;
  color: black;
}

.active {
  background-color: #4CAF50;
  color: white;
}
.row{
  margin-top: 6%;
  margin-bottom: 6%;
}
h1 {
  margin-bottom: 17px;
  text-align: center;
  color: blue;
  font-size: 50px;
  font-family: ariel;
}
box {
  width: 100%;
  overflow: none;
}
.content-name{
  overflow:none;
  text-align: center;
  border: 5px solid black;
  width: 100px;
  height: 40px;
  padding: 2px;
  float:right;
  margin-top:4px;
  margin-right:15px;
  font-weight: bold;
  position: relative;
}
.content 
{
  border:3px solid black;
  width: 300x;
  hieght: 200px;
  margin: 2.5%;
  color:black;
  font-size: 25px;
  padding: 20px 20px 20px 20px;
  padding-top: 55px;
  background-color:silver;
}
.name1{
background-color:maroon;  
}
.name2{
background-color:aqua;  
}

.name3{
background-color:teal;  
}
@media (min-width: 992px) {
.col-lg-4{
  float:left;
  width:33.33%;
}
}
@media(min-width:768px)and(max-width:991)
{
  .col-md-6,col-md-12;{
  float:left;
}
.col-md-6{
  width:50%;}
.col-md-12{
  margin-left:-10px;
  width:50%;
.name3{
  margin-right:65px;
  width:100px;
}
}
</style>
</head>
<body>

<!-- Simulate a smartphone / tablet -->
<div class="mobile-container">

<!-- Top Navigation Menu -->
<div class="topnav">
  <a href="#home" class="active">Food LLC</a>
  <div id="myLinks">
    <a href="#news">Chicken</a>
    <a href="#contact">Beef</a>
    <a href="#about">Sushi</a>
  </div>
  <a href="javascript:void(0);" class="icon" onclick="myFunction()">
    <i class="fa fa-bars"></i>
  </a>
  <div class="row">
<div>
 <div class="col-lg-4 col-md-6 col-sm-12">
    <div class="box">
      <p class="content-name name1">
        Dummy
      </p>
      <p class="content">
        This is a dummy text, no need to read this please do skip it , its no point in reading this.
      </p>
  </div>
  </div>
  <div class="col-lg-4 col-md-6 col-sm-12">
    <div class="box">
      <p class="content-name name2">
        Dummy
      </p>
      <p class="content">
        This is a dummy text too, no need to read this please do skip it , its no point in reading this.
      </p>
    </div>
  </div>
  <div  class="col-lg-4 col-md-6 col-sm-12">
    <div class="box">
      <p class="content-name name3">
        Dummy
      </p>
      <p class="content">
       This is a dummy text again, no need to read this please do skip it , its no point in reading this. 
      </p>
    </div>
  </div> <!-- Simulate a smartphone / tablet -->
    </div>
<script>
function myFunction() {
  var x = document.getElementById("myLinks");
  if (x.style.display === "block") {
    x.style.display = "none";
  } else {
    x.style.display = "block";
  }
}
</script>

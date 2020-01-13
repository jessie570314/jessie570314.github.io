body {
  padding-left: 11em;
  font-family: Georgia, "Times New Roman",Times, serif;
  color: purple;
  background-color: #d8da3d }
ul.navbar {
  list-style-type: none;
  padding: 0;
  margin: 0;
  position: absolute;
  top: 2em;
  left: 1em;
  width: 9em }
h1 {
  font-family: Helvetica, Geneva, Arial,
        SunSans-Regular, sans-serif }
ul.navbar li {
  background: white;
  margin: 0.5em 0;
  padding: 0.3em;
  border-right: 1em solid black }
ul.navbar a {
  text-decoration: none }
a:link {
  color: blue }
a:visited {
  color: purple }
address {
  margin-top: 1em;
  padding-top: 1em;
  border-top: thin dotted }
  <!DOCTYPE html PUBLIC "-//W3C//DTD HTML 4.01//EN">
<html>
<head>
  <title>Mypage</title>
  <style type="text/css">
  body{
    padding-left: 14em;
    font-family: Georgia, "Times New Roman",
          Times, serif;
    color: #565656;
    background-color: #D7CEC7 }
  h1{
    color: #76323F
    }
  span {
    color: #C09F80
    }
  ul.navbar {
    list-style-type: none;
    padding: 0;
    margin: 0;
    position: absolute;
    top: 2em;
    left: 1em;
    width: 9em }
  h1 {
    font-family: Helvetica, Geneva, Arial,
          SunSans-Regular, sans-serif }
  ul.navbar li {
    background: white;
    margin: 0.5em 0;
    padding: 0.3em;
    border-right: 1em solid #C09F80 }
  ul.navbar a {
    text-decoration: none }
  a:link {
    color: #76323F }
  a:visited {
    color: purple }
  address {
    margin-top: 1em;
    padding-top: 1em;
    border-top: thin dotted }
  </style>
</head>

<body>

<script language="JavaScript">
<!--
var now,hours,minutes,seconds,timeValue;
function showtime(){
now = new Date();
hours = now.getHours();
minutes = now.getMinutes();
seconds = now.getSeconds();
timeValue = (hours >= 12) ? "afternoon " : "morning ";
timeValue += ((hours > 12) ? hours - 12 : hours) + " :";
timeValue += ((minutes < 10) ? " 0" : " ") + minutes + " :";
timeValue += ((seconds < 10) ? " 0" : " ") + seconds + "";
clock.innerHTML = timeValue;
setTimeout("showtime()",1000);
}
showtime();
//-->
</script>

<body onload="showtime();" >

<span id='clock'></span>

<!-- 目錄 -->
<ul class="navbar">
  <li><a href="myproject.html">myprofile</a>
  <li><a href="myinterest.html">interest</a>
  <li><a href="myexperience.html">Ariticles</a>
</ul>

<!-- 主要內容 -->

<h1>Mypage</h1>

<p>Welcome to my page

<p>Three years ago, I packed my suitcase and got on the plane that flies to the U.S.A. I stayed in Washington state for a year as an exchange student, and that year has changed my life. Not only because I became confident and independent, but also because I found the career that I want to pursue in my life.


<P>Besides America, I also studied in China for six years when I was in elementary school. As a result of travelling a lot, I learned to interact with people from different background and culture. This valuable studying experience gave me a better view of the world and the chance to learn something from a different culture. 

<p>

<p>
<!-- 簽名和日期 -->

<address>2019/12</address>

</body>
</html>

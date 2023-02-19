# hour1
<!DOCTYPE html>
<html>
<head>
<meta charset="utf-8" />
<meta name="description" content="no thing" />
<link rel="stylesheet"href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.2.1/css/all.min.css">
<title>Mahmoud Ahmed</title>
<style>
:root{
--main-color:rgb(96,207,226);
}
*{
margin:0;padding:0;
}
.header {
width:100%;
min-width:0;
max-width:100%;
align-items:center;
background:rgb(38,194,252);
position:fixed;
display:flex;
height:130px;
min-height:0;
max-height:150px;
justify-content:space-between;
z-index:700;
}
#h1{
padding-right:10px;
padding-left:30px;
padding-top:10px;
font-size:70px;
text-transform:uppercase;
}
ul li{
position:relative;
padding-right:140px;
display:inline;
font-weight:500;
font-size:31.8px;
margin-right:10px;
}
ul li a{
text-decoration:none;
position:absolute;
color:purple;
transition:.55s;
}
ul li :hover {
background:blue;
color:white;
padding-left:10px;
border-radius:15px;
transform:scale(1.1);
}
li a:hover {
padding-right:10px;
transform:scale(1.1);
cursor:pointer;
}
.body2 {
background-image:url("num.jpg");
padding-top:1000px;
background-repeat:no-repeat;
background-size:auto;
background-position:0 200px;
position:relative;
}
.body2 h1{
padding-left:500px;
bottom:500px;
position:absolute;
margin:20px;
font-size:60px;
color:var(--main-color);
}
.body2 p{
position:absolute;
padding-left:500px;
bottom:310px;
font-size:45px;
}

.card1 {
background-color:var(--main-color);
border-radius:25px;
align-items:center;
position:relative;
display:block;
margin-bottom:20px;
height:570px;
}
.card1 img {
padding-top:120px;
width:97%;
height:440px;
padding-right:10px;
padding-left:100px;
border-radius:10px;
}
.card1 h3{
position:absolute;
top:5px;
font-size:50px;
left:360px;
}
.card1 p{
position:absolute;
top:67px;
font-size:37px;
left:350px;
}
.card2 {
background-color:var(--main-color);
border-radius:25px;
align-items:center;
position:relative;
display:block;
margin-bottom:20px;
height:570px;
}
.card2 img {
padding-top:120px;
padding-right:23px;
height:450px;
width:95%;
border-radius:30px;
}
.card2 h3{
position:absolute;
top:15px;
left:320px;
font-size:30px;
font-weight:800;
}
.card2 p{
position:absolute;
top:60px;
font-size:20px;
font-weight:650;
}
.card3 {
background-color:var(--main-color);
border-radius:25px;
align-items:center;
position:relative;
display:block;
margin-bottom:20px;
height:570px;
}
.card3 img {
padding-top:120px;
padding-right:23px;
height:450px;
width:95%;
border-radius:30px;
}
.card3 h3{
position:absolute;
top:15px;
left:380px;
font-size:40px;
font-weight:800;
}
.card3 p{
position:absolute;
top:60px;
font-size:20px;
font-weight:650;
left:350px;
}
.services {
position:relative;
}
#services11 {
text-align:center;
font-size:50px;
}
#services11 span {
color:var(--main-color);
}
#card-1 {
background-color:var(--main-color);
width:400px;
height:500px;
margin-top:50px;
margin-left:550px;
border-radius:20px;
transition:10.999999s;
}

#card-1 p{
font-size:50px;
}
#card-1 h3{
padding-top:10px;
text-align:center;
font-size:35px;
}
.card-2 {
position:absolute;
background-color:var(--main-color);
width:400px;
height:500px;
margin-top:50px;
margin-left:50px;
bottom:0;
border-radius:20px;
}
.card-2 h3{
padding-top:10px;
text-align:center;
font-size:35px;
}
.card-2 p{
font-size:50px;
}
.card-3 {
position:absolute;
background-color:var(--main-color);
width:400px;
height:500px;
top:570px;
margin-left:556px;
margin-bottom:10px;
border-radius:20px;
}
.card-3 h3{
padding-top:10px;
text-align:center;
font-size:35px;
}
.card-3 p{
font-size:50px;
}
.card-4 {
position:absolute;
background-color:var(--main-color);
width:400px;
height:500px;
top:570px;
margin-left:55px;
margin-bottom:10px;
border-radius:20px;
}
.card-4 h3{
padding-top:10px;
text-align:center;
font-size:35px;
}
.card-4 p{
font-size:50px;
}
#contact {
color:white;
margin:0;
margin-top:700px;
width:100%;
height:700px;
background-color:rgb(18,18,48);
border-radius:20px;
}
#whatsapp {
font-size:50px;
color:aqua;
display:block;
padding-left:20px;
padding-top:50px;
}
#facebook{
padding-top:50px;
font-size:50px;
color:aqua;
display:block;
padding-left:20px;
}
#instgram{
padding-top:50px;
font-size:50px;
color:aqua;
display:block;
padding-left:20px;
}
</style>
</head>
<body> 
<div class="header" >
<h1 id="h1" ><span>Mah</span>moud</h1>
<nav>
<ul>
<li id="a2" ><a href="#card" >content</a></li>
<li id="a3" ><a href="#card-1" >services</a></li>
<li id="a1" ><a id="ai"  href="#contact" >contact</a></li>
</ul>
</nav>
</div>

<div id="body" >
<div class="body2" >

<h1>about me</h1>

<p>i'am Mahmoud Ahmed i like play PUPG  mobile and,
 i very smart</p>
</div>
<div id="card">


<!--card1-->
<div class="card1" dir="rtl" >
<img src="num3.jpg" alt="Erorr 505" >
<h3>My work</h3>
<p>I work as a website designer</p>
</div>

<!---card1--->

<!--card2--->
<div class="card2" dir="rtl" >

<h3>How did you learn the programming I am ?</h3>

<p>There is a channel on YouTube I learned everything about programming and this channel is Alzero web school.</p>
<img src="num2.jpg" alt="Erorr 505" >

</div>
<!---card2--->

<!--card3-->
<div class="card3" dir="rtl" >
<img src="num1.jpg" alt="Erorr 505" >
<h3>look there</h3>
<p>Browse the rest of the site</p>
</div>

<!---card3--->



</div>
<!--end-card-->
</div>
<!--end-body-->
<h1 id="services11" ><span>services</span></h1>
<!--start-srvices-->
<div class="services" >

<!--card-1-->
<div id="card-1" >


<h3>Section i</h3>

<p>––––––––––––––––</p>


</div>
<!--card-1-->
<!--card-2-->
<div class="card-2" >


<h3>Section II</h3>

<p>––––––––––––––––</p>


</div>
<!--card-2-->


<!--card-3-->
<div class="card-3" >

<h3>Section III</h3>

<p>––––––––––––––––</p>

<!--card-3-->
</div>
<!--card-4-->

<div class="card-4" >



<h3>Section IIII</h3>

<p>––––––––––––––––</p>


</div>
<!--card-4-->
</div>
<!--end-srvices-->

<!--start-footer-->
<footer id="contact" >
<a href="https://www.facebook.com/profile.php?id=100067966781714&mibextid=ZbWKwL" ><span id="facebook"> <i class="fa-brands fa-facebook-f"></i> 	 facebook</span></a>
<a href="https://www.tiktok.com/@mahmoud_gaming78?_t=8Z5GTCdiMn0&_r=1" ><span id="tiktok" ><i class="fa-brands fa-tiktok"></i>		tiktok</span></a>
<a href="" ><span id="instgram"> <i class="fa-brands fa-square-instagram"></i>   instagram</span>
<a href="https://wa.me/qr/GLIWGEOKMM7RG1" ><span id="whatsapp"><i class="fa-brands fa-whatsapp" > </i>        whatsapp</span></a>
<a href="https://twitter.com/Mahmoud000797?t=8VIKHO3NOtx8blKRGClEKg&s=09" ><span id="twiter" ><i class="fa-brands fa-twitter"></i></span></a>

</footer>
<!--end-footer-->
</body>
</html>

<!doctype html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1">

<link rel="icon" type="image/png" sizes="32x32" href="https://4.bp.blogspot.com/-gzglVSg12mk/XYxxTERnMnI/AAAAAAAAAvc/U8QCbIOLRk091S6dgTSz5nBzdL6qnFruwCLcBGAsYHQ/s1600/onanion.png">

<link href='https://cdn.statically.io/gh/MaenX/onanion/master/reset.css' rel='stylesheet' type='text/css'/>
	
<link href='https://fonts.googleapis.com/css?family=Lato:300,400,700' rel='stylesheet' type='text/css'/>
<link href='//netdna.bootstrapcdn.com/font-awesome/4.0.3/css/font-awesome.min.css' rel='stylesheet' type='text/css'/>
	
<style>
	
h1,h2,h3,h4,h5,h6{
font-weight:400
}

h1 {
font-size:33px;
margin:0 auto 18px
}
h2 {
font-size:28px;
margin:0 auto 14px
}
h3 {
font-size:24px;
margin:0 auto 10px
}
h4 {
font-size:20px;
margin:0 auto 8px
}
h5 {
font-size:18px;
margin:0 auto 8px
}
h6 {
font-size:16px;
margin:0 auto 6px;
font-weight:700
}


.oposition {
text-align: center;
}
.obutton {
font-size: 1em;
padding: 10px;
color: #000;
border: 2px solid #06D85F;
border-radius: 20px/50px;
text-decoration: none;
cursor: pointer;
transition: all 0.3s ease-out;
}
.obutton:hover {
color:#000;
background: #06D85F;
}
.ooverlay {
position: fixed;
top: 0;
bottom: 0;
left: 0;
right: 0;
background: rgba(0, 0, 0, 0.7);
transition: opacity 500ms;
visibility: hidden;
opacity: 0;
}
.ooverlay:target {
visibility: visible;
opacity: 1;
}
.opopup {
margin: 70px auto;
padding: 20px;
background: #fff;
border-radius: 5px;
width: 30%;
position: relative;
transition: all 5s ease-in-out;
}
.opopup h2 {
margin-top: 0;
color: #333;
font-family: Tahoma, Arial, sans-serif;
}
.opopup .oclose {
position: absolute;
top: 20px;
right: 30px;
transition: all 200ms;
font-size: 30px;
font-weight: bold;
text-decoration: none;
color: #333;
}
.opopup .oclose:hover {
color: #06D85F;
}
.opopup .ocontent {
max-height: 30%;
overflow: auto;
}
@media screen and (max-width: 700px){
.obox{
width: 70%;
}
.opopup{
width: 70%;
}
}

a {
font-family: 'Roboto', sans-serif;
text-decoration: none
}
.link-cont {
    position: relative;
    font-size: 12px;
}

.link {
    display: inline-block;
    position: relative;
    text-decoration: none;
    padding: 10px 0;
    color: #444;
}
.link-wrapper {
    position: relative;
    display: block;
    padding: 20px 0;
}
.hover-link:after {
  content: "";
  position: absolute;
  bottom: 0;
  right: 0;
  width: 100%;
  height: 3px;
  background-color: #666;
  transform: scaleX(0);
  transform-origin: bottom right;
  transition: transform 0.3s;
}
.hover-link:hover:after {
  transform: scaleX(1);
}

</style>
	
<title>Pure CSS Popup Box</title>
</head>
<body>
	
<center>
<div class="link-cont">
<div class="link-wrapper">
<a class="link hover-link" href="https://onanion.blogspot.com/2019/08/blog-post_71.html"><i aria-hidden="true" class="fa fa-long-arrow-left"></i> Back To Article</a></div>
</div>
</center>

<br/>
<br/>

<div class="oposition">
<a class="obutton" href="#popup1">Let me Pop up</a></div>
<div id="popup1" class="ooverlay">
<div class="opopup">
<h2>
Here i am</h2>
<a class="oclose" href="#">&times;</a>
<div class="ocontent">
Thank to pop me out of that button, but now i'm done so you can close this window.
</div>
</div>
</div>
	
</body>
</html>

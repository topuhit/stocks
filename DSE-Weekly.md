---
layout: page
title: DSE-Weekly
permalink: /DSE-Weekly/
---

<br>
<br>
<div id="output"></div>
<!-- Load Babel -->
<script src="https://unpkg.com/babel-standalone@6/babel.min.js"></script>
<!-- Your custom script here -->
<script type="text/babel">

	var list = [

	"SSSTEEL",
	"GP",
	"ICB",
	"SQURPHARMA",
	"NBL",
	"LHBL",
	"BANKASIA",
	"OLYMPIC",
	"EBL",
	"PUBALIBANK",
	"KOHINOOR",
	"MTB",
	"ADNTEL",
	"RINGSHINE",


	]

var i;

var text = "";

for (i = 0; i < list.length; i++) {
    text +=   `
    <img src="https://www.amarstock.com/Chart/draw?Code=${list[i]}&OVER=OverlayV!%3B&IND=&Size=600*750&cg=1&Cycle=Week1&Width=1&type=3&bg=white&upColor=Darkgreen&downColor=Red&grid=0&sv=1&dataType=1&X=undefined&Y=undefined">
    
    <br>`
  
}


document.getElementById('output').innerHTML = text;
</script>
<style type="text/css">
			#output {
			margin: 0 auto;
			text-align: center;
		}

</style>





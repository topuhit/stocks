---
layout: page
title: DSE-Daily-Watchlist
permalink: /DSE-Daily-Watchlist/
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
	"RECKITTBEN",
	"MARICO",
	"GLAXOSMITH",
	"BATBC",
	"BERGERPBL",
	"MPETROLEUM",
	"JAMUNAOIL",
	"PADMAOIL",
	"SQURPHARMA",
	"POPULARLIF",
	"SUMITPOWER",
	"APEXTANRY",
	"BSRMSTEEL",
	"BSRMLTD"

	]

var i;

var text = "";

for (i = 0; i < list.length; i++) {
    text +=   `<h1>${list[i]}</h1><br>
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





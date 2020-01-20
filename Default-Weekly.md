---
layout: page
title: Dafault-Weekly
permalink: /Dafault-Weekly/
---

<br>
<br>
<div id="output"></div>
<!-- Load Babel -->
<script src="https://unpkg.com/babel-standalone@6/babel.min.js"></script>
<!-- Your custom script here -->
<script type="text/babel">

	var list = [

	"AAPL","ACB","AMD","APOG","APPS",
	"BABA","BYND","COST","CRM","COST",
	"DFS","DIS","DLTR","DOCU","FB","FDX","GOOG","JD",
	"KMX",
	"LYFT","MDB","MLHR","MSFT","NFLX","NVDA","NIO",
	"PCG","PM","ROKU","SHOP","SNAP","SPOT","SPY",
	"TEAM","TEVA","TIF","TLT","TSLA","TSM","TWLO","TWTR",
	"UBER","UGAZ","WORK","XLF","ZM","Z",

	]

var i;

var text = ""

for (i = 0; i < list.length; i++) {
    text +=   `<img src="https://finviz.com/chart.ashx?t=${list[i]}&ty=c&ta=0&p=w&s=l">


    <br>`
  
}


document.getElementById('output').innerHTML = text;
</script>
<style type="text/css">
			#output {
			margin: 0 auto;
			width: 80%;
			text-align: center;
		}

</style>




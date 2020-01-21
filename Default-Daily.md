---
layout: page
title: Default-Daily
permalink: /Default-Daily/
---

<br>
<br>
<div id="output"></div>
<!-- Load Babel -->
<script src="https://unpkg.com/babel-standalone@6/babel.min.js"></script>
<!-- Your custom script here -->
<script type="text/babel">

	var list = ["AAPL","ACB","AMD","APOG","APPS","ARE","ATHM","BABA","BRC","BYND","CGC","CHKP","COST","CRM","CRWD","DFS","DIS","DLTR","DOCU","FB","FDX","FSLR","FTNT","GLD","GM","GOOG","IWM","JD","KMX","KSS","LK","LYFT","MDB","MLHR","MSFT","NFLX","NIO","NLOK","NVDA","PCG","PINS","PM","ROKU","SHOP","SNAP","SPOT","SPY","TEAM","TEVA","TIF","TLT","TSCO","TSLA","TSM","TUFN","TWLO","TWTR","UBER","UGAZ","WORK","XLF","Z","ZM","ZS"]
var i;

var text = ""

for (i = 0; i < list.length; i++) {
    text +=   `<img src="https://finviz.com/chart.ashx?t=${list[i]}&ty=c&ta=1&p=d&s=l">
    
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




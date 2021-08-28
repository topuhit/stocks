---
layout: page
title: Default-5min-5days
permalink: /Default-5min-5days/
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
    text +=   `<img src="https://api.nasdaqomx.wallst.com/api/chart?display=mountain&symbol=${list[i]}&scale=linear&duration=5dy&frequency=1min&gridLine=h&bgColor=eff2f5&lineColor=0000a0&fillcolor=aabaf2|eff2f5&width=800&height=400&bdr=2&volume=0&fillOpacity=100" width="800" height="400">
    
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




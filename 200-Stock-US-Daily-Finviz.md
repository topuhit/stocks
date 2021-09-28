---
layout: page
title: 200-Stock-US-Daily-Finviz
permalink: /200-Stock-US-Daily-Finviz/
---

<div id="output"></div>
<!-- Load Babel -->
<script src="https://unpkg.com/babel-standalone@6/babel.min.js"></script>

<!-- Your custom script here -->
<script type="text/babel">


var i;

$.get( "https://topuhit.github.io/stocks/assets/stock-list.json", function( data ) {


var text = ""

data.sort()

for (i = 0; i < data.length; i++) {
    text +=   `<a href="https://finviz.com/quote.ashx?t=${data[i]}" target="_blank"> <img src="https://finviz.com/chart.ashx?t=${data[i]}&ty=c&ta=1&p=d&s=l" class="padding"></a>
    
    `
  
}


document.getElementById('output').innerHTML = text;
});


</script>

<style type="text/css">
			#output {
			margin: 0 auto;
			/*width: 80%;*/
			/*text-align: center;*/
		}
  .padding {
  	padding: 20px;
  }
</style>





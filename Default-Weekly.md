---
layout: page
title: Default-Weekly
permalink: /Default-Weekly/
---

<br>
<br>
<div id="output"></div>
<!-- Load Babel -->
<script src="https://unpkg.com/babel-standalone@6/babel.min.js"></script>
<!-- Your custom script here -->
<script type="text/babel">


$.get( "https://topuhit.github.io/stocks/assets/stock-list.json", function( data ) {
console.log(data.length)
var i;

var text = ""

for (i = 0; i < data.length; i++) {
    text +=   `<a href="https://finviz.com/quote.ashx?t=${data[i]}" target="_blank">  <img src="https://finviz.com/chart.ashx?t=${data[i]}&ty=c&ta=0&p=w&s=l"></a><br>`
  
}


document.getElementById('output').innerHTML = text;

});

</script>
<style type="text/css">
			#output {
			margin: 0 auto;
			text-align: center;
		}

</style>




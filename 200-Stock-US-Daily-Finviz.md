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

	var list = ["AAL","AAPL","ACB","ADBE","AKAM","AMD","AMT","AMZN","APPS","ATVI","BA","BABA","BAC","BBY","BIDU","BIGC","BILL","BYND","C","CAT","CCL","CHWY","CLDR","CMCSA","COST","CRM","CRWD","CSCO","CTXS","DAL","DDOG","DELL","DG","DIA","DIS","DJX","DLTR","DOCU","EA","EBAY","ETSY","F","FB","FDX","FNGO","FSLR","FSLY","GE","GILD","GLD","GM","GOOGL","GPS","GS","HAS","HD","HON","IGV","INTC","IWM","JCPNQ","JD","JNJ","JPM","KIRK","KMX","LK","LMT","LULU","LVGO","LYFT","MA","MCD","MDB","MDT","MGM","MMM","MRK","MSFT","MU","NET","NFLX","NIO","NKE","NKLA","NOW","NVDA","OKTA","ORCL","OSTK","OXY","PAYC","PAYX","PDD","PENN","PEP","PFE","PINS","PM","PODD","PTON","PYPL","QCOM","QQQ","RCL","REGN","RKT","ROKU","RTX","SAP","SBUX","SE","SHOP","SLV","SMAR","SNAP","SNPS","SPCE","SPLK","SPOT","SPX","SPXL","SPY","SQ","STM","SWKS","T","TCOM","TEAM","TECL","TGT","TIF","TLT","TM","TMUS","TNA","TQQQ","TSCO","TSLA","TSM","TTD","TTM","TWLO","TWTR","UAA","UAL","UBER","UCO","ULTA","UNH","UPS","V","VIX","VMW","VRM","VRSN","W","WDAY","WDC","WHR","WIX","WM","WMT","WORK","XLF","XLK","XOM","Z","ZEN","ZM"]
var i;

var text = ""

for (i = 0; i < list.length; i++) {
    text +=   `<img src="https://finviz.com/chart.ashx?t=${list[i]}&ty=c&ta=1&p=d&s=l" class="padding">
    
    `
  
}


document.getElementById('output').innerHTML = text;
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





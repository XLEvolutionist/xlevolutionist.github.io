---
title: "research highlights"
bg: silver
color: black
fa-icon: laptop
---

### Copy-number variants (CNVs) in wild maize


I am currently developing a novel CNV calling pipeline, currently in testing. Preliminary data (see figures below) suggest that the pipeline is working well and we have identified a ~10 MB deletion on chromosome 6 segregating in a wild population of maize (otherwise known as teosinte). 
Furthermore we note that estimates of [Tajima's D](https://en.wikipedia.org/wiki/Tajima's_D) over regions where CNV segregate differ from the background "genome-wide" level.


<script language="JavaScript1.2">

var howOften = 5; //number often in seconds to rotate
var current = 0; //start the counter at 0
var ns6 = document.getElementById&&!document.all; //detect netscape 6

// place your images, text, etc in the array elements here
var items = new Array();
    items[0]="<href="img/fig_2 copy.jpeg"><img src="img/fig_2 copy.jpeg" height='300' width='300' border='0' /></a>"; //a linked image
    items[1]="a href="img/fig_6 copy.jpeg"><img src="img/fig_6 copy.jpeg" alt="TD" title="TD" height='300' width='300' border='0' /></a>"; //a linked image
function rotater() {
    document.getElementById("placeholder").innerHTML = items[current];
    current = (current==items.length-1) ? 0 : current + 1;
    setTimeout("rotater()",howOften*1000);
}

function rotater() {
    if(document.layers) {
        document.placeholderlayer.document.write(items[current]);
        document.placeholderlayer.document.close();
    }
    if(ns6)document.getElementById("placeholderdiv").innerHTML=items[current]
        if(document.all)
            placeholderdiv.innerHTML=items[current];

    current = (current==items.length-1) ? 0 : current + 1; //increment or reset
    setTimeout("rotater()",howOften*1000);
}
window.onload=rotater;
//-->
</script>
                 
### Gene loss in the ancient sub-genomes of cotton  

Here is some text to be modified later.

<script>
  (function(i,s,o,g,r,a,m){i['GoogleAnalyticsObject']=r;i[r]=i[r]||function(){
  (i[r].q=i[r].q||[]).push(arguments)},i[r].l=1*new Date();a=s.createElement(o),
  m=s.getElementsByTagName(o)[0];a.async=1;a.src=g;m.parentNode.insertBefore(a,m)
  })(window,document,'script','//www.google-analytics.com/analytics.js','ga');

  ga('create', 'UA-64425631-1', 'auto');
  ga('send', 'pageview');

</script>


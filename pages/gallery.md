---
title: Galleri
nav: Galleri
nav_order: 2
---

<br/>


<!--  {% include buttonfilter.html type="forsale"  text="Til salg" %} -->
<!--  {% include buttonfilter.html category="blomster"  text="Billeder med blomster" %} -->
 {% include buttonfilter.html category="1891-1893"  text="Periode 1891-1893" %}
 {% include buttonfilter.html category="1895-1903"  text="Periode 1895-1903" %} 
 {% include buttonfilter.html type="removefilter" text="X" %}
 <div class="grid-container"></div>


{% include gallerydata.html %} 
{% include gallerylogic.html %}
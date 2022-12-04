---
title: Galleri
nav: Galleri
nav_order: 2
---

<br/>


 {% include buttonfilter.html type="forsale"  text="Til salg" %}
 {% include buttonfilter.html category="blomster"  text="Billeder med blomster" %}
 {% include buttonfilter.html category="landskab"  text="Landskaber" %}
 {% include buttonfilter.html category="personer"  text="Personer" %} 
 {% include buttonfilter.html type="removefilter" text="X" %}
 <div class="grid-container"></div>

{% include gallerydata.html %}
{% include gallerylogic.html %}
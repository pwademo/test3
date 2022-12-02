---
title: Galleri
nav: Galleri
nav_order: 2

---

<!-- {% include button.html text="Værker" link="#all"  color="none" %}

{% include button.html text="Værker til salg" link="#foresale" color="none" %} -->

<!-- <span class="filter" data-showall>Alle</span> 
<span class="filter" data-forsale>Til salg</span>
<span class="filter" data-category="blomster">Blomster</span>
<span class="filter" data-category="landskab">Landskab</span>
<span class="filter" data-forsale data-category="personer">Potrætter til salg</span>
<span class="filter" data-category="personer">Personer</span>     -->


<br/>


 {% include buttonfilter.html type="forsale"  text="Til salg" %}
<!---->  {% include buttonfilter.html category="blomster"  text="Billeder med blomster" %}
 {% include buttonfilter.html category="landskab"  text="Landskaber" %}
  {% include buttonfilter.html category="personer"  text="Personer" %} 
 {% include buttonfilter.html type="removefilter" text="X" %}

<!--   <div id="buttons">
      <button id="btnAlle" disabled="true">Alle malerier</button> 
      <button id="btnTilSalg">Malerier til salg</button>
  </div> -->

  <div class="grid-container"></div>  


  
{% include gallerydata.html %}
{% include gallerylogic.html %}
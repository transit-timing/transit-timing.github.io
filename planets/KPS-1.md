---
layout: post
style: planet
---
<script src="../js/planets.js"></script>

## KPS-1

<!-- Tab links -->
<div class="tab">
<button class="tablinks" onclick="openCity(event, 'Ephemeris')">Ephemeris</button>
<button class="tablinks" onclick="openCity(event, 'Data')">Data</button>
<button class="tablinks" onclick="openCity(event, 'Figures')">Figures</button>
</div>

<!-- Tab content -->
<div id="Ephemeris" class="tabcontent" markdown="1">
<br/><br/>
$$P = 1.7063254(76) $$ day <br/>
$$T_0 = 2458684.02836(25) $$ BJD TDB
<br/><br/>
<br/><br/>
![alt text](/images/KPS-1_o_c.png)
</div>


<div id="Data" class="tabcontent" markdown="1">

{% include data/data_KPS-1.md %}

</div>

<div id="Figures" class="tabcontent" markdown="1">
{% include figures/figures_KPS-1.md %}
</div>


<script src="../js/tabs.js"></script>



---
name: IS445 Homework 10
tools: [Python, HTML, vega-lite]
image: assets/pngs/chart_static.png
description: This is a "showcase" project that uses vega-lite for interactive viz!
custom_js:
  - vega.min
  - vega-lite.min
  - vega-embed.min
  - justcharts
---


# IS445 Final Project: IMDb Movies Dataset!

Interactive Chart:
<vegachart schema-url="{{ site.baseurl }}/assets/json/final_pt2_interactive1.json" style="width: 100%"></vegachart>
Description: 

Static Chart:
<vegachart schema-url="{{ site.baseurl }}/assets/json/final_pt2_interactive2.json" style="width: 100%"></vegachart>
Description: 


<div class="left">
{% include elements/button.html link="https://github.com/Zairzok/zairzok.github.io/blob/main/_data/building_inventory.csv" text="The Data" %}
</div>

<div class="right">
{% include elements/button.html link="https://github.com/zairzok/zairzok.github.io/blob/main/python_notebooks/peterson_jacob_hw10.ipynb" text="The Analysis" %}
</div>


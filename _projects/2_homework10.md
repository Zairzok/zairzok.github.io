---
name: Vega Lite Example Project
tools: [Python, HTML, vega-lite]
image: assets/pngs/cars.png
description: This is a "showcase" project that uses vega-lite for interactive viz!
custom_js:
  - vega.min
  - vega-lite.min
  - vega-embed.min
  - justcharts
---


# IS445 Homework Assignment #10

Interactive Chart:
<vegachart schema-url="{{ site.baseurl }}/assets/json/chart_interactive.json" style="width: 100%"></vegachart>

Static Chart:
<vegachart schema-url="{{ site.baseurl }}/assets/json/chart_static.json" style="width: 100%"></vegachart>


<div class="left">
{% include elements/button.html link="'https://raw.githubusercontent.com/UIUC-iSchool-DataViz/is445_bcubcg_fall2022/main/data/building_inventory.csv" text="The Data" %}
</div>

<div class="right">
{% include elements/button.html link="https://github.com/jnaiman/online_cv_public/blob/main/python_notebooks/test_generate_plots.ipynb" text="The Analysis" %}
</div>


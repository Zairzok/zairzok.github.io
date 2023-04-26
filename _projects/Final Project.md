---
name: IS445 Final Project (IMDb Movies Dataset)
tools: [Python, HTML, vega-lite]
image: assets/pngs/imdb_logo.png
description: This is a "showcase" project that uses vega-lite & Altair & Python for interactive viz!
custom_js:
  - vega.min
  - vega-lite.min
  - vega-embed.min
  - justcharts
---


# IMDb Movies Dataset!

Interactive Chart:
<vegachart schema-url="{{ site.baseurl }}/assets/json/final_pt2_interactive1.json" style="width: 100%"></vegachart>
Description: 

Static Chart:
<vegachart schema-url="{{ site.baseurl }}/assets/json/final_pt2_interactive1.json" style="width: 100%"></vegachart>
Description: need to edit so that the histogram has correct labels


<div class="left">
{% include elements/button.html link="https://github.com/Zairzok/zairzok.github.io/blob/main/_data/movies.csv" text="The Data" %}
</div>

<div class="right">
{% include elements/button.html link="https://github.com/zairzok/zairzok.github.io/blob/main/python_notebooks/Final_Project_Part_2.ipynb" text="The Analysis" %}
</div>


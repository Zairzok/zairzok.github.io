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


# IS445 Homework Assignment #10

Interactive Chart:
<vegachart schema-url="{{ site.baseurl }}/assets/json/chart_interactive.json" style="width: 100%"></vegachart>
Description: 
This is a interactive visualization that I created in order to show the year the buildings under each agency were constructed. I then let the user select certain areas and that alters the histogram to show the count of the district number. I wanted to try and find a connection between the Agencies, District Representatives, and the age of the buildings. I did not really find any connections unfortunately so I should probably have found another path to go down but I have been extremely busy as we are wrapping up the semester, so I thought it would be easier to write about how I got it to finanly work but it did not result in any connections like I hoped that it would. It does seem however that the majority of the buildings were built between 1920 and 2010. So that is at least some information that can be pulled from this visual. I had initially chose a bar chart for the left visual but I did not think that it looked appealing and it was not showing the infromation accurately. So i oped to go with the scatter plot and I am happy enought with how it turned out. Although I wish it had more room, I probably should have stacked these two on top of each other instead of side by side so that it would be better looking and not as smushed together. It took my awhile to figure out how to get it from html and javascript on Starboard to Python in the Jupyter Notebook. However, I found the class recordings really helpful and I just used the code and examples from there as the skeleton and then built from there. Once that was done then I had to attend office hours to figure out how to upload to here since my github was not working because I created it wrong. Overall I thought it was fun to figure out and I am still enjoying learning more about interactivity since I see a lot of use in it. I saw its use in my visual even though it did not give me any ground breaking information but I still found the interactivity super cool and useful. 

Static Chart:
<vegachart schema-url="{{ site.baseurl }}/assets/json/chart_static.json" style="width: 100%"></vegachart>
Description: 
This was a chart that I sort of took from homework number nine. I know that I at least got the main parts from there but I also think I changed it a little. Anyway, I wanted to go with something simple that would also be effective so I wanted to use a bar graph and I wanted to aggreagate the data in some way. So I chose to stick with the agencies since I used those in the previous visual and then I chose to aggregate and count the agencies to see which one was the most popular or large. This was very simple but it was also really effective since it was easy to answer my question and it made it really easy to see. This one was a lot easier to figure out how to transform since it was super similar to the previous but way more simple. It as a pain to convert everything using Altair though. I had to rewatch the lectures and use the internet a ton to figure that part out and make sure that I was doing it correctly. 

<div class="left">
{% include elements/button.html link="'https://raw.githubusercontent.com/UIUC-iSchool-DataViz/is445_bcubcg_fall2022/main/data/building_inventory.csv" text="The Data" %}
</div>

<div class="right">
{% include elements/button.html link="https://github.com/zairzok/zairzok.github.io/blob/main/python_notebooks/peterson_jacob_hw10.ipynb" text="The Analysis" %}
</div>


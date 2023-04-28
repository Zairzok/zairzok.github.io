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
by Jacob Peterson

Have you ever gone to the movies or watched a movie at home and after the credits roll you were like, “Wow that was awesome! What a great movie! I wonder what others thought of it?”. Then you look up the movie's ratings online to find that it was rated really poorly. Maybe you have experienced the opposite! Maybe you saw a movie that you thought was just awful but then you find out later it was rated really well by critics. If you are anything like me then this probably frustrated you and made you wonder what really makes a movie “good”. That is what led me to writing this article and exploring this topic as a whole. I hope that you enjoy my visualizations and my findings!

To start with I want to talk about my interactive visualization. I chose this visualization when I was thinking of other variables that are similar to rating. I asked myself, “What else could show that a movie was successful besides its rating?”. I thought that a good way to determine a movie's success could be the profit it made. The dataset that I am using includes information that was scraped from the iMDb website. Which is a website that keeps a ton of information on movies new and old. This dataset includes the top 100 movies from each year starting in 2003 and ending in 2022. It also included the ratings, titles, certificates, income, and budgets for all of those films. With all that being said, I made a graph that included the income on the y-axis and the year on the x-axis. I then connected this to a histogram that would display the ratings of the movies that are selected on the original plot. So if I selected 10 movies with my cursor, then the histogram would take those points that represent movies and it would take their ratings and display them in the histogram. This was how I wanted to look at relations between rating and income. However, this graph also allowed me to look at these factors in relation to the years as well since I could select certain areas including by year. I also wanted to make it easier for the viewer (you) and so I added a drop down option that would allow you to reduce the clutter of the graph by filtering by the certification. 

My next graphs were more basic but also important. I created a line graph that included the rating on the y-axis and the title of the movies on the x-axis. This plot also only included the movies from the year 2022. I continued with this trend to create another basic bar plot that included the title of the movie on the y-axis and the budget of the movie on the x-axis. These two plots were very basic but also were very nice to see the breakdown of ratings and budget in a single year. This way I could look for trends, and it would be relatively up to date since 2022 was just last year! 

My findings were pretty lackluster though. I found a few connections that relate budget to overall rating. However, I did not find anything that was solid enough for me to say for sure. So overall I found that there really is no real way to determine if a film is going to be successful. Looking at other factors can help in some cases but it is not consistent enough for me to say for certain. I recommend looking at ratings from multiple sources and, if you can, look at the critics scores vs the peoples scores. That is another angle I will start to look at when I revisit this topic in the future! 

Thank you for reading!



Interactive Chart:
<vegachart schema-url="{{ site.baseurl }}/assets/json/final_pt2_interactive_final.json" style="width: 100%"></vegachart>

Interactive Chart:
<vegachart schema-url="{{ site.baseurl }}/assets/json/final_pt2_interactive_test.json" style="width: 100%"></vegachart>

Static Chart:
<vegachart schema-url="{{ site.baseurl }}/assets/json/final_pt2_Title_Budget_Basic.json" style="width: 100%"></vegachart>

Static Chart:
<vegachart schema-url="{{ site.baseurl }}/assets/json/final_pt2_Title_Rating_Basic.json" style="width: 100%"></vegachart> 

Static Chart:
<vegachart schema-url="{{ site.baseurl }}/assets/json/final_pt2_Title_Rating_Line.json" style="width: 100%"></vegachart>


<div class="left">
{% include elements/button.html link="https://github.com/Zairzok/zairzok.github.io/blob/main/_data/movies.csv" text="The Data" %}
</div>

<div class="right">
{% include elements/button.html link="https://github.com/zairzok/zairzok.github.io/blob/main/python_notebooks/Final_Project_Part_2.ipynb" text="The Analysis" %}
</div>


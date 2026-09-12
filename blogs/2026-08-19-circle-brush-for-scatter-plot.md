---
title: "Circle brush for scatter plot"
url: "https://community.plotly.com/t/circle-brush-for-scatter-plot/97435#post_3"
date: "2026-08-19"
author: "@AnnMarieW"
feed_url: "https://community.plotly.com/posts.rss"
---
Hi @binary Can you say more about what you are looking for? If you are just trying to allow the user to draw multiple circles you could use something like: import plotly.express as px df = px.data.iris() fig = px.scatter( df, x="sepal_width", y="sepal_length", ) fig.update_layout( dragmode="drawcircle", modebar_add=["drawcircle", "eraseshape"], ) fig.show() Or are you trying to allow the user to select points using a circle rather than lasso?

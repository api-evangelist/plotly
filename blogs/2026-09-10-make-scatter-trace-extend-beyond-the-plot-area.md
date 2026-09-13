---
title: "Make scatter trace extend beyond the plot area"
url: "https://community.plotly.com/t/make-scatter-trace-extend-beyond-the-plot-area/97590#post_5"
date: "2026-09-10"
author: "@ckkart Christian"
feed_url: "https://community.plotly.com/posts.rss"
---
That’s better, right. But I whenever I try to add axes on two distinct subplots the result is weird. import plotly.graph_objects as go from plotly.subplots import make_subplots x = list(range(11)) top = [1, 0.6, 0.9, 0.3, 0.7, 0.2, 0.5, -0.2, 0.1, -0.6, -1] bottom = [-1, -0.4, 0.2, -0.3, 0.5, 3.5, 0.4, -0.2, 0.3, 0.6, 1] #

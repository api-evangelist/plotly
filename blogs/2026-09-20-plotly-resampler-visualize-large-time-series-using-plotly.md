---
title: "💫 Plotly-resampler - Visualize large time series using plotly-dash"
url: "https://community.plotly.com/t/plotly-resampler-visualize-large-time-series-using-plotly-dash/59097?page=2#post_24"
date: "2026-09-20"
author: "@jvdd Jeroen Van Der Donckt"
feed_url: "https://community.plotly.com/posts.rss"
---
@ulibussi what you are describing is exactly what we do in flexviz: GitHub - flex-analytics/flexviz: Interactive cross-filter dashboards on 100M+ rows, in pure Python. Polars-native · GitHub In flexviz we keep the data lazy (i.e., not in memory) and stream the data from disk to ram → allows the visualize larger-than-ram dataset. Basically, this is the successor of the plotly-resampler library; in addition to line charts, it supports 9 other trace types (through highly optimized data aggregation), the server is now stateless, and it comes with native cross-filtering.

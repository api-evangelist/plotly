---
title: "Migrating from DataTable to Dash AG Grid: Conditional Formatting"
url: "https://community.plotly.com/t/migrating-from-datatable-to-dash-ag-grid-conditional-formatting/97792#post_1"
date: "2026-10-01"
author: "@AnnMarieW"
feed_url: "https://community.plotly.com/posts.rss"
---
Conditional Formatting Recipes This post shows how to recreate the conditional formatting recipes from the DataTable documentation using Dash AG Grid. For more information please see the Dash Docs AG Gris styling sections, including: Styling Rows Styling Cells Highlighting the Max Value in a Column from dash import Dash import pandas as pd import dash_ag_grid as dag data = dict( [ ("Date", ["2015-01-01", "2015-10-24", "2016-05-10", "2017-01-10", "2018-05-10", "2018-08-15"]), ("Region", ["Montreal", "Toronto", "New York City", "Miami", "San Francisco", "London"]), ("A", [1, -20, 3.512, 4, 10423

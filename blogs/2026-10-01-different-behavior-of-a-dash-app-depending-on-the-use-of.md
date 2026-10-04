---
title: "Different behavior of a Dash app depending on the use of the embedded web server or of gunicorn"
url: "https://community.plotly.com/t/different-behavior-of-a-dash-app-depending-on-the-use-of-the-embedded-web-server-or-of-gunicorn/97763#post_2"
date: "2026-10-01"
author: "@AnnMarieW"
feed_url: "https://community.plotly.com/posts.rss"
---
Hi @jfh999 and welcome to the Dash community For a Dash app, you don’t normally need to subclass gunicorn.app.base.BaseApplication . Here’s a more typical pattern: from dash import Dash app = Dash() server = app.server then Gunicorn can be started from the command line: gunicorn app:server or with more settings: gunicorn --bind 0.0.0.0:10033 --workers 2 app:server

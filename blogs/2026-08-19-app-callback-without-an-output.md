---
title: "App callback without an output"
url: "https://community.plotly.com/t/app-callback-without-an-output/5502?page=2#post_38"
date: "2026-08-19"
author: "@AnnMarieW"
feed_url: "https://community.plotly.com/posts.rss"
---
This is an old post, but it’s still popular, so I wanted to make sure anyone who finds it through a search gets the current answer. Callbacks with no outputs have been supported since Dash 2.17: dash.plotly.com Callbacks with No Outputs - Advanced Callbacks | Dash for Python Documentation |... In this case, prevent_initial_call will prevent the update_output() callback from firing when its input is first inserted into the app layout as a result of the display_page() callback.

---
title: "Reproducible figure-interchange format + a Plotly-figure mapping — interop feedback welcome"
url: "https://community.plotly.com/t/reproducible-figure-interchange-format-a-plotly-figure-mapping-interop-feedback-welcome/97566#post_1"
date: "2026-09-04"
author: "@Isaac_Neuhaus Isaac Neuhaus"
feed_url: "https://community.plotly.com/posts.rss"
---
We maintain cxspec , a versioned, self-describing figure format: a single portable JSON object that carries a chart’s data and the spec to render it, with a stated forward-render/compatibility policy, a structural round-trip guarantee, and an optional provenance hash. Schemas (JSON Schema 2020-12) and conformance fixtures are public: GitHub - neuhausi/cxspec · GitHub The goal is interchange, not a silo — a figure should be able to move between tools and still reproduce. We already ship a dependency-free vega-lite → cxfigure converter ( cxspec/converters/vega-lite at main · neuhausi/cxspec · Gi

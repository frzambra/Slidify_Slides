---
title       : Example Presentation 
subtitle    : Webmapping app for drought monitoring
author      : Francisco Zambrano Bigiarini
job         : 
framework   : io2012        # {io2012, html5slides, shower, dzslides, ...}
highlighter : highlight.js  # {highlight.js, prettify, highlight}
hitheme     : tomorrow      # 
widgets     : [mathjax]            # {mathjax, quiz, bootstrap}
mode        : selfcontained # {standalone, draft}
knit        : slidify::knit2slides
---

## Summary

This is an example of making presentations using Slidify used to show one application made on Shiny to show the assessment of the agricultural drought on the BioBio Region of Chile for the last sixteen years. This webmapping show the Vegetation Condition Index (VCI) aggregated at administrative unit on the Region for each period of 16 days, also present the Standarized Precipitation Index (SPI) for 26 weather stations.

---

## Vegetation Condition Index (VCI)

This is the equation for the vegetation condition index calculated from data of NDVI.

$$VCI = \frac{NDVI - NDVI_{min}}{NDVI_{max}-NDVI_{min}}$$

---

## Derivation of VCI 

![plot of chunk unnamed-chunk-1](assets/fig/unnamed-chunk-1-1.png)

---

## Derivation of VCI

![plot of chunk unnamed-chunk-2](assets/fig/unnamed-chunk-2-1.png)

---

## Hyperlink to an a Shiny app

<iframe src="https://frzambra.shinyapps.io/shinyapp/" width=100% height=500 allowtransparency="true"> </iframe>

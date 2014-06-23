---
title       : IRIS Explorer Shiny App
subtitle    : Coursera
author      : kaushik912
job         : 
framework   : io2012        # {io2012, html5slides, shower, dzslides, ...}
highlighter : highlight.js  # {highlight.js, prettify, highlight}
hitheme     : tomorrow      # 
widgets     : []            # {mathjax, quiz, bootstrap}
mode        : selfcontained # {standalone, draft}
---

## Slide1: Why IRIS Explore Shiny App?

1. Visualize the iris dataset.
2. Look for any interesting patterns

---

## Slide2: Why IRIS Explore Shiny App (Contd.)?

1. Explore relationships between variables.
2. Graphically visualize them
3. Add jitters, smoothers to these plots
4. Learn Shiny through this project


---

## Slide3: Example Code


```r
library(ggplot2)
ggplot(data=iris,aes(Sepal.Length,Sepal.Width,color=Species))+geom_point()+facet_grid(.~Species)
```

---

## Slide4: Some Plots in Shiny App

![plot of chunk unnamed-chunk-2](figure/unnamed-chunk-2.png) 

---

## Slide5: Links

1. Github link for code
2. Shiny App for viewing the demo


---
title       : Introduction to R
subtitle    : Slidify
author      : Mohammed Omar
job         : Researcher/Bioinformatician
framework   : io2012        # {io2012, html5slides, shower, dzslides, ...}
highlighter : highlight.js  # {highlight.js, prettify, highlight}
hitheme     : tomorrow      # 
widgets     : []            # {mathjax, quiz, bootstrap}
mode        : selfcontained # {standalone, draft}
knit        : slidify::knit2slides
transition  : rotate
---

## Read-And-Delete

1. Edit YAML front matter
2. Write using R Markdown
3. Use an empty line followed by three dashes to separate slides!

--- .class #id 

## Slide 2

 

```r
library(RColorBrewer)
with(iris, boxplot(Sepal.Length~Species,col=brewer.pal(3,"Set1")))
```

![plot of chunk unnamed-chunk-1](assets/fig/unnamed-chunk-1-1.png)

---

## Slide 3


```r
library(viridis)
with(iris, boxplot(Petal.Length~Species,col=viridis(3)))
```

![plot of chunk unnamed-chunk-2](assets/fig/unnamed-chunk-2-1.png)



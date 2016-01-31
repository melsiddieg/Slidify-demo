---
title       : Introduction to R
subtitle    : Slidify
author      : Mohammed Omar
job         : Researcher/Bioinformatician
framework   : io2012       # {io2012, html5slides, shower, dzslides, ...}
highlighter : highlight.js  # {highlight.js, prettify, highlight}
hitheme     : tomorrow      # 
widgets     : [bootstrap,quiz,interactive]            # {mathjax, quiz, bootstrap}
mode        : selfcontained # {standalone, draft}
knit        : slidify::knit2slides


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

--- &radio

## Question 1

What is right R syntax to extract the 4th element in the third couln from a dataframe named df?

1. df[3:4]  
2. _df[3,4]_  
3. df[c(3,4),]  
4. df[4,3]  

*** .explanation 
Because dataframe is 2D (two-dimensional), the first dimension is the row and the second dimensioon is the column
*** .hint
Remember a dataframe is two-dimensional

---

## Two Column Layout   
This slide has two columns
*** left
- point 1
- point 2
- point 3
*** right
- point 1
- point 2
- point 3
## Slide with Bullets

- Bullet 1
- Bullet 2
- Bullet 3



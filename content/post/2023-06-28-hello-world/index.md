---
title: hello world
author: green zhao
date: '2023-06-28'
slug: hello-world
categories:
  - R
tags:
  - regression
---


```r
# this is a r file
library(ggplot2)
colnames(iris)
```

```
## [1] "Sepal.Length" "Sepal.Width"  "Petal.Length" "Petal.Width"  "Species"
```

```r
ggplot(iris,aes(x=Sepal.Length,y=Sepal.Width,color=Species))+geom_point()
```

<img src="{{< blogdown/postref >}}index_files/figure-html/unnamed-chunk-1-1.png" width="672" />

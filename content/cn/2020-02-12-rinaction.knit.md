---
title: R in action<U+5B9E><U+7528><U+7B14><U+8BB0>(<U+6301><U+7EED><U+66F4><U+65B0>)
author: 'Jon'
date: '2020-02-12'
slug: bookdata
categories:
  - R
tags:
  - data science
---

1. Some function to manage the R workSpace

```r
##change the working direction
##setwd()

##show the current working direction
getwd()
```

```
## [1] "C:/blogdown/butter/content/cn"
```

```r
##save images
save.image("myfile")
png("filename.png")
```

2. creat a matrix

```r
y <- matrix(1:20, nrow = 5, ncol = 4)

y
```

```
##      [,1] [,2] [,3] [,4]
## [1,]    1    6   11   16
## [2,]    2    7   12   17
## [3,]    3    8   13   18
## [4,]    4    9   14   19
## [5,]    5   10   15   20
```

3. input excel or csv files


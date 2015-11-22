---
title       : Reproducible Pitch Presentation
subtitle    : Developing Data products Project
author      : SM
job         : 
framework   : io2012        # {io2012, html5slides, shower, dzslides, ...}
highlighter : highlight.js  # {highlight.js, prettify, highlight}
hitheme     : tomorrow      # 
widgets     : []            # {mathjax, quiz, bootstrap}
mode        : selfcontained # {standalone, draft}
knit        : slidify::knit2slides
---

## Slide 2

Overview

This is a presentation created as part of the Coursera project for the course 'Developing Data Products'. This explains the Shiny application created as part of this project.

--- .class #id 

## Slide 3

Description

This shiny application is a simple calculation to find maximum value from a list of input values.

--- .class #id 

## Slide 4
User can input 5 numbers. Once they click on submit button, the input values and the maximum number is displayed on the screen


--- .class #id 

## Slide 5

Result
The max function is used to get the maximum value among the list of numbers.

```r
maxvalue <- max(c(10,20,30,40,50))
maxvalue
```

```
## [1] 50
```







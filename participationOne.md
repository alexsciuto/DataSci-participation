---
title: "untited"
output: html_document
---

```{r setup, include=FALSE}
knitr::opts_chunk$set(echo = TRUE)
```

## R Markdown

This is an R Markdown document. Markdown is a simple formatting syntax for authoring HTML, PDF, and MS Word documents. For more details on using R Markdown see <http://rmarkdown.rstudio.com>.

When you click the **Knit** button a document will be generated that includes both content as well as the output of any embedded R code chunks within the document. You can embed an R code chunk like this:

```{r cars}
summary(cars)
```

## Including Plots

You can also embed plots, for example:

```{r pressure, echo=FALSE}

2 + 2 
3 + 4

number = 3
number
number = 2

number = 5
number * 2

times = c(17, 30, 25, 35, 25, 30, 40, 20)
times
mean(times)

time_hours = times/ 60

mean(times)
range(times)
sqrt(times)

times 
times > 30
times == 17

which(times > 30)
all(times > 30)
?any

help(any)

times[times > 30]
times[3]
times[-3]

3:5
times[3:5]
times[c(2,4)]
times[-c(2,4)]
times[times > 30]

times
times[1] = 47
times

times[times>30]= NA
times

times[times > 30] = c(0,1)

times = c(17, 30, 25, 35, 25, 30, 40, 20)


times[times > 30] <- NA
times
mean(times)
mean(times, na.rm = NA)

#mean of values between 20 and 30
times[times > 20 & times < 35]
times > 20
times < 35
times > 20 | times < 35


mean(x = times)
mean(times)
mean(times, trim = .2, na.rm =  TRUE)

mtcars
?mtcars

str(mtcars)

head(mtcars)


  ```
Note that the `echo = FALSE` parameter was added to the code chunk to prevent printing of the R code that generated the plot.

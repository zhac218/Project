---
title: "CodeBook"
author: "Eric Hullander"
date: "Friday, July 24, 2015"
output: html_document
---



```{r, echo=FALSE, message=FALSE, results='markup'}
  x<-read.table("tidy.txt", header=TRUE)

  print("Column Names:", quote=FALSE)
  print(names(x),quote=FALSE)
  print("subject: ", quote=FALSE)
  print(as.matrix(unique(x$subject)),quote=FALSE)
  print("activity: ", quote=FALSE)
  print(as.matrix(unique(x$activity)),quote=FALSE)
  print("variable: ", quote=FALSE)
  print(as.matrix(unique(x$variable)),quote=FALSE)
    
```


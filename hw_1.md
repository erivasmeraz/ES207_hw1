---
title: "hw_1"
author: "Edwin Rivas Meraz"
date: "1/26/2020"
output: 
  html_document: 
    keep_md: true
---



# Problems 1-6

```r
x <- c(1,2,4)
q <- c(x,x,8)
#Problem 3
x[4]
```

```
## [1] NA
```

```r
#Problem 4
s <- sd(q)
s
```

```
## [1] 2.478479
```

```r
#Problem 5
paste("Edwin","Rivas","Meraz")
```

```
## [1] "Edwin Rivas Meraz"
```

```r
#assign value to object "m"
m <- 100
ls()
```

```
## [1] "m" "q" "s" "x"
```

```r
#Problem 6
rm(m)
ls()
```

```
## [1] "q" "s" "x"
```

```r
rm(list=ls())
ls()
```

```
## character(0)
```
# Problems 7-

```r
oddcount <- function(x) {
  print(x)
  k <- 0
  print(paste("k is initialized as",k))
  for(n in x) {
    print(paste("current x value being tested is",n))
    if(n %% 2 == 1)
    {
      k <- k+1
      print(paste(n,"is an odd number!"))
    } else 
    {
      print(paste(n,"is an even number!"))
    }
    print(paste("The final is currently",k))
  }
  print(paste("The final k is",k))
  return(k)
}
#Problem 7
oddcount (x <- c(1,2,3,7,9))
```

```
## [1] 1 2 3 7 9
## [1] "k is initialized as 0"
## [1] "current x value being tested is 1"
## [1] "1 is an odd number!"
## [1] "The final is currently 1"
## [1] "current x value being tested is 2"
## [1] "2 is an even number!"
## [1] "The final is currently 1"
## [1] "current x value being tested is 3"
## [1] "3 is an odd number!"
## [1] "The final is currently 2"
## [1] "current x value being tested is 7"
## [1] "7 is an odd number!"
## [1] "The final is currently 3"
## [1] "current x value being tested is 9"
## [1] "9 is an odd number!"
## [1] "The final is currently 4"
## [1] "The final k is 4"
```

```
## [1] 4
```

```r
#Problem 8
evencount <- function(x) {
  print(x)
  k <- 0
  print(paste("k is initialized as",k))
  for(n in x) {
    print(paste("current x value being tested is",n))
    if(n %% 2 == 0)
    {
      k <- k+1
      print(paste(n,"is an odd number!"))
    } else 
    {
      print(paste(n,"is an even number!"))
    }
    print(paste("The final is currently",k))
  }
  print(paste("The final k is",k))
  return(k)
}
evencount (x <- c(1,2,3,7,9))
```

```
## [1] 1 2 3 7 9
## [1] "k is initialized as 0"
## [1] "current x value being tested is 1"
## [1] "1 is an even number!"
## [1] "The final is currently 0"
## [1] "current x value being tested is 2"
## [1] "2 is an odd number!"
## [1] "The final is currently 1"
## [1] "current x value being tested is 3"
## [1] "3 is an even number!"
## [1] "The final is currently 1"
## [1] "current x value being tested is 7"
## [1] "7 is an even number!"
## [1] "The final is currently 1"
## [1] "current x value being tested is 9"
## [1] "9 is an even number!"
## [1] "The final is currently 1"
## [1] "The final k is 1"
```

```
## [1] 1
```
# 9
- Integrity of data
- Portability of the project
- Helps kickstart a project after a hiatus
- Helps introduce others to your project
- Helps present your data

# 10
- Treat data as read only
- Treat generated output as disposable
- Separate function definition and application

# 11
C:\\Program Files\\RStudio

# 12
/Users/edwin/Program Files/RStudio/

# 13
"C:\Users\edwin\OneDrive - University of California Merced\Environmental Data Analysis\Homework 1"

# 14
C:\Users\edwin\OneDrive - University of California Merced\

# 15
/Users/edwin/OneDrive - University of California Merced/Environmental Data Analysis/Homework 1
/Users/edwin/OneDrive - University of California Merced/

# 16

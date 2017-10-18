---
layout: page
title: Exercises for 'Meta-analysis in biological and environmental sciences'

---


### Before our course 

1) Read a [general overview of 'metafor'](http://www.jstatsoft.org/v36/i03/), the principal R package that we will be using in this course.    
2) Install [R](https://cran.r-project.org/) and [RStudio](https://www.rstudio.com/products/rstudio/download/).  
3) Install the following packages:

```
install.packages(c("metafor","compute.es","ggplot2","dplyr","reshape2","broom","tidyr"),quietly=TRUE)
```
4) If you already have R installed, please update it to the latest version:  

```

install.packages('installr')

updateR()

```

5) Update your packages to the latest version as well:  

```
update.packages()
```

### Course schedule & exercises  

Throughout this course we will use data from [NCEAS](https://www.nceas.ucsb.edu/meta/publications.html#d_t_t)  
You can download the data directly or download using the R code included in the exercises.  

[Day 1: Calculating effect sizes](pages/Day1.html)  
[Day 2: Hierarchical meta-analytical models](pages/Day2.html)  
[Day 3: Assumptions and biases](pages/Day3.html)  
[Day 4: Confounding effects and extra tricks](pages/Day4.html)  

### Additional resources

General reference for how to implement meta-analysis in R: [metafor's website](http://www.metafor-project.org/doku.php) 

New R packages for extracting summary data from figures
[digitize](https://github.com/tpoisot/digitize/)

ImageJ: open-source software for extracting summary data from figures
[ImageJ](https://imagej.net/Welcome)






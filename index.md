---
layout: page
title: Exercises for 'Meta-analysis in biological and environmental sciences'

---


### Before our course  

1) Install [R](https://cran.r-project.org/) and [RStudio](https://www.rstudio.com/products/rstudio/download/).  
2) Install the following packages:

```
install.packages(c("metafor","compute.es","ggplot2","dplyr","reshape2","broom","tidyr"),quietly=TRUE)
```
3) If you already have R installed, please update it to the latest version:  

```

install.packages('installr')

updateR()

```

4) Update your packages to the latest version as well:  

```
update.packages()
```

### Course schedule & exercises  

Throughout this course we will use data from [NCEAS](https://www.nceas.ucsb.edu/meta/publications.html#d_t_t)  
You can download the data directly or download using the R code included in the exercises.  

[Day 1: Calculating effect sizes](pages/Day1.html)  
[Day 2: Hierarchical meta-analytical models](pages/Day2.html)  
[Day 3: Assumptions, biases and confounding effects](pages/Day3.html)  
[Day 4: Methodological issues, advances, and common mistakes](pages/Day4.html)  

### Additional resources

General reference for how to implement meta-analysis in R: [metafor's website](http://www.metafor-project.org/doku.php) & [general overview of 'metafor'](http://www.jstatsoft.org/v36/i03/)  

New R packages for extracting summary data from figures
[digitize](https://github.com/tpoisot/digitize/)

ImageJ: open-source software for extracting summary data from figures
[ImageJ](https://imagej.net/Welcome)






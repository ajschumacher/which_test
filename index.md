## Which statistical analysis should I use?
## Statistical analyses using R

### Notes

This page is based (heavily) on [UCLA IDRE](http://www.ats.ucla.edu/)'s excellent [What statistical analysis should I use?](http://www.ats.ucla.edu/stat/sas/whatstat/default.htm) content, which is itself an extension of Leeper's [Choosing the Correct Statistic](http://bama.ua.edu/~jleeper/627/choosestat.html). UCLA presents thorough examples for SAS, Stata, and SPSS. The goal here is to provide equivalent examples in R.


### Introduction

This page shows how to perform a number of statistical tests using R. Each section gives a brief description of the aim of the statistical test, when it is used, and an example showing R code and R output, with a brief interpretation of the output. You can see the page [Choosing the Correct Statistical Test](http://www.ats.ucla.edu/stat/mult_pkg/whatstat/choosestat.html) for a table that shows an overview of when each test is appropriate to use. In deciding which test is appropriate to use, it is important to consider the type of variables that you have, i.e., whether your variables are categorical, ordinal or interval and whether they are normally distributed. See [What is the difference between categorical, ordinal and interval variables?](http://www.ats.ucla.edu/stat/mult_pkg/whatstat/nominal_ordinal_interval.htm) for more information on this.

Please note that the information on this page is intended only as a very brief introduction to each analysis. This page may be a useful guide to suggest which statistical techniques you should further investigate as part of the analysis of your data. This page does not include necessary and important information on many topics, such as the assumptions of the statistical techniques, under what conditions the results may be questionable, etc. Such information may be obtained from a statistics text or journal article. Also, the interpretation of the results given on this page is very minimal and should not be used as a guide for writing about the results. Rather, the intent is to orient you to a few key points. For many analyses, potentially important information is not presented here.


### Example

Code and output will look like this:


```r
summary(cars)
```

```
##      speed           dist    
##  Min.   : 4.0   Min.   :  2  
##  1st Qu.:12.0   1st Qu.: 26  
##  Median :15.0   Median : 36  
##  Mean   :15.4   Mean   : 43  
##  3rd Qu.:19.0   3rd Qu.: 56  
##  Max.   :25.0   Max.   :120
```


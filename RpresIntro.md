An intro to Rpresentation
========================================================
author: Yanfei Kang
date: 1 May
transition: linear

Section 1
========================================================


For more details on authoring R presentations click the
**Help** button on the toolbar.

- Bullet 1
- Bullet 2
- Bullet 3

Section 2: Slide With Code
========================================================



```r
summary(cars)
```

```
     speed           dist       
 Min.   : 4.0   Min.   :  2.00  
 1st Qu.:12.0   1st Qu.: 26.00  
 Median :15.0   Median : 36.00  
 Mean   :15.4   Mean   : 42.98  
 3rd Qu.:19.0   3rd Qu.: 56.00  
 Max.   :25.0   Max.   :120.00  
```

Slide With inline Code
========================================================
type: subsection

`forecast()`

Section 3: Slide With Plot
========================================================



```r
plot(cars)
```

<img src="RpresIntro-figure/unnamed-chunk-2-1.png" title="plot of chunk unnamed-chunk-2" alt="plot of chunk unnamed-chunk-2" style="display: block; margin: auto;" />

Section 4: Slide With Two column
========================================================

Column1
***
column2


Alert
========================================================
type: alert

Conclusion
========================================================
incremental: true

- easier and more flexible
- visible within Rstudio
- standalone HTML file
- another option of Rpres: **R** package **slidify**

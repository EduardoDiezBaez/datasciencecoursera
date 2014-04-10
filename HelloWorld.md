---
title: "HelloWorld.md"
author: "Eduardo Díez"
date: "Thursday, April 10, 2014"
output: 
  pdf_document:
    keep_tex: yes
---

## This is a markdown file


![plot of HelloWorld](figures/myOutput.pdf) 

```
## 
## Call:
## lm(formula = dist ~ speed, data = cars)
## 
## Residuals:
##    Min     1Q Median     3Q    Max 
## -29.07  -9.53  -2.27   9.21  43.20 
## 
## Coefficients:
##             Estimate Std. Error t value Pr(>|t|)    
## (Intercept)  -17.579      6.758   -2.60    0.012 *  
## speed          3.932      0.416    9.46  1.5e-12 ***
## ---
## Signif. codes:  0 '***' 0.001 '**' 0.01 '*' 0.05 '.' 0.1 ' ' 1
## 
## Residual standard error: 15.4 on 48 degrees of freedom
## Multiple R-squared:  0.651,  Adjusted R-squared:  0.644 
## F-statistic: 89.6 on 1 and 48 DF,  p-value: 1.49e-12
```


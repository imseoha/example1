# example1
airquality data로 Ozone을 Wind로 선형회귀한 모형
---
title: "Airquality Linear Regression"
output: html_document
---
# Summary

```{r,echo "# example1" >> README.md} 

model<-lm(airquality$Ozone~airquality$Wind)
summary(model)

```
## Including Plots
```{r,echo=FALSE}

plot(airquality$Wind,airquality$Ozone)
abline(model)
```


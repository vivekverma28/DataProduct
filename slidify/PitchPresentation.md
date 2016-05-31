Course Project: Shiny Application and Reproducible Pitch
========================================================
author: Vivek Verma
date: May,2016

Course Project
========================================================

- This is the final presentation for the Course Project
- The course is focused on Developing Data Products
- The main objective of the project is to write a Shiny application

Shiny Application
========================================================

- In this project a Shiny Application was written
- The objective of the application was to calculate the BMI of a person
- The motivation of the writing the application was a recent visit to the doctor, and he calculated the the BMI as a normal procedure.

In this slide we show how to include R code embedded in the slide
========================================================
- The following code calculates the Body Mass Index
- The parameters used are height and weight


```r
height <- 180
weight <- 110
BMI <- 110 / (180/100 * 180/100)

BMI
```

```
[1] 33.95062
```

The application
=======================================================
- The application can be found in the following link
  https://vivekverma28.shinyapps.io/DataProduct/

- The source code is hosted in the following link
  https://github.com/vivekverma28/DataProduct.git/

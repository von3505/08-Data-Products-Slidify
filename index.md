---
title       : Measurement Convertor
subtitle    : Coursera Developing Data Products
author      : Von
job         : 
framework   : io2012        # {io2012, html5slides, shower, dzslides, ...}
highlighter : highlight.js  # {highlight.js, prettify, highlight}
hitheme     : tomorrow      # 
widgets     : []            # {mathjax, quiz, bootstrap}
mode        : selfcontained # {standalone, draft}
knit        : slidify::knit2slides
---

## Objective
<br>
Build an application to demonstrate following skill :
<br>
1. use of various widgets of 'shiny' tool <br>
2. understanding of the process of publishing application in shiny <br>
3. interface with R using embeded R code <br>
  
--- .class #id 

## Introducing the Measurement Convertor! 
<br>
<h3>Speaking to an American? </h3>
<br> This app calculates your measurement from centimetres to inches and from kilograms to pounds based on your inputs.   
<br><br>
<h3>Quick facts:</h3> <br>
1. 1 centimetre roughly equals to 0.39 inch <br>
2. 1 kilogram roughly equals to 2.2 pounds <br>

--- .class #id 

## Code

```r
in_cm <- 1000
in_inches <- in_cm * 0.39
print(in_inches)
```

```
## [1] 390
```

```r
in_kg <- 1000
in_pounds <- in_kg * 2.2
print(in_pounds)
```

```
## [1] 2200
```
--- 

## User Interface : Application - Widgets
<br>
This Measurement Convertor includes 4 widgets:<br>
<b>numericInput</b> - A field to enter numbers for a value in centimetres and another in kilograms <br>
<b>actionButton</b> - The 'Convert Now' button' provides non-reactive reactivity to refresh and convert the given values <br>
<b>Textfield</b> - User inputs are displayed on the right column <br>
<b>TabPanel</b> - A separate documentation tab provides further information about this app <br>
--- .class #id 

## Application - Link and Code
<br>
Try out the application on the RStudio shinyapps.io website: https://von3505.shinyapps.io/Measurement_Convertor_App/
<br>

To see the code for the application, visit github website: https://github.com/von3505/08-Data-Products/tree/master/Measurement_Convertor_App
<br>
<b>Useful files in repo:</b> <br>
server.R <br>
ui.R <br>
To execute the application and see the code in action, use: runApp(displayMode = 'showcase')
--- .class #id 

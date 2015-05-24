---
title       : Measurement_Convertor
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
<h3> Speaking to an American? 
<br> This app calculates your measurement from centimetres to inches and from kilograms to pounds based on your inputs.   
<br><br>
Quick facts: <br>
1 kilogram roughly equals to 2.2 pounds <br>
1 centimetre roughly equals to 0.39 inch <br>
--- .class #id 


## User Interface : Application - Widgets
<br>
This Measurement Convertor includes 4 widgets:<br>
numericInput - A field to enter numbers for a value in centimetres and another in kilograms <br>
actionButton - The 'Convert Now' button' provides non-reactive reactivity to refresh and convert the given values <br>
Textfield - User inputs are displayed on the right column <br>
TabPanel - A separate documentation tab provides further information about this app <br>
--- .class #id 

## Application - Link and Code
<br>
Try out the application on the RStudio shinyapps.io website: placeholder
<br>

To see the code for the application, visit github website: https://github.com/von3505/08-Data-Products/tree/master/Measurement_Convertor_App

<br>
Useful files in repo: <br>
server.R <br>
ui.R <br>
To execute the application and see the code in action, use: runApp(displayMode = 'showcase')
--- .class #id 

---
title       : First Names Tell Us A Lot
subtitle    : 
author      : Steph Carew
job         : 
framework   : revealjs       # {io2012, html5slides, shower, dzslides, ...}
highlighter : highlight.js  # {highlight.js, prettify, highlight}
hitheme     : tomorrow      # 
widgets     : []            # {mathjax, quiz, bootstrap}
mode        : selfcontained # {standalone, draft}
knit        : slidify::knit2slides
---


## What's in a name?

<span style="font-size:1em;">
Most first names tend not to stand the test of time. Combining a person's name with knowledge of how long a person typically lives gives us enough information to compute the distribution of how old a person is based on their first name.</span>  
  
    
*Check out the Shiny app* [here](https://sc1463.shinyapps.io/names_likelihood) 

---
## Why do we care?
This could be useful for any type of service that uses a recommendation algorithm to target customers that have given their name. For example, if you sign up for Netflix, it could use knowledge of the distribution of your age to provide better recommendations.

---
## what does the app do?
<img src="app_screenshot.png"  width="600" height="300" />   
Takes in a name and outputs the number born and expected number still living over time. Check out the live version [here](https://sc1463.shinyapps.io/names_likelihood) and the source code [here](https://github.com/stephcarew/names)

---
## It's also pretty fun
Let's try the name **Whitney**  
![plot of chunk slidify](assets/fig/slidify-1.png) 
  
<img src="http://upload.wikimedia.org/wikipedia/commons/a/a7/Whitney_Houston_Welcome_Home_Heroes_1_cropped.jpg" alt="HTMLQuick.com logo" width="88" height="88" />  
*Think she had an effect?*

---
## References
* The data for the number of births per year in the US came from the [Social Security Website](http://www.ssa.gov/OACT/babynames/limits.html)
* The data for survival probability came from the [Centers for Disease Control and Prevention](http://www.cdc.gov/nchs/data/nvsr/nvsr63/nvsr63_07.pdf)


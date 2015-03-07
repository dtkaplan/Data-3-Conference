## Getting Started with R

A brief introduction to R for computer professionals who need to wrangle and present data.

[Link to slides](http://htmlpreview.github.com/?https://raw.githubusercontent.com/dtkaplan/Data-3-Conference/master/Intro-to-R-slides.html)

[link to interactive map at slide 29](https://dtkaplan.shinyapps.io/2015-03-07-Data3/Intro-to-R-slides.Rmd#29)

*Please note*: On slide 19 there is a command
```
BikesRaw <- read.csv("BikeShare/2014-Q4-Trips-History-Data.csv")
```
The `.csv` file is too large to put in this repository.  If you are recompiling the slides in RStudio, you will see that the Rmd document contains the actual line to use:
```
load("BikeShare/2014-Q4-Trips-History-Data.rda")
```
This will create the `Bikes` data frame.

Presented at Data^3 2015, Minneapolis, MN on March 7, 2015

## The Ten Starting Steps

### Preliminaries

-  1: Start with documents
-  2: Simple R chunks within documents
-  3: Atomic types 
-  4: Assignment & naming (trivial)
-  5: Vectors
-  6: Packages

### Data Science

-  7: Data frames
-  8: Wrangling
-  9: Graphics
- 10: Programming constructs

### At this point ...

You don't know everything about R, but enough to read other people's examples and documentation in `dplyr` and `ggplot2`, and modify the examples to your own purpose.

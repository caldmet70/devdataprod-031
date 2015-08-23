# Developing Data Products (devdataprod-031)
This is the README file for the course project of the 'Developing Data Products.' Here the data used is a data set on 48 diamond rings containing price in Singapore dollars and size of diamond in carats. This data comes from a collection of the Journal of Statistics Education. The accompanying documentation says:
“Data presented in a newspaper advertisement suggest the use of simple linear regression to relate the prices of diamond rings to the weights of their diamond stones. The intercept of the resulting regression line is negative and significantly different from zero. This finding raises questions about an assumed pricing mechanism and motivates consideration of remedial actions.”

Please read the instructions to get the complete and clear overview of the project and related materials.

##Instructions
Instructions to run the app locally on your PC or Mac in R/RStudio.

* Change to the directory with these files
* Check the dependencies to see if you are missing any package
* install.packages("shiny")
* install.packages('devtools')
* devtools::install_github('rstudio/shinyapps')
* install.packages('ggplot2') and load the necessary libraries
* library(shiny)
* library(devtools)
* library(ggplot2)
* library(shinyapps)
* runApp()

Source
Data set information is available at http://www.amstat.org/publications/jse/datasets/diamond.txt. Data set is contributed by Singfat Chu.

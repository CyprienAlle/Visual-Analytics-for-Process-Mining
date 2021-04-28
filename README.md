# Visual Analytics for Process Mining
***

## General Info
***
This repository contains the code for the solution developed for my master thesis, which focuses on visual analytics for process mining. The solution produced is a dashboard for analyzing event logs. More specifically, it is centered around the analysis of social interactions. It was created using R and several packages listed below. 

## Prerequisites
***
First, to run this solution, R and RStudio (or another IDE) must be installed. Information on how to install them is available, respectively, on https://cran.rstudio.com/ and www.rstudio.com.

## Installation
***
As mentioned above, several packages are used to build this solution, and thus they need to be installed. They can be installed using the install.packages() function as seen below. 
```
install.packages(c("bupaR","heuristicsmineR","DiagrammeR","flexdashboard","shiny","DT","tibble"))
```

## Runing the code
***
To run this solution, the entire "Master Thesis - Sepsis Analysis Dashboard.Rmd" file should be run. Note that no activities are selected by default on startup to let the solution open faster. The visualizations are, thus, empty until activities are selected. 

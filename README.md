# Instructions for installing and running this app locally

### Install R and the shiny package

1. Download the R programming software [here](https://www.r-project.org/).
2. Download the R Studio software [here](https://www.rstudio.com/products/rstudio/download/). The Open Source (free) option is sufficient. This provides a useful interface for R programming.
3. Open R Studio, and install the Shiny package by typing in the following code into your console:
```
install.packages("shiny")
```

### Directly run the KSEA App

1. Within the R Studio console, type in the following code:
```
shiny::runGitHub('Test', 'casecpb')
```
The KSEA App should automatically launch locally on your computer. <br>
Please read the User Manual for instructions on how to navigate through the app.

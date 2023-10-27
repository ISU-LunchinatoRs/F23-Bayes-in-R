# LunchinatoRs_Bayes_2023

A repository for a seminar during LunchinatoRs about performing Bayesian 
analyses in R. Presentation was given on 2023-10-27. 

## Compile

There are a variety of ways to 
[compile a quarto (qmd) document](https://quarto.org/docs/computations/r.html). 
Here is an R based approach:

    install.packages("quarto")
    quarto::quarto_render("JaradNiemi_LunchinatoRs_Bayes_2023.qmd")
    
This will produce an HTML file that can be viewed in the browser. 

## Extract R code

If you are interested in running the code, you can extract it using

    install.packages("knitr")
    knitr::knit("JaradNiemi_LunchinatoRs_Bayes_2023.qmd", tangle=TRUE)
    
This will produce an R file that be run interactively (or sourced).

## Original repository

The original repository can be found on 
[Jarad Niemi's GitHub account](https://github.com/jarad/LunchinatoRs_Bayes_2023).

## Description 
This repository contains a simple Shiny-app written in R that can be used to visualize metadata about data-publications for Swedish Universities. Data is fetched from: https://raw.githubusercontent.com/snd-sweden/research-output-aggregator-output/refs/heads/main/combined-outputs.csv or the script can use a local copy of the data as well.
The shiny-app is written as a single Quarto-document with ui and server contexts as separate code-chunks. 

## Usage
To use the script, clone a local copy and run it using R and Rstudio. Required packages are listed in the renv.lock -file and can be loaded and installed using 'renv::restore()'[https://rstudio.github.io/renv/reference/restore.html]

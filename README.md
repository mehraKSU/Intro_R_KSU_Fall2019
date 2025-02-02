# IntroR_Workshop
<!--
---
title: "R for Agricultural Scientists"
---
-->


An introduction to R for agricultural scientists written by Dr. Sydney E. Everhart, Nikita Gambhir, Dr. Lucky Mehra, and Dr. Zhian N. Kamvar. At Kansas State Unversity, the workshop will be taught by Dr. Lucky Mehra, Emily Delorean, Dylan Mangel, and Nar Ranabhat.

This repository is intended to serve as an additional resource for the 
workshop given at Kansas State Univeristy. The source code can be found at https://github.com/mehraKSU/Intro_R_KSU_Fall2019.

## About 

This introduction to R is designed to be a companion to a workshop lasting 6 
hours introducing agricultural scientists to the basics of R by using a field data example. 

## Goals

As a result of taking this workshop you should be able to:

 - find, download, and load necessary packages for analysis
 - load tabular data into R
 - understand the basics of data manipulation in R
 - know what a data frame, vector, and function are
 - summarize data
 - visualize data
 - troubleshoot commmon problems


## Website

This website is meant to serve as a companion to the workshop. The pages located
in the **Workshop** tab are rendered versions of R scripts located in the top 
level of https://github.com/mehraKSU/Intro_R_KSU_Fall2019. As the workshop is designed to
be interactive where the participants are given some control over what direction
we should take the analyses, the scripts here are only to serve as guidelines.

These scripts follow these conventions:

 - R code is presented how it would appear in the R console with the first line
   prefixed with `>` and subsequent lines prefixed with `+`. The intent is to
   encourage the user to type the commands instead of copy and paste.
 - There will be instances where we will have exercise questions. These are
   points in the workshop where we stop the participants and ask them to 
   figure out the working of a function or find a suitable function to answer
   the illustrated problem.



The website located at  https://mehraksu.github.io/Intro_R_KSU_Fall2019/ can be build via the
`make` program:

```make
make clean # run this to build the site from scratch
make
```
You can also go to *Environment, History,....* pane in RStudio, click *Build* > *More* > *Clean and Rebuild* to make the website from scratch.

Note: if the README.md is changed, make will force-update the index.Rmd and in
turn force update the corresponding HTML.

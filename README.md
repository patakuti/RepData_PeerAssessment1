## Abstract

This repository is for Course Project1 of Coursera's **Reproducible
Research** class.
This includes these files.
* **PA1_template.Rmd**  
    R markdown document that includes my report for this assignment.
    This file is hand written.
* **PA1_template.html**  
    HTML document that includes my report for this assignment.
    This file is transformed from above Rmd file by knitr.
* **PA1_template.md**  
    Markdown document that includes my report for this assignment.
    This file is an intermediate file transformed from above Rmd file
    by knitr.
* **activity.zip**  
    A zipped dataset of activity monitoring data, which is used in
    this assignment.
    This data is downloaded from
    https://d396qusza40orc.cloudfront.net/exdata%2Fdata%2FNEI_data.zip

## Dataset

Description for dataset used for this assignment.

The dataset file "activity.csv" can be got by unzipping activity.zip.
The dataset has these variables.
<ol>
<li><b>steps</b>: Number of steps taking in a 5-minute interval (missing
values are coded as NA)</li>
<li><b>date</b>: The date on which the measurement was taken in
YYYY-MM-DD format</li>
<li><b>interval</b>: Identifier for the 5-minute interval in which
measurement was taken</li>
</ol>

## Make a HTML report file from R markdown document

R markdown document includes texts and R codes but not results of
calculation and figures.
We should make a HTML report file by knitr to obtain a document
includes also results of calculation and figures.
This is a command line to obtain HTML report file.

    library(knitr)
    knit2html("PA1_template.Rmd")

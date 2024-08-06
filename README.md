## About

This is an vignette for users who have never used R or RStudio before. The tutorial explains how to install R and RStudio and to learn the basics of the R programming language. You can install R on your computer by going to <https://cran.r-project.org/> and selecting the R version that is appropriate for your operating system. After installing R, you will then need to install [RStudio Desktop](https://posit.co/download/rstudio-desktop/). This vignette was born out of the **R**esearch **I**nnovations using **S**ensor Technology in **E**nvironmental Justice Communities (**RISE Communities**) program, which provides technical training in the application of low-cost sensors for indoor, outdoor, and personal air monitoring in Environmental Justice communities. The GitHub page for the [PurpleAir vignette](https://github.com/geomarker-io/purple_air_data_in_R/tree/main#readme) is part of the RISE program hosted at Cincinnati Children's Hospital Medical Center August 7-9, 2024.

## Goals
The milestones covered in this vignette include the essentials for becoming familar with using R:

-   Install R and RStudio on your computer.
-   Opening and using RStudio, becoming familiar with its environment.
-   Setting and changing the working directory.
-   Understanding different kinds of files R can use, such as R scripts (`.R`), R Markdown (`.RMD`), and Quarto (`.QMD`).
-   The basics of R programming, including typing code, executing code, and exploring its output.
-   Understand how basic R functions work.
-   Saving and loading data files into the R session.
-   Sourcing R scripts.
-   Installing and using R packages.

## Prerequisites

-   A computer running either Windows, Mac, or Linux operating systems.
-   A stable internet connection.

It is assumed the user has no prior experience with other programming languages. Only essential code is provided in the vignette. Detailed descriptions are included for all the code blocks to explain each process. Additional code and examples are provided in the `purpleair.R` file for you to try as exercises. 

## Getting Started

Click [here](https://colegasn.github.io/Rintro/) to access the vignette, or click the URL link under the **About** section on the GitHub page. This should open an HTML document of the vignette.

It is highly recommended that you follow along with the HTML vignette by setting up and running the R code provided on your computer to get the most out of this tutorial. For your convenience, we have taken the R code listed in the HTML document and saved it in an R script `purpleair.R`. You can file this file listed at the top of the GitHub page.

Download the following files from our GitHub page:

-   [`new_pas.R`](https://github.com/colegasn/Rintro/blob/main/new_pas.R)

-   [`new_pat.R`](https://github.com/colegasn/Rintro/blob/main/new_pat.R)

To download a file, click on the file name to preview the file within GitHub. In the top-right corner of the preview page, click on the icon that says **Download raw file**. Make sure that you download the raw `.R` files and not the HTML versions. Use the left-side panel to then open the next file to download. Repeat this process until all the files are downloaded.

Save all the files into one (preferrably new) folder. Remember the location of this folder, since you will need to reference its file path later in the tutorial. After you install both R and RStudio, clicking on any of these `.R` files should open RStudio and set your current working directory to the folder where these files are located. Make sure that the current working directory points to the folder containing these `.R` files. You can use the R package `here` to set up the correct working directory so that files are loaded and saved in the correct location on your computer. See the vignette for additional details.

## Additional Links

Learn more about R through the following links:

- [The R Project Website](https://www.r-project.org/)
- [The R Cheatsheat](https://cran.r-project.org/doc/contrib/Short-refcard.pdf)
- [What is R?](https://www.r-project.org/about.html)
- [What is R Coding Language and Why is it so Important?](https://emeritus.org/blog/coding-r-coding-language/)
- [Datacamp: What is R?](https://www.datacamp.com/blog/all-about-r)
- [Quick-R Homepage](https://www.statmethods.net/)
- [R for Data Science Textbook: 2nd Edition](https://r4ds.hadley.nz/)

Learn more about RStudio through the following links:

- [posit Homepage](https://posit.co/)
- [What is R and RStudio?](https://libguides.library.kent.edu/statconsulting/r)
- [R Packages Cheatsheat on posit](https://rstudio.github.io/cheatsheets/contributed-cheatsheets.html?_gl=1*9kp033*_ga*MTgzNzIwNjUwNS4xNjgyNDU0NTc2*_ga_2C0WZ1JHG0*MTY5MDMzMjg0Ni4yNS4xLjE2OTAzMzI5NzYuMC4wLjA.)
- [Beginner's Guide to RStudio](https://careerfoundry.com/en/blog/data-analytics/what-is-rstudio/)

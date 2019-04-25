---
layout: default
---

# R Visualization
## Spring 2019
### University of Washington Tacoma

## Important links

* [Presentation Slides](https://clanfear.github.io/R_Visualization_Workshop/r_visualization_slides.html)
* [.R Script to follow along](https://raw.githubusercontent.com/clanfear/R_Visualization_Workshop/master/r_visualization_script.R) (Save as to download)
* [R and RStudio Installation Instructions](https://clanfear.github.io/CSSS508/docs/installation.html)
* [Enabling compilation of packages](https://clanfear.github.io/CSSS508/docs/compiling.html)
* [Panopto Recording of Workshop](https://uw.hosted.panopto.com/Panopto/Pages/Viewer.aspx?id=f271adad-1792-4213-95c3-aa3a013a2c4d)
* [YouTube Recording of Workshop](https://youtu.be/g2jUfESoPm4)

## General R Resources:

   * [UW CSSS508](https://clanfear.github.io/CSSS508/): My University of Washington Introduction to R course which forms the basis for this workshop. All content including lecture videos are freely available.
   * [R for Data Science](http://r4ds.had.co.nz/) online textbook by Garrett Grolemund and Hadley Wickham. One of many good R texts available, but importantly it is free and focuses on the [`tidyverse`](http://tidyverse.org/) collection of R packages which are the modern standard for data manipulation and visualization in R.
   * [Advanced R](http://adv-r.had.co.nz/) online textbook by Hadley Wickham. A great source for more in-depth and advanced R programming.
   * [DataCamp](https://www.datacamp.com/): A source for interactive R tutorials (some free of charge).
   * [`swirl`](http://swirlstats.com/students.html): Interactive tutorials inside R.
   * [Useful RStudio cheatsheets](https://www.rstudio.com/resources/cheatsheets/) on R Markdown, RStudio shortcuts, etc.
   * [Code style guide](http://adv-r.had.co.nz/Style.html) for writing functions, etc.
   * [Good Enough Practices in Scientific Computing](https://journals.plos.org/ploscompbiol/article?id=10.1371/journal.pcbi.1005510): From abstract, "This paper presents a set of good computing practices that every researcher can adopt, regardless of their current level of computational skill."  

## Plotting

   * Base R graphics
      + [Shapes and line types](http://www.cookbook-r.com/Graphs/Shapes_and_line_types/) in base R
      + [Color names (PDF)](http://www.stat.columbia.edu/~tzheng/files/Rcolor.pdf) in base R
   * `ggplot2`
      + [`ggplot2` documentation](http://docs.ggplot2.org/current/)
      + [`ggplot2` Cheat Sheet](https://github.com/rstudio/cheatsheets/raw/master/data-visualization-2.1.pdf)
   * [Data Visualization: A Practical Introduction](http://socviz.co/) by Kieran Healy
   * [Visualization chapter in R for Data Science](http://r4ds.had.co.nz/data-visualisation.html)
   * [Cookbook for R graph reference](http://www.cookbook-r.com/Graphs/)

## Data Manipulation

   * [Data Transformation chapter in R for Data Science](http://r4ds.had.co.nz/transform.html)
   * `dplyr`:
       + [`dplyr` cheatsheets](http://www.rstudio.com/wp-content/uploads/2015/02/data-wrangling-cheatsheet.pdf) with diagrams to help you remember functions
       + [Introduction to `dplyr`](https://cran.rstudio.com/web/packages/dplyr/vignettes/introduction.html)
       + [Window functions in `dplyr`](https://cran.r-project.org/web/packages/dplyr/vignettes/window-functions.html)
       + [Joining data in `dplyr`](https://cran.rstudio.com/web/packages/dplyr/vignettes/two-table.html)
       + More advanced joins: [`sqldf` for easy SQL in R](https://cran.r-project.org/web/packages/sqldf/index.html)
   * [Data Structures chapter in Advanced R](http://adv-r.had.co.nz/Data-structures.html)
   * Tidying:
       + [`tidyr` vignette](https://cran.r-project.org/web/packages/tidyr/vignettes/tidy-data.html)
       + [Tidy genomics](http://varianceexplained.org/r/tidy-genomics/) (a walkthough of tidy data preparation and analysis)
   * Dates and times:
       + [`lubridate` vignette](https://cran.r-project.org/web/packages/lubridate/vignettes/lubridate.html)
   * Factors:
       + [Lots on factors from Jenny Bryan](http://stat545-ubc.github.io/block014_factors.html)
   * Strings
       + [`stringr` vignette](https://cran.r-project.org/web/packages/stringr/vignettes/stringr.html)
       + [Blog post explaining `paste()`](https://trinkerrstuff.wordpress.com/2013/09/15/paste-paste0-and-sprintf-2) for combining strings
       + [Site for regular expression testing](http://regexr.com/)  with a good cheatsheet and hover explanations
       
## Importing and Exporting Data
   * Data import and export:
       + [`readr` documentation](https://cran.r-project.org/web/packages/readr/readr.pdf)
       + [Column types in readr](https://cran.r-project.org/web/packages/readr/vignettes/column-types.html)
       + [Using `dput()` when asking for help](http://stackoverflow.com/questions/5963269/how-to-make-a-great-r-reproducible-example)
       + [`readxl`](https://github.com/hadley/readxl) and [`openxlsx`](https://cran.r-project.org/web/packages/openxlsx/vignettes/Introduction.pdf) packages for Excel
 
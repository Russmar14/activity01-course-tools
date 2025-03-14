R Basics
================

`{global-options, include=FALSE} knitr::opts_chunk$set(echo = TRUE)`

## Introduction

This will likely be the only `.Rmd` file that I provide to you as all
other activities will have you follow directions in the day-specific
folder’s `README` and type your own “report” in an Rmarkdown document
that you create. Note that when I type in Rmarkdown files, each sentence
begins on its own line. This helps me to quickly find errors and correct
them, but you do not need to use this method.

If I want to start a new paragraph, I simply press Enter/Return twice to
create a new “block”. Below is an R code chunk named
“simple-calculations”. When I am working in Rmarkdown documents, I make
sure that every code chunk has a descriptive title. This is a suggestion
that I strongly recommend that you follow. We will see how naming code
chunks makes our life easier later in this document so be sure to stick
around.

In the code chunk named “simple-calculations” below, add the R code that
does the following items. I also encourage you to use comments (`#`) to
help you identify each item (I provide an example for item 1).

1.  Adds the values 2 and 5.
2.  Creates an R object called `int_vect` that contains the values 1
    through 9. Can you do this without typing each number?.
3.  Creates an R objected called `char_vect` that contains the letters
    “A” (the first letter of the alphabet) through “Q” (the 17th letter
    of the alphabet). Can you do this without typing each letter?
4.  Using code, determine how many of the items in `char_vect` occur
    after the letter “D”
5.  Provides a descriptive comment for each of the above tasks.
6.  Run each line to verify that you get the results you would expect,
    then click on the **knit**
    <img src="../README-img/knit-icon.png" alt="knit" width = "20"/>
    icon your Rmd document to verify that no errors occur. If you use
    [keyboard
    shortcuts](https://support.posit.co/hc/en-us/articles/200711853-Keyboard-Shortcuts-in-the-RStudio-IDE),
    like me, you can instead press Ctrl + Shift + K (for mac users:
    Cmd + Shift + K).
7.  Return to the **Day 1** `README` file to finish the process of
    committing and pushing to GitHub.

``` r
# Item 1 - adding 2 and 5 with addition operator
2 + 5
```

    ## [1] 7

``` r
# item 2 - seq() creates a sequence of values between your from and to values
int_vect <- seq(1,9) # 
#item 3 - LETTERS is a constant, string index for specific subset of letters A - Q
char_vect <- LETTERS[1:17]
# item 4
length(which(char_vect > 'D')) # length is like len() in python, which() returns T/F for each index of list object
```

    ## [1] 13

``` r
# item 5
#done with activity 1
```

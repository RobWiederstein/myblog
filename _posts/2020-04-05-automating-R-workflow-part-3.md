---
layout: single
title: Automating R Workflow--Part 3
date: '2020-04-25 19:53:27 -0500'
categories: R
---

![tree](/assets/img/post/20200405.png)

1. Intro

In the previous post, we learned how to use a shell script to trigger the execution of R scripts. The subject of part III is how to have your computer run those scripts at a particular time. A number of methods are available like Crontab, launchd, and the Mac automator--if you are on Mac. After a half dozen unsuccessful attempts, I ended up discovering the cronR package on CRAN and then figuring out that it is an "add-in" in the Studio environment. There is also a development version on GitHub too. This video was the entry point to the topic. The `cronR` package worked really well and I'm going to take you through the steps of getting it setup in the above shell example.

1. Load Dependencies

```r

## load suggested packages per
## https://cran.r-project.org/web/packages/cronR/index.html
cronR_with_suggested_pkgs <- c("cronR",
"knitr", "miniUI", "shinyFiles", "testthat")
#download pkgs
sapply(cronR_with_suggested_pkgs, install.packages)
#install pkgs
sapply(cronR_with_suggested_pkgs, require, character.only = T)
```

1. Find "Addins" Tab in Rstudio

![cronR add ins](/assets/img/post/rstudio_cron_addin.jpg)

1. Schedule Cron Job

![schedule cron job](/assets/img/post/cron_rstudio_dialog_box.jpg)

1. Check Log File for Success

2. Conclusion

This was by far the easiest effort to implement a time-based execution of R code, at least for me. One nice aspect of it was the execution was to occur each minute. In the interval, I would change the code in the different files to see how it would affect the cron log. It was just like working on a website and seeing the changes occur in the server window. One thing that needs to be emphasized is pay special attention to the file paths in your scripts. In R, the project directory is the default when dealing with files. With cron, it's usually the home directory ("$HOME") or the root directory. There's lots of different ideas on how to do this so feel free to experiment.

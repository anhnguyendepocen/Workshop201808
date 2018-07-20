# Intro to R and RStudio
## August 2018 Workshop
### Sharon Machlis

This repo includes R scripts and data for an R hands-on workshop I'm giving at a newsroom in New York.


1. Download R from [https://cran.rstudio.com/](https://cran.rstudio.com/), choosing the binary distribution for your operating system. Install it as you would any other software program.

2. Download the free, open-source version of RStudio Desktop (not server) from the [RStudio website](https://www.rstudio.com/products/rstudio/download/). Install it as you would any other software program.

3. Open RStudio. Type the following line of code in the bottom left panel at the `>` prompt (it may just be one large panel at the left instead of a top and bottom):

```
install.packages("pacman")
```

and hit return or enter. This installs an external R library called pacman that's useful for installing _other_ packages.

4. When that finishes, type the following line of code at the `>` prompt:

```
install.packages("usethis")
```

and hit return or enter. As you might have guessed, that installs an external R library called usethis.

5. When _that_ finishes, type (or cut and paste) this code at the `>` prompt:

```
usethis::use_course("https://github.com/smach/Workshop201808/archive/master.zip")
```
This should download all the session files to your system, and create a new project for them within RStudio. You'll be asked if you want to proceed with the download (choose yes) and whether you want to subsequently delete the zip file after it's unzipped (you probably do).

RStudio should now open in the directory containing your new project files. If it hasn't, find the IntroToR.Rproj file and click to open that.

6. At the `>` prompt in your lower left pane, type:

```
source("config.R")
```

and hit return or enter. That should load all the other R packages you need for the session.

We'll be using the script files in the following order:

* intro.R
* primary_analysis.R
* salaries.R






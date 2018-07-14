# Intro to tidyverse Workshop Materials

Materials for Northwestern [Research Computing Services](http://www.it.northwestern.edu/research/) workshop, July 2018. 

# Software and Files

## R and RStudio

This workshop assumes you have recent versions of R and RStudio - R 3.4 or 3.5 and RStudio 1.1.  R and RStudio installation notes are in the [main R workshop repository](https://github.com/nuitrcs/rworkshops) or the [summer workshop page](https://sites.northwestern.edu/summerworkshops/resources/software-installation/).  

If you normally connect to the Northwestern wireless network, then that's all you need to do before the workshop.  This workshop downloads packages and data files from the internet as we work through the material.

If you do not have a NetID, you may have difficulty accessing the wireless network at Northwestern (the Guest network has some limits on it that can possibly cause issues).    

If you won't be able to connect to the Northwestern network on an independent wireless network during the workshop, OR if you don't have administrator privileges on your laptop, you might want to install some packages ahead of time.  

To do so, start R, then run the commands in `packagelist.r`.   If you need assistance, please contact the workshop instructor before the workshop.


### Option 1: On your laptop 

Download all of the materials to your laptop.  See [Downloading from GitHub reference](https://sites.northwestern.edu/summerworkshops/resources/downloading-from-github/).

### Option 2: RStudio Cloud

Go to https://rstudio.cloud and log in (or create an account if needed).  Click on Your Workspace in the left Menu.  Then make sure you are on the Projects tab, and click the blue button for New Project.  Choose the option of creating one from a GitHub repo.  The repo address is https://github.com/cskovron/tidyverse-workshop.  This will take a few moments to copy files from this repository.  You'll then need to install packages.  Open `packagelist.r` and run the code.  The tidyverse package will take a while to install.  

You can use this space like you would your RStudio on own computer, except you can only access the files that are part of the project and save files within the project.

## Types of Files

The main materials are slides. HTML and PDF versions are available in the slides directory of the repository.

Exercises taken from the R for Data Science text  are either in the slides or in .Rmd files in the [r4dsexercises directory](/r4dsexercises). For solutions to the book exercises, consult [Jeffrey Arnold’s solutions](https://jrnold.github.io/r4ds-exercise-solutions/), some of which I have reproduced as .Rmd files in [/r4dsexercises/solutions](/r4dsexercises/solutions).

Reference materials and independent practice exercises are written in RMarkdown (*.Rmd).  You can open these files directly in RStudio and run the code chunks.  The RMarkdown files have also been converted to html files for easy viewing.  Additional exercise files are taken from RStudio’s “Master the tidyverse” short course. .Rmd files with the excercises are in the [master-tidyverse-exercises directory](/master-tidyverse-exercises) and .Rmd files with solutions to those are in the [solutions subdirectory](/master-tidyverse-exercises/solutions).

### Opening/Downloading Files

RMarkdown files can be previewed in GitHub, but they won't include the output of the code cells.  HTML files generated from the RMarkdown generally can't be previewed directly in the GitHub repository view, but they can be viewed online through GitHub Pages; links are provided for that below.  HTML files are self-contained; this means they are on the large side, but they can be downloaded and viewed locally as a single file.

REMEMBER: if downloading individual files from GitHub, you want to download the RAW version of a file.  Otherwise, it's often better to download everything together by using the green clone/download button for the entire repository.  [Downloading from GitHub reference](https://sites.northwestern.edu/summerworkshops/resources/downloading-from-github/).


# Other Resources

An extensive list of good R resources can be found in the [main R workshop repository](https://github.com/nuitrcs/rworkshops).


# Acknowledgements

Materials in this workshop have been lifted in large part from [R for Data Science](http://r4ds.had.co.nz/). I also rely on Christina Maimone’s Intro to R workshop for the backbone of some of these materials. 
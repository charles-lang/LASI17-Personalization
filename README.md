# Data Exercise

Download "student.record.csv" data from the following [link](https://github.com/bkoester/PLA/tree/master/data)

Familiarize yourself with the variables.

Design a personalization strategy that would use this data, include a narrative, operational and validiation model.


# Advance Preparation Instructions

##Minimum Preparation
As advanced preparation you will be setting up the software and online tools that you will be using throughout the workshop. Below there are links and instructions to relevant sites.

1. The first stop is to create a personal [Github account](https://github.com/join?source=header)
2. Next you will need to install the software we will be using (if you already have them installed make sure they are the latest versions). Links and instructions can be found below for:
   * R
   * RStudio
   * Git

3. Now you can connect your Github account to your RStudio installation. 


# Software

In this workshop we will be using several online services and software packages to set up a learning analytics system. 

### You will need to make accounts and install the following services.

Instructions for setup can be found [here](https://help.github.com/articles/set-up-git/) and [here](https://git-scm.com/book/en/v2/Getting-Started-Installing-Git).

## [Github](https://github.com/join?source=header)

### You will need to install the following software.

## [Git](https://git-scm.com/downloads) 

## [R 3.2.3](https://www.r-project.org/)

## [RStudio 0.99.903](https://www.rstudio.com/)

Connecting Github to RStudio: [The Molecular Ecologist](http://www.molecularecologist.com/2013/11/using-github-with-r-and-rstudio/) and/or [RStudio Help](https://support.rstudio.com/hc/en-us/articles/200532077-Version-Control-with-Git-and-SVN) or 
[these instructions](https://support.rstudio.com/hc/en-us/articles/200532077-Version-Control-with-Git-and-SVN).

Several errors can be corrected by following the instructions located [here](http://happygitwithr.com/troubleshooting.html).

A common error is: 

`error: unable to read askpass response from 'rpostback-askpass'`

The a fix for most systems is:

* In RStudio, click on the "Tools" menu and select "Shell"
* Run the following command: `git push -u origin master` (*it might ask you for your git username and password. Supply this information, make sure it is correct*)
* Close the window
* Now make some more edits to some file so that you have new content to push click on the "push" button in RStudio and this time the push should work

If you are using a Mac and this does not fix your error please try [these instructions](https://github.com/core-methods-in-edm/Assignment1/blob/master/MAc%20Github%20help%20pages.pdf).

# For Those New To R

[Swirl](http://swirlstats.com/) is a little AI teacher to help you get off the ground with R quickly. You will need to install swirl and then follow along through the exercises. 

1. Open RStudio  
2. Install the swirl package (library) by clicking on the "Packages" tab in the lower right hand panel and clicking on "Install"
3. Type "swirl" in the text box and click "Install"
4. Type `library(swirl)` and press enter
5. Follow the prompts and complete the first unit of the program (more if you want though!) 


 








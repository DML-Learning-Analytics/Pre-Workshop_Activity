# DML Learning Analytics Pre-Workshop Activity

## Introduction to the R programming language  

Welcome to the DML 2017 Learning Analytics Workshop 2017! We are excited to meet you all and start learing together. During the workshop we will be using the R programming language. Before you arrive at Irvine we ask that you install the programming language R and its graphical user interface, RStudio. R is free, can perform powerful analysis and create beautiful data representations (check out [here](http://www.r-graph-gallery.com/) and [here](https://learnr.wordpress.com/) for some great examples). Once you have installed R and RStudio we would also like you to complete a short activity in RStudio (<10mins) (The following instructions and activity are designed to get you up and running in R, don't worry too much about the content of the activity).

## Installing R
* Choose a [download mirror site](https://cran.r-project.org/mirrors.html) from the list that is close to you geographically **(Cntrl/Cmd + click to open in new window)** 
* Download the version of R that is appropriate to your operating system
* Install R in a manner appropriate to your operating system ([MacOSX](https://youtu.be/Ywj6yNfc5nM), [PC](https://youtu.be/5ZbjUEg4a1g))
*FYI - If you recieve the message: "the git command requires command line development tools...do you want to install them now?" just cancel, there is no need to download any other components such as Xcode for this tutorial*

## Installing RStudio (Graphical User Interface for R)
* Download the free version of [RStudio](https://www.rstudio.com/products/rstudio/download/)
* Install RStudio in a manner appropriate to your operating system ([MacOSX](https://youtu.be/Ywj6yNfc5nM), [PC](https://youtu.be/5ZbjUEg4a1g))

## Pre-Workshop Activity
* Once you have installed both programs, open RStudio (RStudio will automatically open R at the same time)
* R is modular, we can install mini-programs called packages within it like apps on your phone to do specific tasks, in this activity we will be using the Swirl package. Swirl is a teaching tool for learning R, it comprises questions and answers and a bit of AI (for positive reinforcement)
* Install the Swirl package by typing `install.packages("swirl")` in the console window (located on the left hand side of the RStudio interface). If you get an error message you can also install by clicking the "packages" tab in the right hand pane and then clicking "install".
* Once we have installed the package we need to turn it on, do that by inputing the code `library(swirl)`. After you do that Swirl will tell you to type `swirl()` **but don't do that just yet!**
* First we need to load a lesson into Swirl, to do this cut and paste the following code into the console window (you will need to be connected to the internet):  
`install_course_github("DML-Learning-Analytics", "Pre-Workshop_Activity")`
* Once the lesson finishes installing (When the R promopt displays the ">" symbol) type `swirl()`, Swirl will then guide you through setting up a user Id (please use your full name so we can identify you later). Choose the `Pre-Workshop Activity` course and the `Introduction to R` lesson when you have the option.

  ## Thanks for joing us at the DML 2017 Learning Analytics Workshop!



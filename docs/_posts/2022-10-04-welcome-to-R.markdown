---
layout: post
title:  "Welcome to our first workshop "Using R for scientific reproducible research!"
categories: R workshop

---


Science is a multi-step process: once you’ve designed an experiment and collected data, the real fun begins! This lesson will teach you how to start this process using R and RStudio. We will begin with raw data, perform exploratory analyses, and learn how to plot results graphically. This example starts with a dataset from gapminder.org containing population information for many countries through time. Can you read the data into R? Can you plot the population for Senegal? Can you calculate the average income for countries on the continent of Asia? By the end of these lessons you will be able to do things like plot the populations for all of these countries in under a minute!

{% highlight ruby %}
`_Before Starting The Workshop`
{% endhighlight %}

When you first open RStudio, you will be greeted by three panels:

1. The interactive R console/Terminal (entire left)
2. Environment/History/Connections (tabbed in upper right)
3. Files/Plots/Packages/Help/Viewer (tabbed in lower right)


<img width="640" alt="01-rstudio" src="https://user-images.githubusercontent.com/65514904/193950969-be4c8a0d-5110-4b3e-917a-f1e1c3ede5e9.png">

Once you open files, such as R scripts, an editor panel will also open in the top left.

<img width="640" alt="01-rstudio-script" src="https://user-images.githubusercontent.com/65514904/193951018-6029a49f-fad8-4290-ab3d-81cd8527e615.png">


Any commands that you write in the R console can be saved into a file to be re-run again. Files containg R code to be ran in this way are called R scripts. R scripts have .R at the end of their names to let you know what they are.


`Workflow within RStudio `

There are two main ways one can work within RStudio:

Test and play within the interactive R console then copy code into a .R file to run later.
This works well when doing small tests and initially starting off.
It quickly becomes laborious
Start writing in a .R file and use RStudio’s short cut keys for the Run command to push the current line, selected lines or modified lines to the interactive R console.
This is a great way to start; all your code is saved for later
You will be able to run the file you create from within RStudio or using R’s `source () ` function.
               
  
<span style="background-color: #914c53; color: #ffffff; padding: 0 3px;">Tip: Running segments of your code
</span></h3>
               

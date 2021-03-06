---
title: "Learn tidytext with my new learnr course"
author: Julia Silge
date: '2021-02-02'
slug: learn-tidytext-learnr
categories:
  - rstats
tags:
  - rstats
subtitle: ''
summary: "I am happy to announce that this free, open source, interactive course on text mining with tidy data principles is now published!"
featured: no
image:
  caption: ''
  focal_point: ''
  preview_only: true
projects: []
---



Today I am happy to announce that a new free, online, open source, interactive tutorial, [**Text Mining with Tidy Data Principles**](https://juliasilge.shinyapps.io/learntidytext/), has been published! :tada:

![](featured.png)

I previously developed an interactive course on text mining for an online learning company, but that course is no longer available. I've been wanting to revisit the ideas behind that course, update them, and make a new tutorial freely available for a long time, much like I did for [my supervised machine learning course](https://juliasilge.com/blog/tidymodels-ml-course/); I recently sat down and got a chance to do just that. 

## Learn tidytext!

Text data sets are diverse and ubiquitous, and **tidy data principles** provide an approach to make text mining easier, more effective, and consistent with tools already in wide use. In this tutorial, you will develop your text mining skills using the [tidytext](https://juliasilge.github.io/tidytext/) package in R, along with other [tidyverse](https://www.tidyverse.org/) tools. You will apply these skills in four case studies, which will allow you to: 

- practice important data handling skills, 
- learn about the ways text analysis can be applied, and 
- extract relevant insights from real-world data.

This tutorial is organized into **four case studies**, each with its own data set:

- transcripts of TED talks
- a collection of comedies and tragedies by Shakespeare
- one month of newspaper headlines (HEADS UP, the particular month is November 2020 :flushed:)
- song lyrics spanning five decades

These case studies demonstrate how you can use text analysis techniques with diverse kinds of text. Much of the data in this tutorial is new, the code is refreshed (a lot of it entirely new), and overall I am really proud of how it has turned out.

## Learning about learnr

For the last interactive course I built, I used the amazing framework created by [Ines Montani](https://ines.io/) based on [Binder](https://mybinder.org). I [reflected a bit last year about the process](https://education.rstudio.com/blog/2020/05/teach-interactive-course/) of building that course and using that framework. This time around, I used [learnr](https://rstudio.github.io/learnr/) instead to put together this tutorial. 

I think that learnr let me develop the tutorial material much faster than other options I've used because I could write in R Markdown, only needing to add a tiny bit more to what I already use in so much of my daily work. Putting the tutorial together felt fluent and natural. You may have seen [Allison Horst's _amazing_ tutorial on missing data](https://allisonhorst.shinyapps.io/missingexplorer/) that uses learnr, and you can tell from seeing my tutorial that I learned a lot from seeing her work. I'd like to also thank my coworker [Alison Hill](https://alison.rbind.io/) for her helpful feedback on the tutorial. :raised_hands:

The deployment and publishing considerations also need to be taken into account. I published my text mining tutorial to [shinyapps.io](https://www.shinyapps.io/) which is a paid service. (I'm an RStudio employee so my situation is not the same as folks outside of RStudio.) I can certainly say that it is very **easy** to publish learnr tutorials to this platform, arguably much easier than learning a little JavaScript, a little Docker, a little Binder, etc! There were a couple of resources I found helpful in checking whether I was going to use a ridiculous amount of computing resources in publishing this tutorial:

- [Scaling and Performance Tuning with shinyapps.io](https://shiny.rstudio.com/articles/scaling-and-tuning.html)
- [Publishing learnr tutorials on shinyapps.io](https://cran.r-project.org/web/packages/learnr/vignettes/shinyapps-publishing.html)
- [Publishing info on learnr's pkgdown site](https://rstudio.github.io/learnr/publishing.html)

## Try it out

If you would like to learn more about text analysis with tidy data principles, [go ahead and give it a whirl](https://juliasilge.shinyapps.io/learntidytext/)! :page_facing_up: Contributions and comments on how to improve this tutorial are welcome. Please [file an issue](https://github.com/juliasilge/learntidytext/issues) or submit a pull request if you find something that could be fixed or improved.

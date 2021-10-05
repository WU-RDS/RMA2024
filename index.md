---
knit: "bookdown::render_book"
title: "Marketing Research Design & Analysis 2021"
bibliography: [book.bib, packages.bib]
biblio-style: apalike
link-citations: yes
description: "An Introduction to Data Analytics Using R"
site: bookdown::bookdown_site
documentclass: book
favicon: "favicon.ico"
css: style.css
classoption:
  - twocolumn
---



# (PART) Course outline {-}


# Welcome! {-}

<p style="text-align:center;">
<img src="https://github.com/IMSMWU/Teaching/raw/master/MRDA2017/Graphics/logo_wu.jpg" alt="logo_wu" height="140"  />&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
<img src="logo_rds.png" alt="logo_rds" height="140"  />
</p>
<br>
Welcome to the course **Marketing Research Design & Analysis**! Due to the limited activity on campus this semester, this course will be delivered using **distance learning**. This means that students are required to familiarize themselves with the contents by means of **self-study**. This website is intended to aid the self-study process by providing you with explanations regarding the relevant concepts and methods in text and video format along with code files and commented outputs that will show you how to implement these methods using the **statistical software R**. The self-learning process will be complemented with weekly **interactive Q&A sessions** via live video streaming (Zoom), which provide ample opportunities to ask questions and clarify points that require further discussion. 
<br><br>
The following pages outline the course schedule and explain how to use this tutorial in detail. If you have any questions, feel free to send me a short email.
<br>
<br>
Nils Wlömert
<br>
[(nils.wloemert@wu.ac.at)](mailto:nils.wloemert@wu.ac.at)


# Introduction {-}

## Course motivation {-}

The following video contains some introductory slides with a motivation for this course.  

<div align="center">
<iframe width="500" height="310" src="https://www.youtube.com/embed/sCXJbKWx-1U" frameborder="0" allowfullscreen></iframe>
</div>

## Course structure {-}

Due to the limited contact on campus this semester, this course combines asynchronous teaching elements (e.g., texts and pre-recorded videos on this website) with synchronous elements (e.g., live video streaming, chats). The syllabus consists of three main parts, as reflected by the structure of this website: 

1. **Lecture notes**: the lecture part will explain the theory behind the concepts and methods and provide you with example applications using the statistical software R
2. **Individual assignments**: in the individual assignments you are asked to apply the acquired knowledge to new data sets
3. **Group project**: in a group you will design and conduct your own market research project and transfer the knowledge to a real business setting

The general approach is that students will first familiarize themselves with the contents by going through the materials on their own. This self-study process is complemented with weekly **interactive Q&A and group coaching sessions** via live video streaming (Zoom), which provide ample opportunities to ask questions and clarify points that require further discussion. The schedule for each of the three parts will be explained below. 

The following video summarizes the information regarding the structure of this course.  

<div align="center">
<iframe width="500" height="310" src="https://www.youtube.com/embed/ujRNrqYTSMg" frameborder="0" allowfullscreen></iframe>
</div>

### Schedule {-}

#### Lecture notes Q&A {-}

The contents on this website are divided into weekly readings. To be able to follow the curriculum and complete the weekly assignments, you need to read the materials assigned for the respective week. The relevant chapters are indicated in the table below. The weekly readings will be complemented with interactive Q&A session, which provide you with an opportunity to ask questions about the assigned readings. Please note that you need to go through the materials on your own in the week following the respective session. For example, chapter 1 will be discussed in the second session. The dates and times for the 90 minute live video sessions are indicated in the table below. It is highly recommended to come with questions or comments about the materials to these sessions that you think might be interesting and helpful to the class. The live sessions will also feature short interactive quizzes that allow you to self-assess your progress and identify knowledge gaps regarding the materials that were assigned for the previous week.     

<br>
<table class=" lightable-paper lightable-hover" style='font-family: "Arial Narrow", arial, helvetica, sans-serif; width: auto !important; margin-left: auto; margin-right: auto;border-bottom: 0;'>
 <thead>
  <tr>
   <th style="text-align:left;"> Date A </th>
   <th style="text-align:left;"> Time A </th>
   <th style="text-align:left;"> Date B </th>
   <th style="text-align:left;"> Time B </th>
   <th style="text-align:left;"> Topics </th>
   <th style="text-align:left;"> Chapters </th>
  </tr>
 </thead>
<tbody>
  <tr>
   <td style="text-align:left;"> Oct. 6 </td>
   <td style="text-align:left;"> 02:00PM - 03:30PM </td>
   <td style="text-align:left;"> Oct. 7 </td>
   <td style="text-align:left;"> 01:00PM - 02:30PM </td>
   <td style="text-align:left;"> * Introduction to the course <br>Basic concepts </td>
   <td style="text-align:left;"> 1 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> Oct. 12 </td>
   <td style="text-align:left;"> 01:00PM - 02:30PM </td>
   <td style="text-align:left;"> Oct. 14 </td>
   <td style="text-align:left;"> 01:00PM - 02:30PM </td>
   <td style="text-align:left;"> * Introduction to R <br>Introduction to inferential statistics </td>
   <td style="text-align:left;"> 2,3,4 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> Oct. 19 </td>
   <td style="text-align:left;"> 01:00PM - 02:30PM </td>
   <td style="text-align:left;"> Oct. 21 </td>
   <td style="text-align:left;"> 01:00PM - 02:30PM </td>
   <td style="text-align:left;"> * Hypothesis testing I </td>
   <td style="text-align:left;"> 5,6.1,6.2,6.3 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> Oct. 29 </td>
   <td style="text-align:left;"> 01:00PM - 02:30PM </td>
   <td style="text-align:left;"> Oct. 28 </td>
   <td style="text-align:left;"> 01:30PM - 03:00PM </td>
   <td style="text-align:left;"> * Hypothesis testing II </td>
   <td style="text-align:left;"> 6.4,6.5,6.6 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> Nov. 2 </td>
   <td style="text-align:left;"> 01:00PM - 02:30PM </td>
   <td style="text-align:left;"> Nov. 4 </td>
   <td style="text-align:left;"> 01:00PM - 02:30PM </td>
   <td style="text-align:left;"> * Regression </td>
   <td style="text-align:left;"> 7 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> Nov. 9 </td>
   <td style="text-align:left;"> 01:00PM - 02:30PM </td>
   <td style="text-align:left;"> Nov. 11 </td>
   <td style="text-align:left;"> 01:00PM - 02:30PM </td>
   <td style="text-align:left;"> * Exploratory factor analysis </td>
   <td style="text-align:left;"> 8 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> Dec. 15 </td>
   <td style="text-align:left;"> 08:30AM - 10:30AM </td>
   <td style="text-align:left;"> Dec. 15 </td>
   <td style="text-align:left;"> 08:30AM - 10:30AM </td>
   <td style="text-align:left;"> * Final exam (online) </td>
   <td style="text-align:left;">  </td>
  </tr>
</tbody>
<tfoot><tr><td style="padding: 0; " colspan="100%">
<span style="font-style: italic;">Note: </span> <sup></sup> Dates and times are indicated for groups A and B respectively.</td></tr></tfoot>
</table>
<br>

::: {.infobox_red .caution data-latex="{caution}"}
We understand that the distance learning format poses challenges to the learning process because we cannot troubleshoot in person during the sessions. Remember that it is unlikely that you are the only student encountering a particular error, so please make use of the forum on Learn\@WU to interact with your peers or ask us questions so everyone else will benefit from the answer (there are no stupid questions). In case you cannot get answers to address a specific problem, we are available 90 min. after each Q&A sessions for short individual coaching sessions (please register by sending me a short email if you require assistance - [nils.wloemert@wu.ac.at](mailto:nils.wloemert@wu.ac.at)).
:::

#### Individual assignments {-}

There will be 4 individual assignments and each assignment is complemented with live video coaching sessions. Note that the assignments need to be submitted in the [R Markdown format](https://rmarkdown.rstudio.com/) and there will be a live video coaching sessions dedicated to this reporting format. The submission dates and the dates and times for the coaching sessions are summarized in the following table: 

<table class=" lightable-paper lightable-hover" style='font-family: "Arial Narrow", arial, helvetica, sans-serif; width: auto !important; margin-left: auto; margin-right: auto;border-bottom: 0;'>
 <thead>
  <tr>
   <th style="text-align:left;"> Date A </th>
   <th style="text-align:left;"> Time A </th>
   <th style="text-align:left;"> Date B </th>
   <th style="text-align:left;"> Time B </th>
   <th style="text-align:left;"> Task </th>
   <th style="text-align:left;"> Chapters </th>
  </tr>
 </thead>
<tbody>
  <tr>
   <td style="text-align:left;"> Oct. 18 </td>
   <td style="text-align:left;"> 11:59PM </td>
   <td style="text-align:left;"> Oct. 20 </td>
   <td style="text-align:left;"> 11:59PM </td>
   <td style="text-align:left;"> * Submit assignment 1: DataCamp </td>
   <td style="text-align:left;">  </td>
  </tr>
  <tr>
   <td style="text-align:left;"> Oct. 20 </td>
   <td style="text-align:left;"> 02:00PM - 05:00PM </td>
   <td style="text-align:left;"> Oct. 23 </td>
   <td style="text-align:left;"> 02:00PM - 05:00PM </td>
   <td style="text-align:left;"> * Coaching assignment 2 &amp; R Markdown tutorial (live video coaching) </td>
   <td style="text-align:left;"> 9 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> Oct. 28 </td>
   <td style="text-align:left;"> 11:59PM </td>
   <td style="text-align:left;"> Oct. 27 </td>
   <td style="text-align:left;"> 11:59PM </td>
   <td style="text-align:left;"> * Submit assignment 2: Hypothesis testing I </td>
   <td style="text-align:left;">  </td>
  </tr>
  <tr>
   <td style="text-align:left;"> Nov. 2* </td>
   <td style="text-align:left;"> 02:00PM - 06:00PM </td>
   <td style="text-align:left;"> Nov. 2* </td>
   <td style="text-align:left;"> 02:00PM - 06:00PM </td>
   <td style="text-align:left;"> * Coaching assignment 3 (live video coaching) </td>
   <td style="text-align:left;">  </td>
  </tr>
  <tr>
   <td style="text-align:left;"> Nov. 5 </td>
   <td style="text-align:left;"> 11:59PM </td>
   <td style="text-align:left;"> Nov. 5 </td>
   <td style="text-align:left;"> 11:59PM </td>
   <td style="text-align:left;"> * Submit assignment 3: Hypothesis testing II </td>
   <td style="text-align:left;">  </td>
  </tr>
  <tr>
   <td style="text-align:left;"> Nov. 11 </td>
   <td style="text-align:left;"> 03:00PM - 06:00PM </td>
   <td style="text-align:left;"> Nov. 11 </td>
   <td style="text-align:left;"> 03:00PM - 06:00PM </td>
   <td style="text-align:left;"> * Coaching assignment 4 (live video coaching) </td>
   <td style="text-align:left;">  </td>
  </tr>
  <tr>
   <td style="text-align:left;"> Nov. 16 </td>
   <td style="text-align:left;"> 11:59PM </td>
   <td style="text-align:left;"> Nov. 18 </td>
   <td style="text-align:left;"> 11:59PM </td>
   <td style="text-align:left;"> * Submit assignment 4: Regression </td>
   <td style="text-align:left;">  </td>
  </tr>
</tbody>
<tfoot><tr><td style="padding: 0; " colspan="100%">
<span style="font-style: italic;">Note: </span> <sup></sup> Dates and times are indicated for groups A and B respectively. <br>           Dates indicated with '*' are optional time slots for individual coaching.<br>           If you would like to schedule a meeting, please contact Mirza (mirza.mujanovic@wu.ac.at)</td></tr></tfoot>
</table>

#### Group project {-}

The marketing research group project consists of multiple consecutive steps: 

* the design of a questionnaire
* data collection using an online survey
* data handling
* data analysis
* presentation of the results 

We will offer coaching sessions via live video streaming (Zoom) throughout the process, providing feedback and allowing you to ask questions. 

The submission dates and the dates and times for the coaching sessions are summarized in the following table: 

<table class=" lightable-paper lightable-hover" style='font-family: "Arial Narrow", arial, helvetica, sans-serif; width: auto !important; margin-left: auto; margin-right: auto;border-bottom: 0;'>
 <thead>
  <tr>
   <th style="text-align:left;"> Date A </th>
   <th style="text-align:left;"> Time A </th>
   <th style="text-align:left;"> Date B </th>
   <th style="text-align:left;"> Time B </th>
   <th style="text-align:left;"> Task </th>
   <th style="text-align:left;"> Chapters </th>
  </tr>
 </thead>
<tbody>
  <tr>
   <td style="text-align:left;"> Oct. 21 </td>
   <td style="text-align:left;"> 11:59PM </td>
   <td style="text-align:left;"> Oct. 25 </td>
   <td style="text-align:left;"> 11:59PM </td>
   <td style="text-align:left;"> * Submit questionnaire draft </td>
   <td style="text-align:left;"> 10 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> Oct. 23* </td>
   <td style="text-align:left;"> 09:00AM - 02:30PM </td>
   <td style="text-align:left;"> Oct. 27* </td>
   <td style="text-align:left;"> 02:00PM - 08:00PM </td>
   <td style="text-align:left;"> * Coaching: Questionnaire design (live video coaching) </td>
   <td style="text-align:left;"> 10 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> Nov. 1 </td>
   <td style="text-align:left;"> 11:59PM </td>
   <td style="text-align:left;"> Nov. 4 </td>
   <td style="text-align:left;"> 11:59PM </td>
   <td style="text-align:left;"> * Submit revised questionnaire </td>
   <td style="text-align:left;"> 10 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> Nov. 16* </td>
   <td style="text-align:left;"> 01:30PM - 04:30PM </td>
   <td style="text-align:left;"> Nov. 18* </td>
   <td style="text-align:left;"> 02:00PM - 05:00PM </td>
   <td style="text-align:left;"> * Coaching: Data handling (live video coaching) </td>
   <td style="text-align:left;">  </td>
  </tr>
  <tr>
   <td style="text-align:left;"> Nov. 23* </td>
   <td style="text-align:left;"> 01:30PM - 06:30PM </td>
   <td style="text-align:left;"> Nov. 25* </td>
   <td style="text-align:left;"> 03:00PM - 08:00PM </td>
   <td style="text-align:left;"> * Coaching: Data analysis (live video coaching) </td>
   <td style="text-align:left;">  </td>
  </tr>
  <tr>
   <td style="text-align:left;"> Dec. 7 </td>
   <td style="text-align:left;"> 11:59PM </td>
   <td style="text-align:left;"> Dec. 9 </td>
   <td style="text-align:left;"> 11:59PM </td>
   <td style="text-align:left;"> * Submit video recording of presentation (pre-recorded) </td>
   <td style="text-align:left;">  </td>
  </tr>
</tbody>
<tfoot><tr><td style="padding: 0; " colspan="100%">
<span style="font-style: italic;">Note: </span> <sup></sup> Dates and times are indicated for groups A and B respectively.<br>           Sessions indicated with '*' are group coaching sessions. Slots of 45 min. are assigned to each group within the indicated times.</td></tr></tfoot>
</table>

### Grading {-}

Grading is based on the following components:

* **Market research group project** (questionnaire design, data collection & analysis, reporting & presentations) [weight: 30%]
* **Individual take-home computer exercises** (statistical analysis of data sets; 4 assignments à 5%) [weight: 20%]
* **Final online exam** (concepts & methods) [weight: 40%]
* **Class participation** (quantity & quality of contributions during the weekly Q&A sessions, contributions in the online forum, etc.) [weight: 10%]

These grading components will be weighted with the respective weights to arrive at the final grade percentage.

Please note that to ensure an equal contribution of group members for the group assignment, a **peer assessment** will be conducted among group members, which enters into the computation of the individual grades for the project. This means that the members of a group are required to assess other students regarding their relative contribution. 

**To successfully pass this course, your weighted final grade needs to exceed 60%.**

## Course materials {-}

### Main reference {-}

The main reference for this course is this website along with the corresponding slides and the pre-recorded video lectures. The relevant materials for each week are indicated in the tables above. The aim of the materials is to condense the contents and direct your attention to the most relevant aspects. This should enable students to study the materials on their own and we can focus our attention during the live video sessions on clarifying points that require further discussion. 

At the end of each chapter, you will find a section with references. It is highly recommended that you consult these references for further clarification in case you require additional information on a topic.  

### Further readings {-}

<p style="text-align:center;">
<img src="https://github.com/IMSMWU/Teaching/raw/master/MRDA2017/Graphics/R4ds.png" alt="DSUR cover" height="120"  />&nbsp;
<img src="https://github.com/IMSMWU/Teaching/raw/master/MRDA2017/Graphics/ISL_cover.jpg" alt="ISL cover" height="120"  />&nbsp;
<img src="https://github.com/IMSMWU/Teaching/raw/master/MRDA2017/Graphics/r4mra.jpg" alt="R4mra cover" height="120"  />&nbsp;
<img src="https://github.com/IMSMWU/Teaching/raw/master/MRDA2017/Graphics/advr.jpg" alt="advr cover" height="120"  />&nbsp;
<img src="https://github.com/IMSMWU/Teaching/raw/master/MRDA2017/Graphics/tmwr.png" alt="tmwr cover" height="120"  />&nbsp;
<img src="https://github.com/IMSMWU/Teaching/raw/master/MRDA2017/Graphics/r_packs.png" alt="Rpacks cover" height="120"/>
<img src="https://github.com/IMSMWU/Teaching/raw/master/MRDA2017/Graphics/URfIE.png" alt="Rpacks cover" height="120"/>
<img src="https://github.com/IMSMWU/Teaching/raw/master/MRDA2017/Graphics/rgraph.jpg" alt="Rgraph cover" height="120"/>
</p>

In addition to these lecture notes, there are many excellent books available (many of them for free) that focus on different aspects of R. In case you would like to learn more about the capabilities of R, I can recommend the following books:

* __"[R for Data Science](http://r4ds.had.co.nz/)"__ An excellent book by Hadley Wickham, which introduces you to R as a tool for doing data science, focusing on a consistent set of packages known as the tidyverse. [FREE online version]

* __"[An Introduction to Statistical Learning](http://www-bcf.usc.edu/~gareth/ISL/)"__ This book provides an introduction to statistical learning methods and covers basic methods (e.g., linear regression) as well as more advanced methods (e.g., Support Vector Machines). [FREE online version]

* __"[R for Marketing Research and Analytics](http://r-marketing.r-forge.r-project.org/)"__ A great book that is designed to teach R to marketing practitioners and data scientists.

* __"[Statistical Inference via Data Science](https://moderndive.com/)"__ Another book covering topics around Statistical Inference. [FREE online version]

* __"[Text Mining with R](http://tidytextmining.com/)"__ This book explains how you can analyze unstructured data (texts) using R. [FREE online version]

* __"[Advanced R](http://adv-r.had.co.nz/)"__ Another great book written by Hadley Wickham. Explains more advanced R concepts. [FREE online version]

* __"[Hands-On Machine Learning with R](https://bradleyboehmke.github.io/HOML/)"__ A great reference to learn about machine learning methods in R. The book favors a hands-on approach, growing an intuitive understanding of machine learning through concrete examples and little bit of theory.[FREE online version]

* __"[Hands-On Data Science for Marketing](https://github.com/PacktPublishing/Hands-On-Data-Science-for-Marketing)"__ Another good reference regarding Data Science for Marketing. [FREE Code exercises]

* __"[R Markdown](https://bookdown.org/yihui/rmarkdown/)"__ A great book about the reporting format 'R Markdown', which we will also use for the assignments in this course. [FREE Code exercises]

* __"[R Packages](http://r-pkgs.had.co.nz/)"__ A book which teaches you how to make the most of R's fantastic package system. [FREE online version]

* __"[R Graphics Cookbook](https://r-graphics.org/)"__ A practical guide that provides more than 150 recipes to help you generate high-quality graphs quickly. [FREE online version]

* __"[Using R For Introductory Econometrics](http://www.urfie.net/read/index.html)"__ This book covers a nice introduction to R with a focus on the implementation of standard tools and methods used in econometrics. [FREE online version]

* __"[Data Science in a Box](https://datasciencebox.org/)"__ Another book covering topics around Data Science using R. [FREE online version]

* __"[Efficient R Programming](https://csgillespie.github.io/efficientR/)"__ A good reference to learn efficient workflows using R. [FREE online version]

* __"[Discovering Statistics Using R](https://www.amazon.de/Discovering-Statistics-Using-Andy-Field/dp/1446200469)"__ (Field, A., Miles, J., & Field Zoe, 2012, 1st Edtn.) This textbook offers an accessible and comprehensive introduction to statistics. 

### Discussion forum {-}

Because there will be limited contact on campus this semester, we would like to facilitate the interaction among students. Thus, we created a discussion forum, which you can access via the course page on the WU learning platform. The purpose of the forum is to allow you to discuss questions related to the contents with your class mates. Please make use of this forum as much as possible and ask questions if something remained unclear. Remember that there are no stupid questions. And if you know the answer to a question that is asked in the forum, it is also a good exercise to explain the concepts to your class mates. 

### DataCamp {-}

<p style="text-align:center;">
<img src="https://github.com/IMSMWU/Teaching/raw/master/MRDA2017/Graphics/DataCamp50h1.png" alt="DSUR cover" height="50"  />&nbsp;
</p>

Please also make use of the abundance of web resources. For students who would like to further train the materials covered in class, we recommend DataCamp, an online platform that offers interactive courses in data science at different levels. To facilitate the learning process you will obtain full access to the entire DataCamp course curriculum for the duration of the course. You will receive and invitation via your WU student email address. Please note that you need to sign up to DataCamp to complete the first assignment.  

### Other web-resources {-}

* __"[https://www.r-project.org/](https://www.r-project.org/)"__ official website
  
* __"[http://www.statmethods.net/](http://www.statmethods.net/)"__ R reference by the author of “R in action”

* __"[http://www.rdocumentation.org/](http://adv-r.had.co.nz/)"__ R documentation aggregator

* __"[http://stackoverflow.com/](http://stackoverflow.com/)"__ general discussion forum for programmers incl. R
  
* __"[http://stats.stackexchange.com/](http://stats.stackexchange.com/)"__ discussion forum on statistics and data analytics

* __"[http://www.r-bloggers.com/](http://www.r-bloggers.com/)"__ R blog aggregator

* __"[http://www.cookbook-r.com/](http://www.cookbook-r.com/)"__ useful examples for all kind of R problems

* __"[https://ggplot2.tidyverse.org/reference/index.html](https://ggplot2.tidyverse.org/reference/index.html)"__ reference for data visualization

### Contact {-}

I am happy to answer your questions, so feel free to send me a short email ([nils.wloemert@wu.ac.at](mailto:nils.wloemert@wu.ac.at)). Mirza Mujanovic will be the tutor for this course ([mirza.mujanovic\@wu.ac.at](mailto:mirza.mujanovic\@wu.ac.at)). We will be available during the weekly Q&A sessions to clarify your questions. Mirza will be your point of contact for questions regarding the group project and the individual assignments. However, please note that before you contact us, you should try to solve problems on your own first (e.g., by using the online tutorial, doing research online, or asking class mates). 

### Acknowledgements {-}

This tutorial is supported through Digital Learning Project Funding by WU Vienna. None of the materials covered in this tutorial are new. We intend to provide a summary of existing methods from a marketing research perspective and cite the corresponding sources. If you should have any comments or suggestions, please [contact us through the github page of this course](https://github.com/IMSMWU/MRDA_issues). 
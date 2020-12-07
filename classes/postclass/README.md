# Post-Class 431 Web Page

On or around 2020-12-15, I will edit this post-class page to include information on 431 grades, and detailed suggestions for the break.

- I’ll email a link to everyone in the 431 class when this page is fully revised, regardless of whether they've signed up for 432. 

# Information on 431 Close-Out and Grades

Your grade in this course is determined by Dr. Love once all elements are in, using the process described [in Section 13 of the Syllabus](https://thomaselove.github.io/431-2020-syllabus/determining-course-grades.html). 

- Your **class participation grade** is determined in large part by your completion of Minute Papers. Your Minute Paper grade is available [in the grades roster](http://bit.ly/431-2020-grades). 
    - Your class participation grade cannot be lower than your Minute Paper grade. Dr. Love won't make final decisions about class participation adjustments until all other grades are complete.
    - Dr. Love can add up to 15 points for completed bonus activities, helpful Piazza comments/answers/questions, helpful in-class participation and TA feedback. 
        - Most students will gain between 0 and 5 points beyond their Minute Paper score. 
        - A way to get an easy point is to finish the class evaluation at https://webapps.case.edu/courseevals/ so that you can truthfully answer `a` to question 31 on Quiz 2.
- Your **labs grade** is available now [in the grades roster](http://bit.ly/431-2020-grades). This includes your grade (and TA feedback) on Lab 8.
    - If you want Dr. Love to review your grade on a Lab, you must submit the [form to request a regrade](http://bit.ly/431-2020-lab-regrade-requests) by Thursday 2020-12-10 at noon.
- Your **projects grade**. You should know your grade on Project A already. Grades on Project B will be available once Dr. Love has graded Project B.
- Your **quiz grade**. You should know your grade on Quiz 1 already. Grades on Quiz 2 will be available once Dr. Love has graded Quiz 2.

Additional information will be forthcoming.

# Things to Do Over the Break

- My best tip is to keep analyzing data using R. Perhaps you could work on one or more of [the Tidy Tuesday projects](https://thomasmock.netlify.app/post/tidytuesday-a-weekly-social-data-project-in-r/). There's a new data set every week! 
    - David Robinson's [YouTube series of live Tidy Tuesday analysis screencasts](https://www.youtube.com/user/safe4democracy/videos) can be especially helpful in learning new tricks with visualization and data management.
- I suggest you [convert your CWRU password to a passphrase](https://thedaily.case.edu/cwru-login-now-requires-passphrase/) as soon as you've completed the 431 course.
- I suggest you upgrade to R 4.0.3 and to the latest version of RStudio as soon as you've completed the 431 course.

## Resources That May Be Of Interest to You

- [Fundamentals of Data Visualization](https://clauswilke.com/dataviz/) by Claus O. Wilke
- [Statistics Done Wrong](https://www.statisticsdonewrong.com/index.html) (the woefully complete guide) by Alex Reinhart
- [A `ggplot2` Tutorial for Beautiful Plotting in R](https://cedricscherer.netlify.app/2019/08/05/a-ggplot2-tutorial-for-beautiful-plotting-in-r/) recently updated by Cedric Scherer, and now including interactive displays.
- Care to make a beautiful streetmap with ggplot2? [Check out this tutorial](https://ggplot2tutor.com/streetmaps/streetmaps/).
- [Brendan Cullen](https://twitter.com/_bcullen/status/1333878752741191680) started a great thread (see below) on Twitter [that I'm following](https://twitter.com/_bcullen/status/1333878752741191680).


![](https://github.com/THOMASELOVE/431-2020/blob/master/classes/postclass/images/Cullen_2020.png)

## Meeting with Professor Love

After December 14, Dr. Love will be pretty quiet through mid-January. I'll next hold office hours during the week of January 21-25, when I will meet individually with students in the MS program in Health Care Analytics in particular, but will also have open Zoom meetings where I can talk to former 431 students and prospective 432 students about whatever they want to talk about. Details to come.

# About 432

1. Don’t panic. Nothing is mandatory before 2021-02-01 for 432, other than obtaining a book or two and registering for the course (no, you cannot audit.)
2. My best advice about preparing for 432 is to get some rest. Take care of yourself, and those around you. **Make good choices**.
3. The books for the Spring 2021 course are not yet settled. 
    - We'll almost certainly read Nate Silver's [*The Signal and the Noise*](https://www.amazon.com/Signal-Noise-Many-Predictions-Fail-but/dp/0143125087)
    - We also might read Jeff Leek's [*How to be a Modern Scientist*](https://leanpub.com/modernscientist)
    - I reserve the right to change my mind on those selections at any time before 2020-01-15.

## Topics I Discussed in 432 in Spring 2020

These are the calendar descriptions of 432 classes in Spring 2020. 2021 will be meaningfully different. I will not have a complete syllabus (and website) available for 432 until late January. 

1. Building Table 1
2. David Spiegelhalter's *The Art of Statistics*
3. Multi-way ANOVA and ANCOVA Models
4. Interaction: Multi-categorical predictors
5. Predicting Binary Outcomes (Linear Probability and Logistic Regression Models via glm)
6. Model Selection and Cross-Validation in Linear Models
7. Non-linearity in regression
8. Using ols to fit flexible linear models, and use multiple imputation
9. Using lrm to fit flexible logistic models, and use multiple imputation
10. Multiple imputation strategies for glm and lm models
11. Ridge Regression and the Lasso
12. Aggregated Data in Logistic Regression
13. Probit Regression
14. Robust Linear Models
15. Regression on a Count outcome
16. Regression on an Ordinal Multi-categorical outcome
17. Regression on an Nominal Multi-categorical outcome
18. Dealing with Time-to-event (survival) data; Kaplan-Meier curves
19. Fitting Cox regression models for time-to-event data
20. The problems with p values
21. Retrospective Design / Thinking about Power
22. Dealing with Hierarchical Data: An Introduction

## Key Topics I Hope to Do Justice To in 432 in Spring 2021

These are my notes (mostly to myself) about important ideas for 432 this Spring. 

- Areas 1, 2, 4, 5, 8, 10, 13 and 14 on this list were substantial parts of the 2020 course. The others were not. 
- It is definitely part of the plan to add 3, 7 and 8. I don't know yet about anything else.
- I'll be happy if we do a reasonable job on more than half of these 15 areas. 

1. Logistic regression and other types of regression for other outcomes
2. Dealing with interaction and other forms of non-linearity by spending degrees of freedom on non-linear terms
3. Using [tidymodels](https://www.tidymodels.org/) approaches to build models in a more automated, tidier way
4. Variable selection and its woeful performance in real situations
5. Using regression methods for different purposes (exploring associations, making predictions, assessing cause and effect)
6. More extensive discussion of power and sample size (definitely retrospective design, and maybe also something about adaptive designs, or about non-inferiority trials?)
7. More on Bayesian modeling approaches, plus we'll read Nate Silver's *The Signal and The Noise*
8. Using sampling weights to mirror populations in modeling results (NHANES being a prime example)
9. Dealing with hierarchical data, with an introduction to repeated measures
10. Dealing with survival data, with an introduction to censoring, Kaplan-Meier curves and Cox models
11. Dealing with time series, with an introduction to ARIMA models
12. Dealing with control of processes (quality control), with an introduction to control charts
13. Why statistical significance and p values are problematic - using the TAS papers
14. Doing replicable research, and how to be a modern scientist with a web presence
15. Using Github more effectively to complete a longer-term project


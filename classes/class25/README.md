# 431 Class 25: 2020-12-01

[Main Website](https://thomaselove.github.io/431/) | [Course Calendar](https://thomaselove.github.io/431/calendar.html) | [Syllabus](https://thomaselove.github.io/431-2020-syllabus/) | [Course Notes](https://thomaselove.github.io/431-notes/) | [Piazza & TA Office Hours](https://thomaselove.github.io/431/contact.html) | [Canvas](https://canvas.case.edu) | [Data and Code](https://thomaselove.github.io/431/data_index.html)
:-----------: | :--------------: | :----------: | :---------: | :-------------: | :-----------: | :------------:
for everything | for deadlines | expectations | from Dr. Love | ways to get help | zoom information | for downloads

> ...the first act of the mind is always to simplify.   Reality is overwhelmingly complex.  We instinctively reduce the flood on information coming toward us to small bits of information.  We do that by throwing away 90% to 99% of the information and filing the event/person/ entity under a label based on the remaining portions.  (Bill James, 2020-11-24)

## Today's Slides

- Class 25 slides are available in [PDF format](https://github.com/THOMASELOVE/431-2020/blob/master/classes/class25/431_class-25-slides_2020.pdf), as well as in [R Markdown](https://github.com/THOMASELOVE/431-2020/blob/master/classes/class25/431_class-25-slides_2020.Rmd).

## Changes to Course Materials Since We Last Met

1. [Project B instructions](https://thomaselove.github.io/431-2020-projectB/)
    - In the [Study 2 Report Specifications](https://thomaselove.github.io/431-2020-projectB/your6.html), I added details in sections 3 and 5 which pull together advice I have provided elsewhere plus new information on cleaning data, the codebook, and what to check in your data. I attempted in section 5, in particular, to provide clear **recipes that you should follow** for this critical section of your Study 2 report. 
        - Some of this advice also appeared in the [Class 24 README](https://github.com/THOMASELOVE/431-2020/tree/master/classes/class24). 
        - I also placed a short note at the start of Sections 3 and 5 of the [Study 2 Demonstration Project](https://thomaselove.github.io/431-2020-projectB/your7.html) to remind you to look at these augmented instructions.
        - If you decide to make a modest change (perhaps changing a variable or two) to what you wrote in your Study 2 Data Plan, that's fine, and there's no need to let me know that. Just make what you're doing now clear in your Study 2 Report.
    - I added the [Instructions for the Oral Presentations](https://thomaselove.github.io/431-2020-projectB/tasks.html) to the [Checklist](https://thomaselove.github.io/431-2020-projectB/tasks.html) page on 2020-11-30. 
        - This includes separate instructions for those of you producing a recording, and those having a Zoom meeting with Dr. Love. My list of [who's doing what is here](https://github.com/THOMASELOVE/431-2020/blob/master/projects/projectB/presentation_schedule.md).
        - We've highlighted exactly what we expect in terms of timing and logistics. Let us know if you have questions.
    - I edited the [Study 1 Demonstration Project](https://thomaselove.github.io/431-2020-projectB/survey6.html) to not use `echo = FALSE` or `warning = FALSE` in the `opts_chunk$set(comment=NA)` in Section 1.1. since I wanted to match the restrictions I have for you, and the approach I used in the Study 2 Demonstration Project.
        - Your `opts_chunk$set` command in both Study reports (1 and 2) should only include `comment = NA`.
2. [Course Notes](https://thomaselove.github.io/431-notes/) 
    - I've now posted all 33 chapters, including 11 new ones since we last met. The class slides always show my most recent thinking for R coding, but I haven't found the time to fix that in the Notes in a few spots, but, for example, Chapters 28-31 have been completely rewritten to reflect our most current approaches. Most of chapters 23-27 are pretty much up-to-date, too. Chapters 32-33 feature older methods, with some surprises. On 2020-11-30, I revised Chapters 13 and 31 to fix small issues.
    - [Chapter 23](https://thomaselove.github.io/431-notes/estimating-a-population-proportion.html): Building Confidence Intervals for a Population Proportion
    - [Chapter 24](https://thomaselove.github.io/431-notes/comparing-proportions-with-two-independent-samples.html): Analyzing a Two-by-Two table to compare proportions
    - [Chapter 25](https://thomaselove.github.io/431-notes/larger-contingency-tables.html): Chi-square tests for larger 2-way tables and Cochran-Mantel-Haenszel for 3-way tables
    - [Chapter 26](https://thomaselove.github.io/431-notes/power-and-proportions.html): Sample Size and Power when comparing Two Proportions
    - [Chapter 27](https://thomaselove.github.io/431-notes/quiz-2-review.html): Some Practice Problems for Quiz 2 (with solutions)
    - [Chapter 28](https://thomaselove.github.io/431-notes/missing-data-mechanisms-and-simple-imputation.html): Missing Data and Simple Imputation
    - [Chapter 29](https://thomaselove.github.io/431-notes/multiple-regression-introduction.html): Setting Up Multiple Regression Case Studies, Outline of Key 431 Concepts
    - [Chapter 30](https://thomaselove.github.io/431-notes/regression-diagnostics.html): Regression Diagnostics
    - [Chapter 31](https://thomaselove.github.io/431-notes/building-prediction-models-for-wcgs.html): Building Prediction Models for the `wcgs` data
    - [Chapter 32](https://thomaselove.github.io/431-notes/species-found-on-the-galapagos-islands.html): The Galapagos Island Data featuring lots of questions to test yourself
    - [Chapter 33](https://thomaselove.github.io/431-notes/bmi-and-employment-study.html): The BMI and Employment in Korea Study featuring Old Ways To Build/Evaluate Regressions
3. On Canvas, you should now be able to **download all of our class Zoom recordings**.
    - When logged into 431 on Canvas, click Zoom, then select Cloud Recordings, pull up a recording of a class as if you were watching it, and at the top right, you should find a button to download the recording. I'm sorry it took until now for these to be downloadable.
    - The Zoom videos will start disappearing in mid-January of 2021. Grab them in December if you want them. 
    - 431 Course Notes and Github materials will disappear on 2021-06-01.
4. Grades for Lab 07 are posted in [the usual place](http://bit.ly/431-2020-grades).
 
## Announcements

1. [Instructions for the Project B Oral Presentations](https://thomaselove.github.io/431-2020-projectB/tasks.html) (recording and Zoom) are now available.
    - My list of [who's doing what (Zoom or recording) is here](https://github.com/THOMASELOVE/431-2020/blob/master/projects/projectB/presentation_schedule.md). 
2. The [Self-Evaluation Google Form for Project B](https://bit.ly/431-projectB-self-evaluation) is now available.
3. There is a [Minute Paper after Class 25](https://bit.ly/431-2020-minute-25), due at noon Wednesday 2020-12-02. 
4. **To be posted**. Answer sketch for Lab 8 will appear by class time on 2020-12-01.
5. TA office hours are back, and will continue every day through Monday 2020-12-07.
6. [The `forcats` package](https://forcats.tidyverse.org/index.html) is an incredibly useful tool for working with factors, but it's sometimes a challenge to figure out which function to use in a particular situation. 
    - [Here is a comprehensive list](https://forcats.tidyverse.org/reference/index.html) of all of the functions available for changing the order of levels, changing the value of level, adding or removing levels, combining multiple factors, and other helper functions, including links to examples.
    - The [RStudio Cheat Sheet (pdf)](https://github.com/rstudio/cheatsheets/raw/master/factors.pdf) for working with factors using `forcats` is very useful.
    - Emily Robinson provides a gentle [introduction to forcats](https://forcats.tidyverse.org/articles/forcats.html)
    - R for Data Science has a [chapter on factors](https://r4ds.had.co.nz/factors.html)
    - Amelia McNamara and Nicholas Horton have a 2017 paper on [Wrangling categorical data in R](https://peerj.com/preprints/3163/) that helped motivate the `forcats` package.
7. **Do I need to upgrade R or RStudio?** 
    - There is no need for you to upgrade until after you complete both Project B and Quiz 2. We assume you have version 4.0.2 of R and RStudio version 1.3.xxx. You are *welcome* to upgrade, but it is more likely to cause problems than solve them for you at this point.
    - Dr. Love intends to continue using R version 4.0.2 and RStudio version 1.3.1056 through the end of the course.
    - As of 2020-11-22, the current versions that are available are R version 4.0.3 and RStudio version 1.3.1093.
8. **equatiomatic** and `results = 'asis'`. 
    - If you decide to use the `equatiomatic` package to produce a listing of a regression equation, we've seen that you have to use `results = 'asis'` in setting up that particular chunk of code. Don't use `results = 'asis'` in any other part of your R Markdown, though, or you will face some very unfortunate results in your HTML files.
9.  **Labelled class** Those of you working with NHANES data may encounter labelled variables. To view the labels, I'd run `Hmisc::describe()`. If you want to remove variable labels because they're causing a problem with a plot or model, I'd use `zap_label()` from [the `haven` package](https://haven.tidyverse.org/reference/zap_labels.html) (part of the `tidyverse`).
    - `zap_label()` (when applied to a tibble) removes variable labels, which are usually the issue in NHANES.
    - `zap_labels()` (with an "s") removes value labels.
10. **COVID trials webinar** There is a webinar on Thursday 2020-12-03 at noon Eastern that I'll be attending (the first half hour of) entitled [The Statistics of COVID-19 Vaccine Trials](https://www.niss.org/events/copss-niss-covid-19-data-science-webinar-series) which might be of interest to you. Register at that link if you want to attend.

## What Should I Be Doing?

1. Now that we're in December, don't forget about staying healthy, keeping other people healthy, and taking care of those that need your help. **Make good choices.**
2. [Minute Paper after Class 25](https://bit.ly/431-2020-minute-25) is due Wednesday 2020-12-02 at noon.
    - One of the questions is about your plans for 432. You may want to see [this list of key 432 topics](https://github.com/THOMASELOVE/431-2020/blob/master/classes/class26/README.md#key-topics-i-hope-to-do-justice-to-in-432) (which we'll discuss Thursday.)
3. The Scheduling form for Project B oral presentations due Wednesday 2020-12-02 at noon, too.
    - People I'm waiting to hear from (as of 9 PM Monday 2020-11-30) are **Emily Conlan, Akif Gormez, Marie Michenkova, Aman Pande, Zoe Sekyonda and Kristi Westphaln**. If you are sure what you're doing, please let me know as soon as you can.
    - If you're [currently scheduled to do a recording](https://github.com/THOMASELOVE/431-2020/blob/master/projects/projectB/presentation_schedule.md) but want to switch to a Zoom meeting, email Dr. Love now and he'll see if that can happen.
    - The complete schedule of Zoom presentations will be available [at this link](https://github.com/THOMASELOVE/431-2020/blob/master/projects/projectB/presentation_schedule.md) by class time Thursday.
4. [Project B](https://thomaselove.github.io/431-2020-projectB) and everything is due 2020-12-10 at Noon, other than the Zoom presentations.
    - If you want TA help on your project, remember to get it by the end of the day Monday 2020-12-07.
    - Dr. Love will monitor Piazza for Project B questions until 2020-12-10 at 9 AM.
5. [Quiz 2](https://github.com/THOMASELOVE/431-2020/tree/master/quizzes/quiz2) will appear before noon Friday 2020-12-04, and is due on 2020-12-14 at Noon.
    - Questions about Quiz 2? Ask them via Piazza via private messages to the Instructor(s) before 2020-12-14 at 9 AM.
6. Fill out the [CWRU Course Evaluation](https://webapps.case.edu/courseevals/) which is available through 2020-12-16. 
    - It's very important to me to have as many of you as possible do this.

## One Last Thing

- From [Walt Hickey at Numlock News](https://numlock.substack.com/), writing about [this interesting data analysis](https://pudding.cool/2020/11/crossword/) by Michelle McGhee with Russell Goldenberg and Jan Diehm at The Pudding.

> An analysis of a sample of tens of thousands of crossword clues, assigning the answers to the actual human people who were the solutions, found that in 2020, 64 percent of the proper noun clues in the New York Times crossword were linked to men, and just 28 percent to a person in a minoritized racial group. Similar disparities were seen in the L.A. Times crossword (68 percent male, 25 percent non-white), Wall Street Journal crossword (69 percent male, 24 percent non-white) and Universal syndicate (54 percent men, 29 percent non-white). Interestingly, in 2020, the USA Today crossword flips that, with 72 percent of the proper noun answers being women and 48 percent of them being from a minoritized racial group, which is actually a serious effort enacted by Erik Agard, the new 27-year-old editor in charge of the USA Today puzzle since the end of 2019.

We've settled into a routine since June in my house, where I do the NY Times crossword puzzles on Monday-Wednesday, and we do Thursday-Sunday together. Here are some of our statistics through 2020-11-30, as an example of where "expert knowledge" of the data would lead you to a very different set of conclusions about the relative difficulty of the puzzles each week than an analysis unsullied by such "subjective" understanding of the underlying process.

![](https://github.com/THOMASELOVE/431-2020/blob/master/classes/class25/images/puzzle_2020-11-30.png)


# 431 Class 26: 2020-12-03

[Main Website](https://thomaselove.github.io/431/) | [Course Calendar](https://thomaselove.github.io/431/calendar.html) | [Syllabus](https://thomaselove.github.io/431-2020-syllabus/) | [Course Notes](https://thomaselove.github.io/431-notes/) | [Piazza & TA Office Hours](https://thomaselove.github.io/431/contact.html) | [Canvas](https://canvas.case.edu) | [Data and Code](https://thomaselove.github.io/431/data_index.html)
:-----------: | :--------------: | :----------: | :---------: | :-------------: | :-----------: | :------------:
for everything | for deadlines | expectations | from Dr. Love | ways to get help | zoom information | for downloads

![](https://github.com/THOMASELOVE/431-2020/blob/master/classes/class26/images/taylor_2020.png) from [@seanjtaylor](https://twitter.com/seanjtaylor/status/1333268960704249862)

## Today's Slides

- Class 26 slides will be made available in [PDF format](https://github.com/THOMASELOVE/431-2020/blob/master/classes/class26/431_class-26-slides_2020.pdf), as well as in [R Markdown](https://github.com/THOMASELOVE/431-2020/blob/master/classes/class26/431_class-26-slides_2020.Rmd).

## Announcements

1. [Feedback on the Minute Paper after Class 25](https://bit.ly/431-2020-min25-feedback) is available now.
2. TA Office Hours continue through Monday 2020-12-07.
3. In light of the first two questions in Lab 7, Karl Broman presents [The Top Ten Worst Graphs in the Scientific Literature](https://www.biostat.wisc.edu/~kbroman/topten_worstgraphs/) as published in 1994-2012.
4. Alison Hill on [How I Teach R Markdown](https://alison.rbind.io/post/2020-05-28-how-i-teach-r-markdown/) has some useful tips.
5. [Interactive data tables in R with `reactable`](https://glin.github.io/reactable/index.html), as [highlighted by @Dataandme](https://twitter.com/dataandme/status/1196552930167599106?s=11). Check out the demos!
6. [Rayshader for building 3-dimensional ggplots!](https://www.tylermw.com/3d-ggplots-with-rayshader/), and Tyler Morgan-Wall (who developed the package) describes and demonstrates these things at [this YouTube link](https://www.youtube.com/watch?v=G6Y3-_GKtcs&feature=youtu.be). 
    - Learn how a single line of code can transform your data visualizations into stunning 3D using the rayshader package. In this talk, I will show how you can use rayshader to create beautiful 3D figures and animations to help promote your research and analyses to the public.
7. Care to make a beautiful streetmap with ggplot2? [Check out this tutorial](https://ggplot2tutor.com/streetmaps/streetmaps/).

## What Should I Be Working On?

1. [Project B](https://thomaselove.github.io/431-2020-projectB/) 
    - Presentations [are now scheduled](https://github.com/THOMASELOVE/431-2020/blob/master/projects/projectB/presentation_schedule.md). 
        - If you have a scheduled Zoom meeting that is [listed as not yet confirmed](https://github.com/THOMASELOVE/431-2020/blob/master/projects/projectB/presentation_schedule.md), please respond to my email sent on 2021-12-01 to confirm your spot.
    - The Canvas link to submit Project B materials went live today. Everything must be in at that link by noon on 2020-12-10.
    - Don't forget to submit the [Project B Self-Evaluation Form](https://bit.ly/431-projectB-self-evaluation) by noon on 2020-12-10, too.
2. [Quiz 2](https://github.com/THOMASELOVE/431-2020/tree/master/quizzes/quiz2)
    - Instructions **to come** before noon Friday 2020-12-04. The Quiz is due 2020-12-14 at Noon.
    - Questions about Quiz 2 should be asked on Piazza through private messages to the instructor(s).
3. Fill out the [CWRU Course Evaluation](https://webapps.case.edu/courseevals/) which is available through 2020-12-16. 
    - It's very important to me to have as many of you as possible do this, so I'll be asking about it, possibly on Quiz 2.
4. Need a [regrade on a Lab](https://github.com/THOMASELOVE/431-2020/blob/master/labs/README.md#grading-errors-and-regrade-requests)? Fill in the form at http://bit.ly/431-2020-lab-regrade-requests by noon 2020-12-10.
    - Grades on Lab 8 should be available by Tuesday 2020-12-08.

## Taking Other Courses (like 432) With Me

Around 2020-12-15, I will edit [the post-class webpage](https://github.com/THOMASELOVE/431-2020/tree/master/classes/postclass) to include detailed suggestions for the break, and additional information on 432. 
    - You’ll also get the last few specific grades (project B/quiz 2, etc.) in 431 at about that time, although you'll get your final course grade only through SIS. 
    - I’ll email a link to everyone in the 431 class when grades are done and when the updated page is available.    

In addition to 431, I teach two other semester-long courses, called **PQHS 432** and **PQHS 500**. I am scheduled to teach both 432 and 500 in Spring 2021. Here's my advice, for what it's worth ...

- **432** is the continuation of this course (widely regarded as the "better" half.) I think **everyone** in this class should be planning to take 432 this Spring (i.e. Spring 2021), **unless** you don't feel you've received sufficient value from this course and don't need to take 432 to finish your program at CWRU, **or** you have an unshakable conflict in Spring 2021 (especially if you plan to instead take 432 in Spring 2022.)
    - Some (early) notes on the plans for 432 in Spring 2021 and what we discussed in the course in Spring 2020 are [provided here](https://github.com/THOMASELOVE/431-2020/blob/master/classes/postclass/README.md#about-432). I will write the 432 course in January, mostly.
- **500** is a project-based and more advanced course covering specific topics in the design and analysis of observational studies. 
    - I think everyone in this class who is interested in taking 500 should do so at some point. The course is mostly about using propensity scores well to help design (and analyze) data from observational studies where we want to estimate a causal effect.
    - I especially think MS and PhD students (in any department) interested in applications of health research in real world situations should take it, as well as people looking for jobs in fields related to health care analytics.
    - Most people would benefit from taking 500 in Spring 2022 rather than Spring 2021 if that option is available to you, since it's usually better to complete 432 before taking 500, for at least three reasons this year.
        1. percolation time
        2. potential for in-person learning rises
        3. too much of me at one time is a lot
    - However, if Spring 2021 is your best opportunity to take 500, for whatever reason, then I will certainly permit you to do so, but I'll want to talk to you about it a little before the class begins so that you (and I) know what you're getting into.

## Key References from Today's Slides

- [Common statistical tests are linear models](https://lindeloev.github.io/tests-as-linear/) by Jonas Kristoffer Lindeløv
- [Get Started with Tidymodels](https://www.tidymodels.org/start/)
- [TidyTuesday and tidymodels](https://juliasilge.com/blog/intro-tidymodels/) by [Julia Silge](https://juliasilge.com/)
- I have a surprise visualization example today, which (after the surprise has been revealed) might interest you in reading more from [Alberto Cairo](http://www.thefunctionalart.com/2016/08/download-datasaurus-never-trust-summary.html), [Steph Locke](https://cran.r-project.org/web/packages/datasauRus/vignettes/Datasaurus.html), [Julia Silge](https://juliasilge.com/blog/datasaurus-multiclass/) and [Justin Mareika and George Fitzmaurice](https://www.autodesk.com/research/publications/same-stats-different-graphs). 

## A Few Last Things

A [2019 paper in BMJ Open by Adrian Barnett and Jonathan Wren](https://bmjopen.bmj.com/content/9/11/e032506.full) examines nearly 1 million confidence intervals in health and medical journals over the period of 1976-2019 and found a huge number (perhaps an unbelievable number) that were just below the magic 0.05 "statistically significant" threshold. See [Adrian's tweet, too](https://twitter.com/aidybarnett/status/1197633930943315968).

- This isn't news. Check out [Masicampo and Lalande from 2012](https://pubmed.ncbi.nlm.nih.gov/22853650/)
- [Physicians and Statistics](https://jamanetwork.com/journals/jama/fullarticle/2754781) is a 100 year-old reprint (in JAMA) of a plea for better statistics in medicine. The money quote is probably: "It is probably true that the bulk of medical statistics of the past has been prepared by medical men not trained as expert statisticians." [My source was @RielyMD](https://twitter.com/rielymd/status/1196392547096104961?s=11)

Yes, there's an advent calendar for learning R. Kiirsti Own, a conservation biologist created [the 25 days of chRistmas](https://kiirstio.wixsite.com/kowen/post/the-25-days-of-christmas-an-r-advent-calendar).

![](https://github.com/THOMASELOVE/431-2020/blob/master/classes/class26/images/vacations.png) from [PhD Comics](http://phdcomics.com/comics/archive.php?comicid=2037)

![](https://imgs.xkcd.com/comics/electoral_precedent_2020.png) from [XKCD](https://xkcd.com/2383)


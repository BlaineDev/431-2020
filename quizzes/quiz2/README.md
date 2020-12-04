# Quiz 2 Information for 431 in Fall 2020

Available | Deadline
--------- | ------------
Friday 2020-12-04 by 3 PM | Monday 2020-12-14 at Noon

## Materials

- The [Instructions and Questions (pdf)](https://github.com/THOMASELOVE/431-2020/blob/master/quizzes/quiz2/431_2020_quiz2.pdf) is now available. Be sure that you have all **19** pages of this document.
- The [Answer Submission Form](https://bit.ly/431-2020-quiz2-answer-sheet) is where all responses should be submitted by **Noon on 2020-12-14**. The link is https://bit.ly/431-2020-quiz2-answer-sheet.
- I have provided one data set (called `survA.csv`) and two R scripts (our usual `Love-boost.R` and also `wc_code.R`) for this Quiz. They may be helpful to you. You will find them in our **Shared Google Drive** in the **data** subfolder within the **Quiz 2** folder.

## Questions?

If you need clarification on a Quiz question, you have exactly two ways of getting help:

1. You can ask your question in a private post on Piazza to the instructors. 
2. You can ask your question via email to **431-help at case dot edu**.

## Good luck!

------------

# Detailed Instructions (repeated from [the pdf](https://github.com/THOMASELOVE/431-2020/blob/master/quizzes/quiz2/431_2020_quiz2.pdf))

## The Google Form Answer Sheet 

Place your responses in the Google Form located at https://bit.ly/431-2020-quiz2-answer-sheet. All of your answers must be submitted through that Google Form by noon on Monday 2020-12-14, without exception. The form will close at that time, and no extensions will be made available, so do not wait until Monday to submit. We will not accept any responses except through the Google Form.

The Google Form contains places to provide your responses to each of the 31 questions (including a place to submit a file with your response to the essay in question 30), and a final affirmation where you'll type in your name to tell us that you followed the rules for the Quiz. You must complete that affirmation and then submit your results. When you submit your results (in the same way you submit a Minute Paper) you will receive an email copy of your submission, with a link that will allow you to edit your results.

If you wish to work on some of the quiz and then return later, you can do this by [1] typing in your name at the start of the Quiz, then [2] completing the affirmation (after Question 31) which asks you to type in your full name again (this time to affirm that you've followed these instructions), and then [3] submitting the quiz. You will then receive a link at your CWRU email which will allow you to return to the quiz as often as you like without losing your progress.

## Timing 

The Quiz is meant to take 5-6 hours. I expect most students will take 4-8 hours, and some will take as little as 3 or as many as 12. It is a bad idea to spend a long time on any one question without asking for help. 

## Responding to the Items 

The Quiz contains 31 questions. The first 30 comprise the actual Quiz and are worth a combined 100 points. It is to your advantage to answer all 31 Questions. Your score is based on the number of correct responses, so there's no chance a blank response will be correct, and a guess might be, so you should definitely answer all of the questions.

26 of the first 29 questions are worth 3 points each, and the others (questions 16, 17, 19) are worth 4-6 points, as indicated. 

- The first 15 questions all refer to the same data set and each have two parts to them. They test your ability to use R to analyze data, and are not arranged in order of difficulty. 
- Questions 16-29 are not in any special order.
- Questions 1-29 range in difficulty from "things I expect everyone to get right" to "things that are deliberately tricky".
- In Questions 1-29, when you have the option to type in a response, just provide the answers, without adding in material to create a complete sentence. 
    - So, for example, if you are asked how many students meet a particular standard and the answer is 10, please just type **10** into the form, as opposed to something like "There are 10 students."
    - Occasionally, we ask you to provide a single line of code. Do not include the `library` command at any time as part of your response. Assume in all questions that all relevant packages have been loaded in R.

Question 30 is an essay, which will require more time than any of the other questions. Question 30 requires the careful writing of complete sentences, which you will upload to the Google Form as either a PDF or Word document. You needn't use R Markdown to write your essay, although you are welcome to do so. Question 30 is worth 8 points.

Question 31 is about whether you've completed the class evaluation at https://webapps.case.edu/courseevals/. Question 31 has no impact on your Quiz 2 grade, but a response of `a` or `b` will add 1 point to your class participation grade.

## The Data Set and R Scripts
 
I have provided one data set (called `survA.csv`) and two R scripts (our usual `Love-boost.R` and also `wc_code.R`) for this Quiz. They may be helpful to you. You will find them in our Shared Google Drive in the data subfolder within the Quiz 2 folder.

## Getting Help

This is an open book, open notes quiz. You are welcome to consult the materials provided on the course website and that we've been reading in the class, but you are not allowed to discuss the questions on this quiz with **anyone** other than Professor Love and the teaching assistants. You will be required to complete a short affirmation that you have obeyed these rules as part of submitting the Quiz.

If you need clarification on a Quiz question, you have exactly two ways of getting help:

1. You can ask your question in a private post on Piazza to the instructors. 
2. You can ask your question via email to **431-help at case dot edu**.

During the Quiz period (from now through Noon 2020-12-14) we will not answer questions about the Quiz except through the two approaches listed above. We promise to respond to all questions received before 9 AM on 2020-12-14 in a timely fashion.

A few cautions:

- Specific questions are more likely to get helpful answers.
- We will not review your code or your English for you.
- We will not tell you if your answer is correct, or if it is complete.
- Dr. Love will email all students and post a note to Piazza if we find an error in the Quiz that needs fixing.

## When Should I ask for help?

We recommend the following process.

- If you encounter a tough question, skip it, and build up your confidence by tackling other questions.
- When you return to the tough question, spend no more than 10-15 minutes on it.
If you still don't have it, take a break (not just to do other questions) but an actual break.
- When you return to the question, it may be much clearer to you. If so, great. If not, spend 5-10 minutes on it, at most, and if you are still stuck, ask us for help.
- This is not to say that you cannot ask us sooner than this, but you should **never, ever** spend more than 20 minutes on any question without asking for help. 

## R Packages Dr. Love Used To Build This

This **doesn't** mean you need to use all of these packages, but Dr. Love was able to build a complete answer sketch using this setup (although he doesn't promise to have used all of these packages.)

```
library(knitr)
library(janitor)
library(mosaic)
library(naniar)
library(ggrepel)
library(car)
library(magrittr)
library(patchwork)
library(vcd)
library(Epi)
library(Hmisc)
library(broom)
library(tidyverse)

opts_chunk$set(comment = NA)
theme_set(theme_bw())

source("data/Love-boost.R")

survA <- read_csv("data/survA.csv")
```

I've also provided my session information at [the end of the PDF](https://github.com/THOMASELOVE/431-2020/blob/master/quizzes/quiz2/431_2020_quiz2.pdf) in case that helps you.


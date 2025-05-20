# SCI_2025
Statistics &amp; Causal Inference PhD Course 2025

This course is an introduction to the use of probabilistic models to answer scientific questions, aimed at graduate students in the social and biological sciences. We will cover three core subjects: (i) probability theory, (ii) Bayesian statistics, and (iii) causal inference. We will also engage with some information theory. The goal is to develop a strong understanding of these fundamentals--which apply broadly across research areas--and to be able to use Monte Carlo methods for simulation and estimation.

This course involves many hands-on exercises in R, because the only way to learn how to analyze data is to analyze *a lot* of data. Students should have the latest versions of R and Richard McElreath's `rethinking` package installed: https://github.com/rmcelreath/rethinking/. An IDE such as RStudio or VSCode is also highly reccomended. The course will be in English.

## Accessing course content and attending class

We will meet on Fridays via Zoom from 15:00 - 16:15, with the meeting link shared to registered participants. The course will feature "flipped" instruction: participants should come already having watched lectures and attempted the exercises for the week, and our class time will be used to solve problems together. Lectures and readings will be posted at least one week in advance.

The primary text for this course is the [2nd edition of Statistical Rethinking](https://github.com/rmcelreath/rethinking/). It is available as both a physical book and an eBook. A full series of lectures by the author is [available for free on YouTube](https://www.youtube.com/playlist?list=PLDcUM9US4XdMROZ57-OIRtIK0aOynbgZN).

## Course schedule (subject to change)

| Week # | Meeting date | Reading | Mini-Lectures | Homework |
| ------- | -------------- | ------------- | ---------------- | ---------------------- |
| Week 01: Probability, Bayes' Rule | 21 February  | Rethiking Ch. 2.0-2.3 (pp. 19-38) | https://youtu.be/xB5GWDfZWyw | No homework
| Week 02: Samples and Simulations | 28 February  | Rethinking Ch. 2.4-3 (pp. 39-68) | https://youtu.be/JAwWjHxcu44 | [Homework 1](https://github.com/ErikRingen/SCI_2025/blob/main/homeworks/HW1.pdf); [Solutions](https://github.com/ErikRingen/SCI_2025/blob/main/homeworks/HW1_solutions.pdf)
| Week 03: Linear Regression | 7 March  | Rethinking Ch. 4.0-4.5.1 (pp. 71-114) | https://youtu.be/fAVCxP80kCk | [Homework 2](https://github.com/ErikRingen/SCI_2025/blob/main/homeworks/HW2.pdf); [Solutions](https://github.com/ErikRingen/SCI_2025/blob/main/homeworks/HW2_solutions.pdf)
| Week 04: Causal Inference I: DAGs, Confounders, Counterfactuals | 14 March  | Rethinking Ch. 5 (pp. 123-158) | https://youtu.be/ajocBTi-tFI | [Homework 3](https://github.com/ErikRingen/SCI_2025/blob/main/homeworks/HW3.qmd)
| Week 05: Causal Inference II: Mediation, Colliders | 21 March  | Rethinking Ch. 6 (pp. 161-189) | https://youtu.be/wGblB6IY2ns | [Homework 4](http://github.com/ErikRingen/SCI_2025/blob/main/homeworks/HW4.pdf); [Solutions](https://github.com/ErikRingen/SCI_2025/blob/main/homeworks/HW4_solutions.pdf)
| Week 06: Causal Inference III: Estimands, estimators (**NO CLASS MEETING**)  | 28 March  | [Lundberg et al. (2021). What is your estimand? Defining the target quantity connects statistical evidence to theory](https://osf.io/ba67n/download/) | https://youtu.be/JGHuiwg4KDI | No homework
| Week 07: Information, Prediction, and Model Comparison | 4 April  | Rethinking Ch. 7 (pp. 191-235) | https://youtu.be/tO4oYTGj36I | [Homework 5](https://github.com/ErikRingen/SCI_2025/blob/main/homeworks/HW5.pdf); [Solutions](https://github.com/ErikRingen/SCI_2025/blob/main/homeworks/HW5_solutions.pdf)
| Week 08: Interactions and non-linearity | 11 April  | Rethinking Ch. 8 (pp. 237-260) | https://youtu.be/EG44N2jHzi8 | [Homework 6](https://github.com/ErikRingen/SCI_2025/blob/main/homeworks/HW6.pdf); [Solutions](https://github.com/ErikRingen/SCI_2025/blob/main/homeworks/HW6_solutions.pdf)
| spring break |
| spring break |
| Week 09: Markov Chain Monte Carlo | 2 May  | Rethinking Ch. 9 (pp. 263-296) | https://youtu.be/EVpuOrG2Clc | [Homework 7](https://github.com/ErikRingen/SCI_2025/blob/main/homeworks/HW7.pdf); [Solutions](https://github.com/ErikRingen/SCI_2025/tree/main/homeworks#:~:text=2%20weeks%20ago-,HW7_solutions.qmd,-hw7%20solutions)
| Week 10: Generalized Linear Models | 9 May  | Rethinking Ch. 10.2-10.4 (pp. 312-321), Rethinking Ch. 11.1-11.2 (pp. 342-359) | https://youtu.be/JUDI-cg05Jw | [Homework 8](https://github.com/ErikRingen/SCI_2025/blob/main/homeworks/HW8.qmd); [Solutions](https://github.com/ErikRingen/SCI_2025/blob/main/homeworks/HW8_solutions.qmd)
| Week 11: Multilevel Models | 16 May  | Rethinking Ch. 13 (pp. 399-431) | None | [Homework 9](https://github.com/ErikRingen/SCI_2025/blob/main/homeworks/HW9.pdf); [Solutions](https://github.com/ErikRingen/SCI_2025/blob/main/homeworks/HW9_solutions.qmd)
| Week 12: Gaussian Processes & Generalized Additive Models | 23 May | Rethinking Ch. 14 (pp. 435-485) | | No homework

## Prerequisites

The mathematical pre-reqs for this course are light. I assume that you have taken high-school level algebra and are comfortable with plotting functions in a Cartesian plane e.g., y = mx + b and understand basic descriptive statistics/data visualizations such as scatterplots, histograms.

On the coding side, *I highly reccomend that you have some experience programming in R*, because it is very challening to learn the modelling and programming for the first time simulataneously. You do not need to be an expert, but should have a minimum 1 semester worth of experience in R to get the most out of this course.

## Graded components

If you are taking this course for ECTS credits, there are two graded components: (1) weekly homework exercises to assess your understanding of the materials, worth 75% of your grade and (2) class participation where you will be asked to give a brief (1-2 minute) summary/reflection of the the weeks' materials and pose a question or two for the class to discuss, worth 25% of your grade. The latter will be done pseudo-randomly, such that *you will not know in advance whether it is one of your weeks to summarise*.

Grading for each homework and class participation is done on a simple three-point scale: 

0 - Incomplete
1 - Unsatisfactory
2 - Satisfactory

The overall course is pass/fail, with 65/100 gradepoints needed to recieve ECTS credits.

## Homework

Homeworks are always due before our Friday class meetings, and must be submitted to Erik via email (ringen.erik@gmail.com). You may use whatever format you wish for the submissions, e.g., R/quarto markdown, R scripts, Microsoft Word, PDF. But you *must* use the following naming convention for your submissions:

lastname-HW-number.extension

So, if Erik was to make a submission for the first homework using a PDF report he would name his file:

ringen-HW-1.pdf

## Contact

Please send all questions and homework submissions to ringen.erik@gmail.com.

## Office Hours

Office hours with Erik are available by request.

## Additional Resources

Adjustment via Propensity Scores & Inverse Treatment Weights: https://www.andrewheiss.com/blog/2021/12/18/bayesian-propensity-scores-weights/
Adjustment via Matching Methods: https://www.andrewheiss.com/blog/2020/02/25/closing-backdoors-dags/#adjustment-using-matching-with-mahalanobis-distance

Neuroscience + causal inference: https://www.sciencedirect.com/science/article/pii/S1878929324001269

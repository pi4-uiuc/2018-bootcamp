---
title: "Syllabus"
date: "2018-05-15"
output:
  blogdown::html_page:
    toc: "true"
---


## Instructor: 

_David LeBauer, Ph.D._  
University of Illinois     
email:[dlebauer@illinois.edu](mailto:dlebauer@illinois.edu)  
web: [davidlebauer.com](https://www.davidlebauer.com)

## Course Objectives

A two week course designed to introduce graduate students from the Department of Mathematics to methods in software development, data science, and analysis. The goal is to prepare students to apply their understanding of math to solve problems in industry.

## Requirements

### Code of Conduct

All participants must read and abide by our [Code of Conduct](https://github.com/pi4-uiuc/2018-bootcamp/blob/master/CODE_OF_CONDUCT.md).


### Preparation 

Please do the following **before class starts**:

1. Create an account at github.com
2. Fill out the [pre-workshop survey](https://goo.gl/forms/GSS1Cngrzpn292c23)
3. Signup for the [PI4 Slack channel](https://pi4uiuc.slack.com/signup) (requires email ending in illinois.edu or hawaii.edu email address)
4. Complete "Introduction to R" and "Intermediate R" courses on Data Camp (I will send invitations)

### Expectation: Familarity with basic syntax and operations in R

Although the course is aimed at students with limited experience using software, you are expected to complete two introductory courses in order to become familiar with the basic syntax and operations in R. Two free courses from DataCamp are **Required** before the start of the second day (May 22) of the course.

### Materials: Computers and Software 

The only software requirement is a modern web browser. The classroom is equiped with desktop computers, though students are encouraged to bring laptops. Much of the instruction and collaborative work will be done using the NDS Labs Workbench. The NDS labs workbench provides Shell, R, and Python editors as well as access to large datasets and databases.

## Logistics

### Location: 

239 [Altgeld Hall](https://en.wikipedia.org/wiki/Altgeld_Hall)  
University of Illinois Department of Mathematics  
1409 West Green Street  
Urbana, Il  

#### Time: 9AM - 5PM

We will have two fifteen minute breaks and a one hour lunch break from 12-1, each day for lunch.

#### Dates: May 21 -- May 26, 2018

* May 21: Scientific Computing Fundamentals
* May 22 -- May 25: Data and Statistics in R
* May 26: Conclusion and Project Presentations

#### Daily Schedule:

| Time | Activity |
|:---|:---|
| 9:00--9:30 | Review, questions, overview |
| 9:30--10:30 | Topic 1 | 
| 10:45--11:00 | Break | 
| 11:00--12:00 | Group Projects |
| 12:00--1:00 | Lunch |
| 1:00--2:00 | Topic 2 | 
| 2:00--3:00 | Topic 3 |
| 3:00--3:15 | Break | 
| 3:15--5:00 | Group Projects | 

## Course Schedule

The following schedule is subject to change based on student feedback and interests.

### Day 1: Computing Fundamentals

Monday May 21

1. The Terminal [SWC The Unix Shell](http://swcarpentry.github.io/shell-novice/))
   * file system navigation
   * scripting
   * control flow
2. Version Control [SWC Git Novice 1-6](http://swcarpentry.github.io/git-novice/)
   * commiting changes
   * branching
   * merging
4.  Collaborative Coding [SWC Git Novice 7-14](http://swcarpentry.github.io/git-novice/)
    * GitHub
    * Code Reviews
3. Software Development
   * Reproducible Research
   * Agile / Scrum
5. Group Projects: Setup
   * Overview of available data
   * Overview of scientific questions 
   * Divide into Teams
   * Setup GitHub repository
   * Formulate projects

### Day 2: Getting started with R

Tuesday May 22

1. [Getting Started with R and Rstudio (SWC 1-3)](http://swcarpentry.github.io/r-novice-gapminder/01-rstudio-intro/)
2. Rmarkdown and Reproducible Research 
2. Loading and Evaluating Data
   * data types
   * [vectorization](http://swcarpentry.github.io/r-novice-gapminder/09-vectorization/)
3. Control Flow (if, else, for) [SWC 7](http://swcarpentry.github.io/r-novice-gapminder/07-control-flow/)
4. Visualization [SWC 8](http://swcarpentry.github.io/r-novice-gapminder/08-plot-ggplot2/)
5. Data Manipulation
   * [filtering, subsetting, summarizing, new variables with dplyr](http://swcarpentry.github.io/r-novice-gapminder/13-dplyr/)
   * [Converting data from wide to long with tidyr](http://swcarpentry.github.io/r-novice-gapminder/14-tidyr/)
6. Project 
   * import, and explore data
   * exploratory data analysis 
   * summarize and next steps

The first half of the day will follow the R Novice Gapminder lesson http://swcarpentry.github.io/r-novice-gapminder/

### Day 3: Databases and Visualization

Wednesday May 31 

4. Data Cleaning and Exploratory Analysis
   * Data Cleaning with Open Refine [DC lesson 1-4](http://www.datacarpentry.org/OpenRefine-ecology-lesson/)
   * Data Cleaning in R
   * Scatter Plots
1. Data structures
   * Spreadsheets [DC lesson](http://www.datacarpentry.org/spreadsheet-ecology-lesson/)
   * Relational Databases
   * non-relational databases
   * Raster data and databases
2. Querying databases
   * SQL
   * Connecting from R using the dplyr package
5. Data Curation
   * Metadata and Vocabularies
   * Publishing Data, Archives and Repositories
3. Visualization
   * bestiary of plots, which plots for which data
   * Turning tables into graphs [Gelman et al 2002](http://www.tandfonline.com/doi/abs/10.1198/000313002317572790)
   * Beyond Bar and line graphs [Weissgerber et al 2015](http://journals.plos.org/plosbiology/article?id=10.1371/journal.pbio.1002128)
   * Tufte, sparklines 
4. Project: 
  * more plots
  * summary of available data


### Day 4: Probability and Statistics

Thursday June 1

1. Probability Distributions
   * Bestiary, meaning, PDFs (Bolker Ch4, [Dietze EE509](https://github.com/mdietze/EE509/blob/master/Exercise_02_Distributions.Rmd))
   * Stochastic Simulation (Bolker Ch5)
2. Summary statistics
   * Estimates of central tendency, variance, shape
   * Fitting PDFs - 
      * parameter estimation 
      * goodness of fit (_L_, [A,B,D,]IC)
3. Statistical Modeling
   * Regression
   * Functions
   * Dynamic Models
4. Projects
   * Develop and apply QA/QC metrics
   * Make sure reports can be automated
   
### Day 5

Friday June 2

1. Model Building
   * Descriptive Analysis
   * Hypothesis Driven Analysis
4. Model Fitting 
   * Frequentist, Bayesian
   * Inference and Prediction
6. Multilevel modeling
   * ANOVA ([Gelman et al 2005](https://projecteuclid.org/download/pdfview_1/euclid.aos/1112967698))
   * GLM
   * HB
  
### Day 6: Project Wrapup and Presentations

Saturday May 26

* Student-requested topics
  * more details from earlier topic (advanced visualization?)
  * Shiny apps
  * dimensionality reduction and clustering?
* Finish projects
* Presentations
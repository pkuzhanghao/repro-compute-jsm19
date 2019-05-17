# Reproducible Computing

Short-course at [ISBA 2018](https://bayesian.org/isba2018/Short-Courses/)  
2018-06-24  
9am - 5pm

## Abstract

Success in statistics and data science is dependent on the development of both analytical and computational skills. This workshop will cover:

- Recognizing the problems that reproducible research helps address.
- Identifying pain points in getting your analysis to be reproducible.
- The role of documentation, sharing, version control, automation, and organization in making your research more reproducible.
- Introducing tools to solve these problems, specifically R, RStudio, RMarkdown, git, GitHub, and make.
- Strategies for scaling these tools and methods for larger more complex projects.

Workshop attendees will work through several exercises and get first-hand experience with using relevant tool-chains and techniques, including R/RStudio, literate programming with R Markdown, automation with make, and collaboration and version control with git/GitHub.

## Schedule - TBD

<!--
| Time          | Activity                                |
|:--------------|:----------------------------------------|
| 09:00 - 09:20 | [Welcome](https://htmlpreview.github.io/?https://github.com/mine-cetinkaya-rundel/repro-compute-isba18/blob/master/00-welcome/00-welcome.html)       |  
| 09:20 - 10:00 | [Literate programming](https://htmlpreview.github.io/?https://github.com/mine-cetinkaya-rundel/repro-compute-isba18/blob/master/01-lit-program/01-lit-program.html)  |
| 10:00 - 10:30 | [Naming](https://htmlpreview.github.io/?https://github.com/mine-cetinkaya-rundel/repro-compute-isba18/blob/master/02-naming/02-naming.html)          |
| 10:30 - 11:00 | *Coffee break*                          |
| 11:00 - 11:30 | [Organization](https://htmlpreview.github.io/?https://github.com/mine-cetinkaya-rundel/repro-compute-isba18/blob/master/03-organization/03-organization.html)        |
| 11:00 - 12:30 | [Version control with Git and GitHub](https://htmlpreview.github.io/?https://github.com/mine-cetinkaya-rundel/repro-compute-isba18/blob/master/04-git/04-git.html) |
| 12:30 - 14:00 | *Lunch break*                           |
| 14:00 - 14:45 | [Scaling reproducible projects](https://htmlpreview.github.io/?https://github.com/mine-cetinkaya-rundel/repro-compute-isba18/blob/master/05-scaling/05-scaling.html)                         |
| 14:40 - 15:30 | [Introduction to make](https://htmlpreview.github.io/?https://github.com/mine-cetinkaya-rundel/repro-compute-isba18/blob/master/06-make/06-make.html)          |
| 15:30 - 16:00 | *Coffee break*                          |
| 16:00 - 16:45 | make in action                          |
| 16:45 - 17:00 | [Parting remarks](https://htmlpreview.github.io/?https://github.com/mine-cetinkaya-rundel/repro-compute-isba18/blob/master/08-parting-remarks/08-parting-remarks.html)  |

-->

### Welcome, literate programming, and naming

- Recognize the problems that reproducible research helps address and identify 
pain points in getting your analysis to be reproducible.
- The role of documentation, sharing, automation, and organization in making 
your research more reproducible.
- Literate programming with R Markdown
  - Introduce the data: World Cup!
  - Hands on activity: Updating an analysis when the source data changes
- Naming best practices

### Organization and version control with Git and GitHub

- Project organization
  - File and folder organization for projects
  - Naming conventions
- What is Git and version control?
- Git in GitHub
  - Define git vocabulary (commit, fork, pull request, repository, commit 
  message).
  - Demonstrate ability to navigate through a Github repository main page.
  - Define the difference between a directory and a repository.
  - Create a repository on GitHub.
  - Demonstrate ability to commit changes to text files with a commit message.
  - Evaluate repository History.
  - Create a pull request to someone else's repository.
- Git in RStudio
  - Define git vocabulary (push, fork, local repository, remote repository)
  - Fork remote repository from Github into RStudio.
  - Navigate through the basics of using git in RStudio.
  - Push local repository from RStudio to Github.
  - Demonstrate the ability to host code from RStudio to Github.

### Scaling reproducible projects + Make 

- Practical example - Scottish lip cancer
  - Reproducible R Markdown document with "full Bayesian analysis" including data munging, EDA, model fitting and analysis.
- Caching as a solution to scaling
  - Build your own cache: Saving your own results with `save()` vs. `saveRDS()`
  - R Markdown caching: `cache = TRUE`
- Using make to automate and scale
  - Introduce make
  - Review make syntax
  - Introduce hands on exerciseß



## Computing requirements

- R - 3.5.0
- [RStudio](https://www.rstudio.com/products/rstudio/download/preview/) - 1.2.707 or higher
- git
  - OSX - install Git for Mac by downloading and running the xcode installer or install homebrew and use it to install git via `brew install git`.
  - Unix / Linux - you should be able to install git via your prefered package manager (e.g. apt, dnf, yum).
  - Windows - install [Git for Windows](https://gitforwindows.org/). This will provide you with git, the bash shell, and ssh in windows.
- System libraries and packages (including development headers):
  - jags
  - geos
  - gdal
  - proj
  - texlive
  - udunits2
- R packages (from CRAN):
    - tidyverse
    - rmarkdown
    - shiny
    - rjags
    - rstan
    - sf
    - tidybayes
    - ggplot2

## Instructors

**[Colin Rundel](http://www2.stat.duke.edu/~cr173/)** - Duke University

Colin is a Assistant Professor of the Practice in the Department of Statistical Science at Duke University where he has developed and taught a number of Statistical Computing courses for undergraduate, master's and Ph.D. levels students. His pedagogical and research interests are in the area of statistical computing, data science, and spatial statistics.
## Acknowledgements

- Naming, organization, and version control sections are derived from [Data Carpentry](https://github.com/datacarpentry)'s corresponding modules.
- [Happy git with R](http://happygitwithr.com/) by [Jenny Bryan](http://github.com/jennybc).

## License

Materials in this repository are licensed under [CC Attribution 4.0 International](LICENSE.md).

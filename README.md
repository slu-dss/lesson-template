# lesson-template <img src="/img/logo.png" align="right" />
[![](https://img.shields.io/badge/lesson%20status-under%20development-red.svg)](https://github.com/slu-dss/lesson-template/)
[![](https://img.shields.io/github/release/slu-dss/lesson-template.svg?label=version)](https://github.com/slu-dss/lesson-template/releases)
[![](https://img.shields.io/github/last-commit/slu-dss/lesson-template.svg)](https://github.com/slu-dss/lesson-template/commits/master)

## Lesson Overview
This repository models the layout of a SLU DSS lesson. An overview of our lesson structure is available from the lesson's associated [slides](https://slu-dss.github.io/lesson-template/). Additional details are avilable from this repository's [wiki](https://github.com/slu-dss/lesson-template/wiki).

### Objectives
At the end of this lesson, participants should be able to:

1. Locate the key elements of a SLU DSS lesson within a lesson repository.
2. Describe the purposes of each key element.
3. Employ RStudio to update a lesson.

### Dependencies
This lesson requires the following `R` packages from CRAN:
- [`devtools`](https://github.com/r-lib/devtools)
- [`knitr`](https://yihui.name/knitr/)
- [`RMarkdown`](https://rmarkdown.rstudio.com)

To install a package from CRAN, type the following into your console:

```r
install.packages("devtools")
```

This lesson requires the following `R` packages from GitHub:
- [`xaringan`](https://github.com/yihui/xaringan)

To install a package from GitHub using `devtools`, type the following into your console:

```r
devtools::install_github("yihui/xaringan")
```

### Repository Contents
This repository contains files for:
- `docs/` - lesson slides, which can be seen [here](https://slu-dss.github.io/lesson-template/)
- `img` - image files associated with the lesson
- `lesson-template.Rproj` - R project for lesson
- `.gitignore`
- `LICENSE`
- `README.md` - seminar resources

### Resources
< This should be a bulleted list of online resources that are connected to the material covered in the lesson. >

## About the SLU DSS
### < DSS Seminar >
< seminar description >

### About the SLU Data Science Seminar
The [SLU Data Science Seminar](https://slu-dss.githb.io) (DSS) is a collaborative, interdisciplinary group at Saint Louis University focused on building researchers’ data science skills using open source software. We currently host seminars focused on the programming language R. The SLU DSS is co-organized by [Christina Gacia, Ph.D.](mailto:christina.garcia@slu.edu), [Kelly Lovejoy, Ph.D.](mailto:kelly.lovejoy@slu.edu@slu.edu), and [Christopher Prener, Ph.D.](mailto:chris.prener@slu.edu}). You can keep up with us here on GitHub, on our [website](https://slu-dss.githb.io), and on [Twitter](https://twitter.com/SLUDSS).

### About Saint Louis University <img src="/img/sluLogo.png" align="right" />
Founded in 1818, [Saint Louis University](http://www.slu.edu) is one of the nation’s oldest and most prestigious Catholic institutions. Rooted in Jesuit values and its pioneering history as the first university west of the Mississippi River, SLU offers nearly 13,000 students a rigorous, transformative education of the whole person. At the core of the University’s diverse community of scholars is SLU’s service-focused mission, which challenges and prepares students to make the world a better, more just place.


---
title: "03 Zotero history and open science practices"
teaching: 10
exercises: 2
---

 Lorem ipsum dolor sit amet, consectetur adipiscing elit. Ut ligula urna, accumsan nec venenatis quis, cursus ac mi. Praesent lacinia eros a mi gravida, vel varius dui consequat. Vestibulum ipsum ante, luctus eget arcu non, consectetur pulvinar metus. Vestibulum ante ipsum primis in faucibus orci luctus et ultrices posuere cubilia curae; Sed venenatis nulla id magna condimentum, porttitor mattis ligula aliquam. Nulla sodales nulla et dui malesuada, vel venenatis sem dapibus. Donec vehicula dolor vitae ipsum sodales, in laoreet libero sodales. Duis rutrum, eros a accumsan sagittis, sem purus imperdiet quam, sed faucibus leo lorem nec leo. Quisque ullamcorper convallis massa, vel rhoncus eros porttitor non. Nulla ultricies elit bibendum justo posuere, vitae porttitor elit faucibus.

Duis sit amet vehicula ex. Etiam volutpat leo nec velit fringilla, ut facilisis ante rhoncus. Nulla ultricies libero felis, sit amet vulputate neque pharetra sed. Nullam tristique, enim sed tincidunt blandit, augue purus lacinia leo, a ultrices metus sapien pellentesque ante. Morbi vitae leo sit amet dui sodales scelerisque vitae et nunc. Fusce sodales imperdiet eleifend. Aenean mattis auctor viverra. Praesent quis tincidunt nunc. 

:::::::::::::::::::::::::::::::::::::: questions 

- What is characteristic with open digital science?

::::::::::::::::::::::::::::::::::::::::::::::::

::::::::::::::::::::::::::::::::::::: objectives

- Knowing how Zotero can ease cooperation in study groups or research groups.

::::::::::::::::::::::::::::::::::::::::::::::::

## Introduction

This is a lesson created via The Carpentries Workbench. It is written in
[Pandoc-flavored Markdown](https://pandoc.org/MANUAL.txt) for static files and
[R Markdown][r-markdown] for dynamic files that can render code into output. 
Please refer to the [Zotero]([https://www.zotero.org/support/] for full documentation.

What you need to know is that there are three sections required for a valid
Carpentries lesson:

 1. `questions` are displayed at the beginning of the episode to prime the
    learner for the content.
 2. `objectives` are the learning objectives for an episode displayed with
    the questions.
 3. `keypoints` are displayed at the end of the episode to reinforce the
    objectives.

:::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::: instructor

Inline instructor notes can help inform instructors of timing challenges
associated with the lessons. They appear in the "Instructor View"

::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::

::::::::::::::::::::::::::::::::::::: challenge 

## Challenge 1: Can you do it?

Did you ever use a reference manager integrated into a text editor

a) no, I used only the reference manager itself

b) I Use Word and Zotero. I am an advanced user


```r
paste("This", "new", "lesson", "looks", "good")
```

:::::::::::::::::::::::: solution 

## Output
 
```output
[1] The answer will soon be: b) I Use Word and Zotero. I am an advanced user
```

:::::::::::::::::::::::::::::::::


## Challenge 2: how do you nest solutions within challenge blocks?

:::::::::::::::::::::::: solution 

You can add a line with at least three colons and a `solution` tag.

:::::::::::::::::::::::::::::::::
::::::::::::::::::::::::::::::::::::::::::::::::

## Figures

You can use standard markdown for static figures with the following syntax:

`![optional caption that appears below the figure](figure url){alt='alt text for
accessibility purposes'}`

![You belong in The Carpentries!](https://raw.githubusercontent.com/carpentries/logo/master/Badge_Carpentries.svg){alt='Blue Carpentries hex person logo with no text.'}

## Math

One of our episodes contains $\LaTeX$ equations when describing how to create
dynamic reports with {knitr}, so we now use mathjax to describe this:

`$\alpha = \dfrac{1}{(1 - \beta)^2}$` becomes: $\alpha = \dfrac{1}{(1 - \beta)^2}$

Cool, right?

::::::::::::::::::::::::::::::::::::: keypoints 

- Use `.md` files for episodes when you want static content
- Use `.Rmd` files for episodes when you need to generate output
- Run `sandpaper::check_lesson()` to identify any issues with your lesson
- Run `sandpaper::build_lesson()` to preview your lesson locally

::::::::::::::::::::::::::::::::::::::::::::::::

[r-markdown]: https://rmarkdown.rstudio.com/

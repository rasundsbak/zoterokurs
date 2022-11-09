---
title: "04 Mapping your archive"
teaching: 10
exercises: 2
---
**Creating the overview through SR Accelerator**
Now that we already have a big archive with literature on a specific research area, it will be useful to apply some tools for getting a qiuck overview of the material.  Go to the Zotero folder where you have the literature on the water management question, or the research question you chose. Export the collection in an .ris file and put it somewhere in your folder locations so that you know how to find it again. Go to the web page SR Accelerator and choose WordFreq from the left hand menu. Upload the .ris file that you made. Do you see any unexpected terms in your data? Are there any terms that you would expect to have a greater frequency?

**Making the folders talk**
You may now go back to your archive and look for the possibility of making 

Right click "my library" to the left, and make --> new saved search. Make a folder with 000 and the term as a name, like this 000Drought. See that the folder takes up all of the literature with the relevant term. then check the number and rename the folder so that the number before the term is right. The name of the folder should look something like this 040Drought, and current number of references containing the terms. 

:::::::::::::::::::::::::::::::::::::: questions 

- What is characteristic with open digital science?

::::::::::::::::::::::::::::::::::::::::::::::::

::::::::::::::::::::::::::::::::::::: objectives

- organizing and mapping a large amount of references
- knowing how Zotero can ease cooperation in study groups or research groups

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

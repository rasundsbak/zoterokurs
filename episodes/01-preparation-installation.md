---
title: "Preparation and installation"
teaching: 10
exercises: 2
---
## Code of Conduct

To make clear what is expected, 
everyone participating in The Carpentries activities is required to abide by our 
[Code of Conduct](../CODE_OF_CONDUCT.md). 
Any form of behaviour to exclude, intimidate, 
or cause discomfort is a violation of the Code of Conduct. 
In order to foster a positive and professional learning environment we encourage you to:  

* Use welcoming and inclusive language
* Be respectful of different viewpoints and experiences
* Gracefully accept constructive criticism
* Focus on what is best for the community
* Show courtesy and respect towards other community members

If you believe someone is violating the Code of Conduct,
we ask that you report it to The Carpentries Code of Conduct Committee 
by completing [this form](https://goo.gl/forms/KoUfO53Za3apOuOK2).

## Zotero, Zotero Connector, Zutilo, Better Bibtex for Zotero, Better notes for Zotero and text editing in R Cloud
Go to Zotero.org and download the relevant Zotero desktop version and connector for your PC, Mac or Linux machine. We are going to use Zutillo add-on to Zotero and SR Accelerator in order to get an overview of our field of research.

Download the zutilo. xpi file from Zutilo's GitHub releases page. Then go to Tools-> Add-ons in Zotero. Click on the gear button in the upper right area of the Add-ons Manager window and install the Add-on from the file. Then select the downloaded zutilo. Note that this should not be done in Mozilla. Most other web browsers should work. Do same procedure with Better notes for Zotero and Better bibtex for zotero.

You will need a google account, or a GitHub account in order to be able to use the cloud service of RStudio called Posit. If you need digital privacy, you may download R and R Studio to your desktop instead. In this case, you do not have to make a user id for login.

**Academic preparation**
In this course we have an academic problem that is used for learning the method: 
"Water scarcity or floods are increasingly a problem during the anthropocene. How is this problem solved in varouis regions, and what has the scientific community suggested in previous research?"

However, feel free to limit the scope of the problem, or use your own academic problem in episode 2. You must be able to easily find at least 500 references treating the chosen subject. We do this in order to simulate how to easily get an overview over a relatively good search on the literature on the chosen subject.

**Check the functionality**
After the installation. Check your usual text editor. For Word users: Do you see the tab for Zotero functionality somewhere to the right? If not, you may use googles solution:

**Zotero tab does not appear in the Word Ribbon**
Open the Templates and Add-ins window by going to File → Options → Add-ins, selecting “Word Add-ins” in the Manage drop-down at the bottom, and clicking “Go…”. Then, make sure Zotero.dotm is present and ticked.

Zotero supports the text editors Google Docs, Microsoft Word and Libre Office.

**Installing the Zotero Word Processor Plugins**
Vitit this site: https://www.zotero.org/support/word_processor_plugin_installation

:::::::::::::::::::::::::::::::::::::: questions

- How do you write a lesson using Markdown and `{sandpaper}`?

::::::::::::::::::::::::::::::::::::::::::::::::

::::::::::::::::::::::::::::::::::::: objectives

- Have all the installations ready on your PC/ Mac
- Be technically ready to start working with Zotero

::::::::::::::::::::::::::::::::::::::::::::::::

## Introduction

This is a lesson created via The Carpentries Workbench. It is written in
[Pandoc-flavored Markdown](https://pandoc.org/MANUAL.txt) for static files and
[R Markdown][r-markdown] for dynamic files that can render code into output. 
Please refer to the [Introduction to The Carpentries 
Workbench](https://carpentries.github.io/sandpaper-docs/) for full documentation.

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



How did you organize your references the last time you wrote an assignment?

a) Endnote

b) I did it manually

c) Zotero

:::::::::::::::::::::::: solution 

## Output
 
the right answer should be c) Zotero

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

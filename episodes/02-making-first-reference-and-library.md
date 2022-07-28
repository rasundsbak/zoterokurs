---
title: "Making the first manual reference and library"
teaching: 10
exercises: 2
---

**Making a manual reference**
In zotero desktop, choose file --> New item --> Book

Insert the data for this book:

Title: Behave: The Biology of Humans at Our Best and Worst 
Format: Hardcover – Illustrated, May 2, 2017
by Robert M. Sapolsky (Author)

**Making a Library**
Go to Zotero and klick New library--> New Group. This will send you to the Zotero cloud solution. Make your own username and password. Find an adeqate group name, and go back to the desktop to see how it now looks.

**Syncing**
Go to Edit--> Preferences --> Sync, and enter the data for your account. Check that the syncing works. You should now have a new group in your library.

**Download single articles**
Open this website https://doi.org/10.1016/j.aopr.2022.100065 and click on the zotero icon in your browser. Check that everything is downloaded correctly in the Zotero app, and then cite the source in the text editor, and make a bibliography. 
Next, open these articles https://doi.org/10.1016/j.aopr.2022.100065 , https://doi.org/10.1038/s41467-022-30091-3 , click on the zotero icon and check everything is correctly downloaded into the Zotero app. The last one we want in the library is a random open access book https://link.springer.com/content/pdf/10.1007/978-94-024-1720-3.pdf , click on the PDF icon where Zotero icon normally are. Check the item in the zotero app.

**Downloading references from research databases**
There are various for profit databases held in subscriptions by the University Libraries. We reccomend trying these, if you have the possibility. In this course the main focus will be on Open Acess resources. Download references from [Dag Hammarskjöld Library](https://www.un.org/en/library/page/databases), [ScienceOpen.com](https://www.scienceopen.com/) and [Directory of Open Access Journals](https://doaj.org/). If you do not have your own academic problem, you may use this one:

"Many people in the world live with water scarcity. How is this problem solved in varouis regions, and what has the scientific community suggested in previous research?"

Try to downlowd at least 500 references directly to your new group. Find the export solution for the relevant database. We recommend the RIS format for Zotero. Open/ import the file in Zotero. Put the references in the group you made.

Look at your references, mark 20 of them, and use the function "find pdf". use "fn lock" to mark several references, for instance 10 --> right click --> Find available pdfs. This solution will work better it you are on a university campus with subscriptions to academic journals. If using it from the home office, it will import open access resources.

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



How did you organize your references the last time you wrote an assignment.

a) Endnore

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

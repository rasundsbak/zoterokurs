---
title: "03 The academic writing process - Zotero and text editors"
teaching: 10
exercises: 2
---
**Using Zotero with a text editor**
Open R-cloud when Zotero run. Log into Zotero to generate Zotero Web API https://www.zotero.org/settings/keys/new . Name this key for example Rmarkdown and generate key. Go to R-markdown an click on Tools, Rmarkdown, Citations, paste in the citation key from Zotero. Then go to Tools, Project options, Rmarkdown, select zotero libraries.

Then copy and paste an example text from the Lorem ipsum generator.
url: https://www.lipsum.com/

Save your file somewhere so that you know where to find it.

**Storing your data in a good way**
When working with text and files, it is important to know how and where to store them. Most universities offer protected storage drives at their networks. This makes students and reaearchers able to store their data in an adequate way. Often these storage places come with high quality backup. Familiarize yourself with the recommendations of your home institution. Check out the available platforms of storage. You should know the difference between these storage platforms
- Private OneDrive
- Institutional OneDrive
- Office 365
- local harddrive (C:)
- personal network storage on campus (M:)

There are other storage places too, but the above are the most important.

**File structure and file names**
Your data should be organizes with folders and sub folders that make it easy to fing your data, even in the future, when you have stopped working with the project. Store versions and backup in an appropriate and orderly way. Use the right kind of filenames, where you avoid space bar and special characters. Rememver the dot means the file ending is coming, and avoid the wrong use of period in the file name.

**Save your document**
Save your document in a way that takes the above mentioned into account. Check that you have both Zotero and your text editor open. Experiment with taking in text references. Put in several text references. Make the bibliography. How do you take in page numbers to your references?


:::::::::::::::::::::::::::::::::::::: questions 

- How do you write a lesson using Markdown and `{sandpaper}`?

::::::::::::::::::::::::::::::::::::::::::::::::

::::::::::::::::::::::::::::::::::::: objectives

- Know how to integrate zotero into your own usual workflow, with your favourite text editor
- Importing bibliographic data
- Placing text references
- Backup
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

You want to send your manuscript to a journal that tell you to follow these style: 
Referansene skal følge Harvard Style of Referencing. Referansene i teksten skal være som følger ved
henholdsvis en, to og flere forfattere: «…Meland (2010), Bårdsen og Nymoen (2011), Finstad mfl.
(2002)…». Referanser i parentes skrives som følger: «… (Finstad mfl., 2002; Meland, 2010)…».
g. Referanselisten skal ha overskriften REFERANSER og ha følgende format:
Melberg, H. O. (2010). Animal spirit: Fargerik tomhet? Samfunnsøkonomen 64 (2), 4–10.
Bårdsen, G. og R. Nymoen (2011). Innføring i økonometri. Fakbokforlaget, Bergen.
Finstad, A., G. Haakonsen og K. Rypdal (2002). Utslipp til luft av dioksiner i Norge – Dokumentasjon av
metode og resultater. Rapporter 2002/7, Statistisk sentralbyrå.

How can you do that?

```r
paste("This", "new", "lesson", "looks", "good")
```

:::::::::::::::::::::::: Solution
Take a copy of the document, in the copy go to "Unlink citations" in the Zotero menu, use the Find and Replace function in the text editor and replace the et al. with mfl., then correct the paranthesis, and fill in the Place of publication. It depend if you have used the APA style or Cite Them Right.Try different styles in Zotero "Document preferences".

## Output
 
```output
[1] "This new lesson looks good"
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

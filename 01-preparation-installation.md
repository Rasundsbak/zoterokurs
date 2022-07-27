---
title: "01 Preparation and installation"
teaching: 10
exercises: 2
---
**Code of conduct**
https://rasundsbak.github.io/zoterokurs/CODE_OF_CONDUCT.html

**Desktop and Zotero Connector**
Visit Zotero.org and download the relevant Zotero desktop version and connector for your PC, Mac or Linux machine. We are also going to use Zutillo and SA Accelerator in order to get som overview over our field of research

**Academic preparation**
In this course we have an academic problem that is used for learning the method: 
"Today, many people in the world live with water scarcity. How is this problem solved in varouis regions, and what has the scientific community suggested in previous research?"

However, feel free to use your own academic problem in episode 2. You must be able to easily find at least 500 references treating the chosen subject. We do this in order to get an overview over the literature on the chosen subject.

**Check the functionality**
After the installation. Check your usual text editor. For Word users: Do you see the tab for Zotero functionality somewhere to the right? If not, see below. Zotero supports the text editors Google Docs, Microsoft Word and Libre Office.

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
---
title: Generic Markdown Comic Script
description: --Comic Script Template
author: RJ Cody Markelz
date: 2022-01-20
categories: [comics, art, script, writing, rmarkdown]
image: /images/Ry_On_A_Buffalo_web.jpg
---

A quick post to outline how I create simple comic scripts using markdown and then render them to a PDF.
This is loosely based off of the [Comics Experience Example Script](https://www.comicsexperience.com/scripts/) with some modifications for markdown specific syntax like page-breaks. I like to have each comic page on it's own printed page for editing. This allows room to thumbnail ideas directly on the scripts to workout storytelling ideas.


# Rendering PDFs using rmarkdown
```R
library(knitr)
library(rmarkdown)
setwd("path/to/markdown/file/directory")
list.files()
render("comic-script.md")
```


# rmarkdown formatted comic script example below


```
---
title: "Title with version number: v6.1.1"
author: Author Name
date: January 20, 2022
header-includes:
- \usepackage{fancyhdr}
- \pagestyle{fancy}
- \fancyhead[CO,CE]{STORY NAME -NAME NAMERSON}
- \fancyfoot[CO,CE]{Copyright 2022 - NAME NAMERSON - email@email.com}
- \fancyfoot[LE,RO]{\thepage}
output: pdf_document
---

# Background
STORY SENTENCE -One sentence summary.

CHARACTER 1 BIO - What do they want in the pages?

CHARACTER 2 BIO- What do they want in the pages?


# Story Synopsis
1 paragraph summary of the action/events of the story. Keep it dry and to the point. First sentence is the first page and the last sentence is the last page.

# Contact Info
**Your Name**

email@email.com

[www.codymarkelz.com](www.codymarkelz.com)



\pagebreak

# PAGE ONE- SIX PANELS
One sentence page summary.

## PANEL 1
Panel description of single action, dialogue, sound effects SFX.

## PANEL 2
Panel description of single action, dialogue, sound effects SFX.

1. **CHARACTER 1**: statement and dialogue.

## PANEL 3
Panel description of single action, dialogue, sound effects SFX.

1. **CHARACTER 1**: statement and dialogue.

## PANEL 4
Panel description of single action, dialogue, sound effects SFX.

## PANEL 5
Panel description of single action, dialogue, sound effects SFX.

1. **CHARACTER 1**: dialogue!

## PANEL 6
Panel description of single action, dialogue, sound effects SFX.

1. **CHARACTER 2**: **winded** dialogue!

**SFX** WHOOOMPF!



\pagebreak

#  PAGE TWO- THREE PANELS
One sentence page summary.

## PANEL 1
Panel description of single action, dialogue, sound effects SFX.

## PANEL 2
Panel description of single action, dialogue, sound effects SFX.

## PANEL 3
Panel description of single action, dialogue, sound effects SFX.
```

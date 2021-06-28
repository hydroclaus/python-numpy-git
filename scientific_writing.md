# Notes on Scientific Writing

version 1; Stuttgart; 2021-Mar-02

While editing a few written works recently, a few things struck me again and again. Things that are not related to the scientific topic, but related to writing. I tried to note them down – please have a look! I'm happy for feedback (also, it's an open repository, so you could practice also your git skills)!

- If you are related to the University of Stuttgart: there is writing Support: [Writing Center](https://www.sz.uni-stuttgart.de/en/writing_center/mainpage/)

- be consistent, with everything, as much as you can
    - if you say something is called "sand", always call it sand, and not "sand" in the beginning and then "clayey sand" from page 87 on.
    - if you use an abbreviation for something, always use this abbreviation from then on. Do not use another abbreviation from some point on
	- the search and replace functionality in your texteditor make this relatively easy.

- style
    - each sentence should be following logically from the previous sentence. Sentences that belong together form a paragraph. Each paragraph should contain one line of thought. This logical order, where everything builds sequentially on the previous building stone, makes it easier for the reader to follow (the "rote Faden" is easily visible then; your text is not "fadenscheinig").
    - I found that many students start with "Figure X shows Y". Then they continue with the next figure. Instead, the text becomes much more convincing when you state your hypothesis, then explain what you did  to test the hypothesis (experiment, simulation) and then explain what you observed. The figures are there to help to make the point or to make the point clearer. They do not make the point by themselves!
    - Additionally, I like to know where we are going in a chapter or a section. What is this section's aim?
    - avoid filling words ("also", ...)
    - no qualifiers ("very", "excellent", ...); instead use numbers to compare "things" (measurements)
    - there is a difference between UK and US [English](http://www.tysto.com/uk-us-spelling-list.html)
    - in English, there is a "[Title case](https://en.wikipedia.org/wiki/Title_case)", and there are tools that convert a text (a heading) consistently
    - something can be seen *on* a figure or *in* a table.
    - "e.g., ..." and "i.e., " -- watch for comma and dots and be consistent
    - weigh your options carefully:
        - "estimate" vs. "predict"
        - when is something "significant" and at what level of significance
    - Generally, the first word of a sentence starts with a capital letter, and at the end of a sentence forms some sort of punctuation, usually a period. While it seems strange that I feel the urge to point this out, history has shown that it is necessary to be pointed out.


- Be carful and consistent with units. In my experience, this works best in Latex using the package [SIunitx](https://www.namsu.de/Extra/pakete/Siunitx.pdf). An example: "*The concentration of Deathylene varies between 11.3⋅10^{-3} mg/L and 12.4⋅10^{-1} mg/L*" [note: the exponents are written here in latex syntax for clarity, but should ultimately be typeset properly, independent of the software you use]
    - units after each number
    - watch significant digits
    - liter: capital "L"
    
- proper citation!
    - there are many resources, for [example this one](http://tim.thorpeallen.net/Courses/Reference/Citations.html)
    - a sentence with a citation should like a proper sentence!
    - "et al." (watch where the dot is)
    - use tools to help (automatically change styles according to needs, be consistent; e.g., Mendeley, EndNote, Citavi, biblatex)
    
    
- there are important symbols (in word, in latex, etc.):
    - [non-breaking hyphen](https://en.wikipedia.org/wiki/Wikipedia:Non-breaking_hyphen)
    - [non-breaking space](https://en.wikipedia.org/wiki/Non-breaking_space) – e.g., between the word "Figure" and the number of the figure, such that the word and the number do not appear on two different lines
    
- commas in English:
    "A panda walks into a bar. He eats, shoots, and leaves" versus "A panda walks into a bar. He eats, shoots and leaves" ([there's a joke, and there's even a book that I like on this issue](https://adeptenglish.com/lessons/english-learn-grammar-7/#eats-shoots-and-leaves-the-joke))


- specials: hydrogeology
    - everything below the water table is the saturated zone. Above the water table, water does still exist, hence it is not unsaturated but variably saturated
    - "aquifer" vs. "high-K zone" -- what is the difference?
    - singular: "porous medium"; plural: "porous media"
    - hydraulic head is the sum of pressure head and elevation head (this is what these terms are called)
	- the Darcy flux q ($q=-K i$; $i$ is the hydraulic gradient $i= \frac{\Delta h}{\Delta l}) is a specific discharge ($q= Q / A$)  = "Filtergeschwindigkeit"
	- the groundwater veocity or seepage velocity ($v = q / \phi$) corrects for the part in the cross-sectional area through which flow can occur = "Abstandsgeschwindigkeit"
    
- tools:
    - [Grammarly](https://www.grammarly.com) (can be used directly in VS code, [extension for VS Code](https://github.com/znck/grammarly))
    - [Writefull](https://writefull.com) (can be used in [overleaf](http://www.overleaf.com))
    
- references:
    - "[The Elements of Style](https://en.wikipedia.org/wiki/The_Elements_of_Style)" by Wiliam Strunk, JR and E.B. White
    - "[Deutsch für Profis](https://www.buecher.de/shop/humor/deutsch-fuer-profis/schneider-wolf/products_products/detail/prod_id/07603956/)" von Wolf Schneider
    - [Writing in the Sciences | Coursera](https://www.coursera.org/learn/sciwrite) by [Kristin Sainani](https://profiles.stanford.edu/kristin-sainani?tab=bio)


## Introduction

Wie ein Trichter, oben breit, unten spitz

- background, known information
- knowledge gap, unknown information
- Hypothesis, question, purpose statement
- approach, plan of attack, proposed solution

Alternative formulation

- What's known
- What's unknown (limitations and gaps in previous studies)
- your burning question / hypothesis / aim
- your experimental approach
- why your experimental approach is new and different and important (fill in the gaps)

## Useful Links
- [10 Simple Steps to Writing a Scientific Paper](https://spie.org/news/photonics-focus/janfeb-2020/how-to-write-a-scientific-paper?SSO=1)
- @Geostatsguy: Every day I review abstracts & papers, for my 12 Ph.D. students, my editor roles & as a reviewer for a variety of journals. Here are some of the common issues that I observe in #technical #writing. Writing is a hard, worthwhile life-long journey. https://twitter.com/GeostatsGuy/status/1285610419504242690?s=20
- [Importance of Editing and Proofreading in Academic Writing - Enago Academy](https://www.enago.com/academy/importance-of-proofreading-and-editing-in-academic-writing/)
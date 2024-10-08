# Notes on Scientific Writing

version 1; Stuttgart; 2021-Mar-02

While editing a few written works recently, a few things struck me again and again. Things that are not related to the scientific topic, but related to writing. I tried to note them down – please have a look! I'm happy for feedback (also, it's an open repository, so you could practice also your git skills)!

- If you are related to the University of Stuttgart: there is writing Support: [Writing Center](https://www.sz.uni-stuttgart.de/en/writing_center/mainpage/)

- How to [construct a summary paragraph](https://cbs.umn.edu/sites/cbs.umn.edu/files/migrated-files/downloads/Annotated_Nature_abstract.pdf)

- I strongly recommend [Writing in the Sciences | Coursera](https://www.coursera.org/learn/sciwrite) by [Kristin Sainani](https://profiles.stanford.edu/kristin-sainani?tab=bio)

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
    - ditch "in order to" for "to" ([youtube](https://www.youtube.com/watch?v=DPOcVojQ0kY))
    - there is a difference between UK and US [English](http://www.tysto.com/uk-us-spelling-list.html)
    - in English, there is a "[Title case](https://en.wikipedia.org/wiki/Title_case)", and there are tools that convert a text (a heading) consistently
    - something can be seen *on* a figure or *in* a table.
    - "e.g., ..." and "i.e., " -- watch for comma and dots and be consistent
    - weigh your options carefully:
        - "estimate" vs. "predict"
        - when is something "significant" and at what level of significance
    - Generally, the first word of a sentence starts with a capital letter, and at the end of a sentence forms some sort of punctuation, usually a period. While it seems strange that I feel the urge to point this out, history has shown that it is necessary to be pointed out.
    - Don't use: "it can be seen" (unless you specify what and where and when), "obviously" and other fill-words. Most of the time, you can delete "also"
    - Don't use: "we could observe". Instead: "we observed", or, if passive voice should be necessary "it was observed".
	- [Stay off gobbledygook language](https://archive.org/details/Maverick1944MemoAboutGobbledygook). The Naval officer who wired "Sighted Sub - Sank Same" told the whole story.

- Be carful and consistent with units. In my experience, this works best in Latex using the package [SIunitx](https://www.namsu.de/Extra/pakete/Siunitx.pdf). An example: "*The concentration of Deathylene varies between 11.3⋅10^{-3} mg/L and 12.4⋅10^{-1} mg/L*" [note: the exponents are written here in latex syntax for clarity, but should ultimately be typeset properly, independent of the software you use (and if you use latex, then use SIunitx)]
    - units after each number
    - watch significant digits
    - liter: capital "L"
    
- proper citation!
    - there are many resources, for [example this one](http://tim.thorpeallen.net/Courses/Reference/Citations.html)
    - a sentence with a citation should read like a proper sentence (place brackets accordingly)!
    - "et al." (watch where the dot is)
    - use tools to help (automatically change styles according to needs, be consistent; e.g., Mendeley, EndNote, Citavi, biblatex, etc.)
    
- there are important symbols (in word, in latex, etc.):
	- dashes/hypens: there are different kinds of dashes:[the "en" and the "em" Dash](https://www.scribbr.com/language-rules/dashes/); both have their [representations in latex](https://tex.stackexchange.com/a/53637).
    - breaking/non-breaking hyphens/spaces:
		- [non-breaking hyphen](https://en.wikipedia.org/wiki/Wikipedia:Non-breaking_hyphen)
    	- [non-breaking space](https://en.wikipedia.org/wiki/Non-breaking_space) – e.g., between the word "Figure" and the number of the figure, such that the word and the number do not appear on two different lines
	- quotation marks: [see here](https://en.wikibooks.org/wiki/LaTeX/Text_Formatting#Quote-marks) and [here](https://de.wikibooks.org/wiki/LaTeX-Wörterbuch:_Anführungszeichen)
    
- commas in English:
    "A panda walks into a bar. He eats, shoots, and leaves" versus "A panda walks into a bar. He eats, shoots and leaves" ([there's a joke, and there's even a book Non this issue](https://adeptenglish.com/lessons/english-learn-grammar-7/#eats-shoots-and-leaves-the-joke))


### Hydrogeology-Specifc Notes
- Generally, you want to refer to "*hydraulic head*" (hydraulische Druckhöhe, but "head" is not equal to Druckhöhe!). Not "head". Also not "piezometric head", as $h= \psi + z$, where $h$ is hydraulic head, $\psi$ is piezometric head, and $z$ is elevation head. In a static water column, without flow, hydraulic head is constant.
- everything below the water table is the saturated zone. Above the water table, water does still exist, hence it is not unsaturated but variably saturated (dependent on the vertical elevation above the water table). Hence, this zone is called the "variably saturated zone" or the "vadose zone".
- think about it: "aquifer" vs. "high-K zone" -- what is the difference?
- singular: "porous medium"; plural: "porous media"
- hydraulic head is the sum of pressure head and elevation head (this is what these terms are called)
- the Darcy flux q ($q=-K i$; $i$ is the hydraulic gradient $i= \frac{\Delta h}{\Delta l}$) is a specific discharge ($q= Q / A$)  = "Filtergeschwindigkeit"
- the groundwater veocity or seepage velocity ($v = q / \phi$) corrects for the part in the cross-sectional area through which flow can occur = "Abstandsgeschwindigkeit"
    
### Other Notes
- tools:
    - [Grammarly](https://www.grammarly.com) (can be used directly in VS code, [extension for VS Code](https://github.com/znck/grammarly))
    - [Writefull](https://writefull.com) (can be used in [overleaf](http://www.overleaf.com))
   
- online ressources:
    - "[Ozdic.com](https://ozdic.com/)" (to find correct word relations and prepositions)
	- "[Manchester Academic Phrasebank](https://www.phrasebank.manchester.ac.uk/)" (comprehensive guide to scientific writing with lots of examples)
	- "[COCA](https://www.english-corpora.org/coca/) (largest corpus of english text; to find word usages and more in academic texts)
	
- references:
    - "[The Elements of Style](https://en.wikipedia.org/wiki/The_Elements_of_Style)" by Wiliam Strunk, JR and E.B. White, [at project Gutenberg](https://gutenberg.org/ebooks/37134)
    - "[Deutsch für Profis](https://www.buecher.de/shop/humor/deutsch-fuer-profis/schneider-wolf/products_products/detail/prod_id/07603956/)" von Wolf Schneider

## The Introduction

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
- [Clinical Chemistry Guide to Scientific Writing](https://www.aacc.org/science-and-research/clinical-chemistry/clinical-chemistry%C2%A0guide-to-scientific-writing#)


## Latex

Scientific Writing in [Latex](https://www.latex-project.org) has advantages
- consistent referencing (to figures, papers, sections in the writing)
- a reasonable system to deal with references is included (bibtex)

There is a relatively nice online tool ([overleaf](https://www.overleaf.com/)) that
- facilitates the compilation of latex online (no need to install latex locally)
- allows for collaboration and sharing

### Tables in latex
- [Typesetting tables in latex](https://tug.org/TUGboat/tb28-3/tb90hoeppner.pdf) and references therein!
- [Small Guide to Making Nice Tables](https://people.inf.ethz.ch/markusp/teaching/guides/guide-tables.pdf)
- [Professional and clean tables with LaTeX – texblog](https://texblog.org/2017/02/06/proper-tables-with-latex/) -- use [booktabs](https://www.ctan.org/pkg/booktabs?lang=en)!

Tools for Tables
- [Create LaTeX tables online – TablesGenerator.com](https://www.tablesgenerator.com/)
- [TableFlip - Simple Table Editor for Mac](https://tableflipapp.com/)
- [Convert Excel to LaTeX Table - Table Convert Online](https://tableconvert.com/excel-to-latex)
- [calc2latex](https://calc2latex.sourceforge.net/) -- from open office calc to latex table
- [Excel2LaTeX](https://www.ctan.org/pkg/excel2latex) -- from ms excel to latex (might be a bit old)

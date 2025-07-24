# Writing Details

Be consistent!

- use the package [`SIUnitX`](https://www.namsu.de/Extra/pakete/Siunitx.html). Examples: A precipitation intensity should be written as `\SI{0.167}{\centi\metre\per\day}`. If you do this, the symbol for a liter will always be a capital `L`, as it should be. You need these two (at least the first) in the preamble:

    \usepackage{siunitx}
    \DeclareSIUnit\year{yr}

- Bulleted Lists
    - Typeset a period (`.`) at the end of each item
    - Start each item with a capital letter
    

Style

- descriptive figure captions are nice.

# Resources
- [Learn LaTeX | learnlatex.org](https://www.learnlatex.org/)
- [Documentation - Overleaf, Online LaTeX Editor](https://www.overleaf.com/learn)

Latex Distibutions (you need this if you want to compile latex locally on your desktop; overleaf maintains this behind the scenes)
- [TeX Live - TeX Users Group](https://tug.org/texlive/)
- [Home](https://miktex.org/)

## Bibliography
- [JabRef - Free Reference Manager - Stay on top of your Literature](https://www.jabref.org/)
- [BibDesk (macOS)](https://bibdesk.sourceforge.io/)
## Other Useful Things
- Markdown: simple alternative to "markup", also supported in jupyter: [Daring Fireball: Markdown](https://daringfireball.net/projects/markdown/)
- [Pandoc - If you need to convert files from one markup format into another, pandoc is your swiss-army knife. Pandoc can convert between the following formats:](https://pandoc.org/)
- [typst/typst: A new markup-based typesetting system that is powerful and easy to learn.](https://github.com/typst/typst)
- A plugin for PowerPoint: [IguanaTex - A Free Latex Add-In for PowerPoint on Windows and Mac](http://www.jonathanleroux.org/software/iguanatex/)

How to get Tables into Latex
- [Convert Excel to LaTeX Table - Table Convert Online](https://tableconvert.com/excel-to-latex)
- [CTAN: Package Excel2LaTeX](https://ctan.org/pkg/excel2latex)

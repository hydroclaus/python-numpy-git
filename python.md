# Python

## Motivation


- [open source][python], [widely used language](https://www.zdnet.com/article/programming-language-rankings-javascript-still-rules-python-holds-off-java/)
    - community, support
    - a lot of packages
        - comparable to R
        - tools for other stuff integrated ("[batteries included][batteries]"), e.g. interface to [operation system level][os], web server, [database][db_sqlite3], [web-scraping][beautiful_soup] (useufl for data), [regular expressions][re])
    
- good for employability

- good for scientific computing

    - "Computational thinking": [Ten computer codes that transformed science](https://www.nature.com/articles/d41586-021-00075-2)

    - [IPCC Special Report on Global Warming of 1.5°C (SR15)](https://matplotlib.org/matplotblog/posts/ipcc-sr15/)

    - LIGO [uses it][Ligo]
    - [Ditching Excel for Python - Lessons Learned from a Legacy Industry - Amy Peniston](https://amypeniston.com/ditching-excel-for-python/)
    - [Höhere Staatsschulden = weniger Wachstum?](https://makronom.de/reinhart-rogoff-hoehere-staatsschulden-weniger-wachstum-40736) (correlation vs. causation; the excel problem)
    
    - python in Earch Science data processing and visualisation: [3D Visualization of Well Lithology with Python, Pyvista and VTK - Tutorial](https://www.hatarilabs.com/ih-en/3d-visualization-of-well-lithology-with-python-pyvista-and-vtk-tutorial)
    
    - some arguments pro python by [Cyrille Rossant][python_science]

    - easily extensible via "modules"
    
        - vector / matrix stuff: [numpy][np]
        - other "scientific stuff": [scipy][sp]
        - visualization: matplotlib ([gallery][mpl_gallery], [plot command summary][mpl_commands])
        - data / time series: [pandas][pd]
        - nicer visualization than mpl: [seaborn][sb]
        - ... many more
        
- transition from version 2 to version 3 recently finished / ongoing. If you start fresh, I recommend version 3; I will be demonstrating using version 3

## "Scientific Python"
Despite the fact that python is a general programming language and has intrinsically many things like web-servers, simple data-bases, and many more available ("batteries included"), there exists a Python-based ecosystem of open-source software for mathematics, science, and engineering. "[SciPy](https://www.scipy.org)" (pronounced “Sigh Pie”).  In particular, these are some of the core packages that extend pythons abilities much for our purposes:

- [Numpy](https://numpy.org): linear algebra, 
- [SciPy](https://www.scipy.org/scipylib/index.html): statistics, FFT, special functions,...
- [matplotlib](https://matplotlib.org): plotting, 
- [iPython](http://ipython.org): interactive computing, 
- [xarray](https://xarray.pydata.org/en/stable/index.html): xarray: N-D labeled arrays and datasets in Python
- [pandas](https://pandas.pydata.org): data structures, particularly good for time-series
- [pint](https://pint.readthedocs.io/en/stable/): define, operate and manipulate physical quantities
- [SymPy](https://www.sympy.org/en/index.html): symbolic math 

### matplotlib
A plotting/visualisation environment that can conveniently be called directly from python

- [Matplotlib Figures](https://matplotlib.org/matplotblog/posts/an-inquiry-into-matplotlib-figures/)
- [pyplot vs. object-oriented plotting](https://matplotlib.org/matplotblog/posts/pyplot-vs-object-oriented-interface/)
- [The Python Graph Gallery](https://www.python-graph-gallery.com)
- [Matplotlib Forum](https://discourse.matplotlib.org/)
- [Matplotlib Packages / "extensions"](https://matplotlib.org/mpl-third-party/)
- [dufte](https://github.com/nschloe/dufte): This package creates clean and beautiful plots that work on light and dark backgrounds. Inspired by the work of Edward Tufte.
- great matplotlib "book" (PDF): [Scientific Visualization: Python + Matplotlib](https://github.com/rougier/scientific-visualization-book) by Nicolas Rougier

#### On the Use of Color
- [SciPy 2015 video](https://www.youtube.com/watch?v=xAoljeRJ3lU) on developing the then novel default color map 
- [paper by Stoelzle and Stein](https://hess.copernicus.org/preprints/hess-2021-118/): "Rainbow colors distort and mislead research in hydrology – guidance for better visualizations and science communication" in HESSD
- nature paper: Crameri, F., Shephard, G.E. & Heron, P.J. The misuse of colour in science communication. Nat Commun 11, 5444 (2020). [https://doi.org/10.1038/s41467-020-19160-7][mpl_color_nature]


### ipython / project jupyter
Most of my teaching takes place in [jupyter notebooks](https://jupyter-notebook.readthedocs.io/en/stable/) or in [JupyterLab](https://jupyterlab.readthedocs.io/en/latest/)

- [project jupyter][jupyter] developed from [ipython](http://ipython.org)

- notebooks have certain advantages, especially for teaching:

    - scientific notebooks for systematic search for novel discoveries (science), such as Kepler who discovered the moons of jupyter after meticuously recording his astronomical observations in his famous notebooks
    - combine text (including math), computing, __and__ visualization
    - great for teaching
    - [widgets][jup_widgets]
    - simple inteface to [R][R] and others
    - [gallery][jup_gallery] of interesting notebooks; [earth science section][jup_earthsci]
    - [keyboard shortcuts][jup_keyboard]
    - cross-platform, as they work in browser (recommendation: firefox, chrome)
    

    
#### Writing in jupyter notebooks

- [latex][latex] 

    - the "not so short introduction to latex" ([lshort][lshort])

- [markdown][md]
    - [markdown tutorial](https://www.markdowntutorial.com)

#### Intersting Python / Jupyter Packages
- [Ice Cream](https://github.com/gruns/icecream) (`ic`) -- convenience for debugging
- [Science Plots](https://github.com/garrettj403/SciencePlots) for pretty figures
- Curated list of [jupyter tools](https://github.com/markusschanta/awesome-jupyter) (via the [talk python podcast](https://talkpython.fm/episodes/show/394/awesome-jupyter-libraries-and-extensions-in-2022))

## Tutorials, Help
Here is a list of some useful tutorials:

- official [python tutorial][py_tutorial]; list of tutorials in the [python wiki](https://wiki.python.org/moin/BeginnersGuide/Programmers)

- [Scipy Lecture Notes][sp_lectures]

- [e2eml school](https://e2eml.school/blog.html)

- [from python to numpy](https://www.labri.fr/perso/nrougier/from-python-to-numpy/) and [numpy questions](https://github.com/rougier/numpy-100) by Nicolas Rougier

- [Modern Python Developer's Toolkit](https://pycon.switowski.com/)

- good course for novices: [Lorena Barba MOOC course](https://openedx.seas.gwu.edu/courses/course-v1:GW+EngComp1+2018/about)

- [PyTudes](https://github.com/norvig/pytudes) by Peter Norvig

- Allen Downey:
    - [blog](https://www.allendowney.com/blog/)
    - [books](https://greenteapress.com/wp/)
	    - [tink python](https://greenteapress.com/wp/think-python-2e/); a [repo with worked examples](https://github.com/BenU/thinkPython); UPDATE: [3rd version](https://allendowney.github.io/ThinkPython/index.html)
	    - [think stats](https://www.greenteapress.com/thinkstats/)
    - [on Colab](https://colab.research.google.com/github/AllenDowney/)

- [Numpy Introduction](https://colab.research.google.com/github/cs231n/cs231n.github.io/blob/master/python-colab.ipynb) on [google colab](https://colab.research.google.com/notebooks/intro.ipynb) 
- [Numpy tutorials](https://numpy.org/numpy-tutorials/)
- [Python Programming And Numerical Methods: A Guide For Engineers And Scientists](https://pythonnumericalmethods.berkeley.edu/notebooks/Index.html)
- [Hans Petter Langtangen](http://hplgit.github.io/homepage/index.html)
- for [pandas](https://pandas.pydata.org), there are
	 - "[10 minutes to pandas](https://pandas.pydata.org/pandas-docs/stable/user_guide/10min.html)"
	 - [Python for Data Analysis](https://wesmckinney.com/book/), 3E by Wes McKinney
- The following two webpages offer great resources, particularly for beginners:
    - [realpython.com](https://realpython.com)
    - [tutorialspoint.com](https://www.tutorialspoint.com/index.htm)
- YouTube video tutorials: [Python Numpy for Your Grandma](https://www.youtube.com/playlist?list=PL9oKUrtC4VP6gDp1Vq3BzfViO0TWgR0vR)



Also, check out the [github student pack](https://education.github.com/pack) that comes with wonderful tools such as the [git gui "Tower"](https://www.git-tower.com), ["working copy"](https://workingcopyapp.com) an awesome git gui for iOS, and others



## Python and geographic data / geocomputation / GIS
- online book, with Jakub Nowosad: [Geocomputation with Python](https://py.geocompx.org)
- Working with Spatial Data in Python, [OpenGeoHub Summer School](https://geobgu.xyz/presentations/p_2023_ogh/)
- [Computational modelling of terrains](https://tudelft3d.github.io/terrainbook/)

## Installing on your own maching
You could download python, and most modules individually, either as compiled binary for your OS, or via some sort of packages. The distribution I recommend, is [anaconda][anaconda] (free fopr personal use). "Distribution" means that most commonly used modules (such as numpy et al.) are included in one downloadable installer. For windows, there is a portable scientific python distribution, "[WinPython](https://sourceforge.net/projects/winpython/)"


### Integrated Development Environment (IDE):
IDEs offer a convenient environment to develop code. This might be useful when a jupyter notebook is not enough anymore, or for coding/developing routines that are tested and played with in jupyter.

IDEs offer the following advantages
    - debugging
    - some niceities (not necessary for jupyter notebooks)
    - anaconda comes with [Visual Studio Code](https://code.visualstudio.com/), which is some kind of hybrid text editor and IDE, and also comes with [Spyder](https://www.spyder-ide.org)
    - other options: 
        - [PyCharm][pycharm] (free for educational purposes, cross-platform); 
        - [PyScripter][pyscripter] (on windows, I learned it there, loved it)

### Text Editors
For editing text and data files, a good text editor is a must. Here are some recommendations:

- mac OS: 
    - [textmate][TM]
    - [Sub Etha Edit](https://subethaedit.net)
- cross-platform: 
    - [Sublime Text][sublime], 
    - [notepad++](https://notepad-plus-plus.org/)
    - [Visual Studio Code](https://code.visualstudio.com) or "[vscodium](https://github.com/VSCodium/vscodium)" its sibbling that doesn't phone home





## eBooks at the Library of the University of Tübingen (old)
- [Python Data Science Essentials - Second Edition](http://proquest.tech.safaribooksonline.de/9781786462138)
- [Python Data Science Handbook](http://proquest.tech.safaribooksonline.de/book/programming/python/9781491912126)
- [NumPy Essentials](http://proquest.tech.safaribooksonline.de/9781784393670)
- [Foundations for Analytics with Python](http://proquest.tech.safaribooksonline.de/9781491922521)
- [Mastering matplotlib](http://proquest.tech.safaribooksonline.de/9781783987542)

[python]: https://www.python.org/
[os]: https://docs.python.org/3/library/os.html
[db_sqlite3]: https://docs.python.org/3.5/library/sqlite3.html
[batteries]: https://www.python.org/dev/peps/pep-0206/
[re]: https://docs.python.org/3/library/re.html
[py_tutorial]: https://docs.python.org/3/tutorial/index.html
[sp_lectures]: http://www.scipy-lectures.org
[python_science]: http://cyrille.rossant.net/why-using-python-for-scientific-computing/
[np]: http://www.numpy.org
[sp]: http://docs.scipy.org/doc/
[mpl_gallery]: http://matplotlib.org/gallery.html
[mpl_commands]: http://matplotlib.org/api/pyplot_summary.html
[pd]: http://pandas.pydata.org/
[sb]: http://stanford.edu/~mwaskom/software/seaborn/
[R]: http://pandas.pydata.org/
[Ligo]:https://www.reddit.com/r/IAmA/comments/45g8qu/we_are_the_ligo_scientific_collaboration_and_we/czxnlux
[beautiful_soup]: https://www.crummy.com/software/BeautifulSoup/
[lshort]: http://tug.ctan.org/info/lshort/english/lshort.pdf
[latex]: https://latex-project.org/guides/
[md]: https://daringfireball.net/projects/markdown/syntax
[anaconda]: https://www.anaconda.com/products/individual
[jup_gallery]: http://jupyter-notebook.readthedocs.org/en/latest/notebook.html
[jup_earthsci]: https://github.com/ipython/ipython/wiki/A-gallery-of-interesting-IPython-Notebooks#earth-science-and-geo-spatial-data
[jup_widgets]: https://github.com/ipython/ipywidgets
[jup_keyboard]: https://iqbalnaved.wordpress.com/2013/09/04/ipython-notebook-keyboard-shortcuts/
[jupyter]: http://jupyter.org/
[TM]: http://macromates.com/download
[sublime]: http://www.sublimetext.com/
[pycharm]: https://www.jetbrains.com/pycharm-edu/
[pyscripter]: https://sourceforge.net/projects/pyscripter/
[mpl_color_nature]: https://www.nature.com/articles/s41467-020-19160-7
# Python

## Motivation


- [open source][python]

    - community, support
    
    - a lot of packages
    
        - comparable to R
        - tools for other stuff integrated ("[batteries included][batteries]"), e.g. interface to [operation system level][os], web server, [database][db_sqlite3], [web-scraping][beautiful_soup] (useufl for data), [regular expressions][re])
    
- good for employability



- good for scientific computing

    - LIGO [uses it][Ligo]
    
    - python in Earch Science data processing and visualisation: [3D Visualization of Well Lithology with Python, Pyvista and VTK - Tutorial](https://www.hatarilabs.com/ih-en/3d-visualization-of-well-lithology-with-python-pyvista-and-vtk-tutorial)
    
    - some arguments pro python by [Cyrille Rossant][python_science]

    - easily extensible via "modules"
    
        - vector / matrix stuff: [numpy][np]
        - other "scientific stuff": [scipy][sp]
        - visualization: matplotlib ([gallery][mpl_gallery], [plot command summary][mpl_commands])
        - (data / time series: [pandas][pd])
        - (nicer visualization than mpl: [seaborn][sb])
        - ... many more
        
- transition from version 2 to version 3 recently finished / ongoing. If you start fresh, I recommend version 3; I will be demonstrating using version 3


## ipython / project jupyter

- ipython → [project jupyter][jupyter]

- notebooks

    - scientific notebooks for systematic search for novel discoveries (science), such as Kepler who discovered the moons of jupyter after meticuously recording his astronomical observations in his famous notebooks
    - combine text (including math), computing, __and__ visualization
    - great for teaching
    - [widgets][jup_widgets]
    - simple inteface to [R][R] and others
    - [gallery][jup_gallery] of interesting notebooks; [earth science section][jup_earthsci]
    - [keyboard shortcuts][jup_keyboard]
    - cross-platform, as they work in browser (recommendation: firefox, chrome)
    

    
### Writing in ipynb

- [latex][latex] 

    - the "not so short introduction to latex" ([lshort][lshort])

- [markdown][md]


## Tutorials, Help

- official [python tutorial][py_tutorial]
- [Scipy Lecture Notes][sp_lectures]
- [from python to numpy](https://www.labri.fr/perso/nrougier/from-python-to-numpy/) and [numpy questions](https://github.com/rougier/numpy-100) by Nicolas Rougier
- good course for novices: [Lorena Barba MOOC course](https://openedx.seas.gwu.edu/courses/course-v1:GW+EngComp1+2018/about)
- [Allen Downey on Colab](https://colab.research.google.com/github/AllenDowney/)
- [PyTudes](https://github.com/norvig/pytudes) by Peter Norvig
- [Numpy Introduction](https://colab.research.google.com/github/cs231n/cs231n.github.io/blob/master/python-colab.ipynb) on [google colab](https://colab.research.google.com/notebooks/intro.ipynb) 
- for [pandas](https://pandas.pydata.org), there is "[10 minutes to pandas](https://pandas.pydata.org/pandas-docs/stable/getting_started/10min.html)"
- The following two webpages offer great resources, particularly for beginners:
    - [realpython.com](https://realpython.com)
    - [tutorialspoint.com](https://www.tutorialspoint.com/index.htm)



Also, check out the [github student pack](https://education.github.com/pack) that comes with wonderful tools such as the [git gui "Tower"](https://www.git-tower.com/mac), ["working copy"](https://workingcopyapp.com) an awesome git gui for iOS, and others

## Installing on your own maching

- you could download python, and most modules individually, either as compiled binary for your OS, or via some sort of packages. The distribution I recommend, and which is free for [academic use][anaconda_academic], is [anaconda][anaconda]. "Distribution" means that most commonly used modules (such as numpy et al.) are included in one downloadable installer. For windows, there is a portable scientific python distribution, "[WinPython](https://sourceforge.net/projects/winpython/)"

- Integrated Development Environment (IDE):

    - debugging
    - some niceities (not necessary for jupyter notebooks)
    - anaconda comes with [Visual Studio Code](https://code.visualstudio.com/)
    - options: 
        - [PyCharm][pycharm] (free for educational purposes, cross-platform); 
        - [PyScripter][pyscripter] (on windows, I learned it there, loved it)

- text editors

    - mac OS: 
        - [textmate][TM]
        - [Sub Etha Edit](https://subethaedit.net)
    - cross-platform: 
        - [Sublime Text][sublime], 
        - [notepad++](https://notepad-plus-plus.org/)
        - [Visual Studio Code](https://code.visualstudio.com)



### eBooks at the Library of the University of Tübingen
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
[anaconda]: https://www.continuum.io/downloads
[anaconda_academic]: https://www.continuum.io/anaconda-academic-subscriptions-available
[jup_gallery]: http://jupyter-notebook.readthedocs.org/en/latest/notebook.html
[jup_earthsci]: https://github.com/ipython/ipython/wiki/A-gallery-of-interesting-IPython-Notebooks#earth-science-and-geo-spatial-data
[jup_widgets]: https://github.com/ipython/ipywidgets
[jup_keyboard]: https://iqbalnaved.wordpress.com/2013/09/04/ipython-notebook-keyboard-shortcuts/
[jupyter]: http://jupyter.org/
[TM]: http://macromates.com/download
[sublime]: http://www.sublimetext.com/
[pycharm]: https://www.jetbrains.com/pycharm-edu/
[pyscripter]: https://sourceforge.net/projects/pyscripter/

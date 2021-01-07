# Debugging

'Debugging code' at the [scipy lecture notes][sp_ln_dbg]


## [Jupyterlab debugger](https://github.com/jupyterlab/debugger)
since version 3.0 is useable

### Installation
1. [xeux-pyton](https://xeus-python.readthedocs.io/en/latest/installation.html)

    conda create -n xeus-python
    conda activate xeus-python
    conda install xeus-python jupyterlab -c conda-forge

2. ptvsd, nodejs

    conda install -c conda-forge ptvsd
    conda install -c conda-forge nodejs

3. debugger

    jupyter labextension install @jupyterlab/debugger

4. the rest

    conda install numpy
    conda install scipy
    conda install matplotlib
    conda install pandas
    conda install xlrd
    conda install openpyxl

5. start jupyterlab

    jupyter lab

## jupyter notebook

- [official docu][docs_ipython]
- [simple example][dbg_example]

- at [quant-econ][quant-econ] (scroll to the Section "Debugging")
- at [gestaltrevision][gestaltrevision]


 IPython importieren und dann im code einfach `IPython.embed()` an der Stelle wo du stoppen moechtest. Und das funktioniert in IPython aber auch ganz normal in Python
 
## python scripts

- python debugger commands [dbg commands][dbg_com]


### with an IDE

- probably preferred: PyCharm (see at the bottom of [the python intro notebook][python_ipynb])



[docs_ipython]: https://ipython.readthedocs.io/en/stable/interactive/reference.html#using-the-python-debugger-pdb
[quant-econ]: http://quant-econ.net/py/ipython.html
[gestaltrevision]: http://gestaltrevision.be/wiki/python/debugging
[dbg_com]: https://docs.python.org/3.5/library/pdb.html#debugger-commands
[dbg_example]: http://nbviewer.jupyter.org/urls/gist.githubusercontent.com/damontallen/8e68b7b823573ecc9d60/raw/583607af4a92f39afe407171cd20f7adcd90defe/Debugging%20Example.ipynb
[sp_ln_dbg]: http://www.scipy-lectures.org/advanced/debugging/index.html
[python_ipynb]: 88_python.ipynb
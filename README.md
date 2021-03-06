# jp_gene_viz

A collection of visualizations for genomics related information for use with Jupyter notebooks.

Please see the [index.ipynb](index.ipynb) IPython notebook for
a guide to the package content.

To launch a container to run the package in the Binder service, please
click the image link below:

[![Binder](http://mybinder.org/badge.svg)](http://mybinder.org/repo/simonsfoundation/jp_gene_viz)

# Installation

The installation requires the Python module `jp_gene_viz` to be installed with its
dependencies and for the wigdets extension to be enabled in Jupyter/IPython.

For example the following sequence completes a first time complete installation

### clone the repository and change directory into the repository folder

```
git clone https://github.com/simonsfoundation/jp_gene_viz.git
cd jp_gene_viz
```

### install the requirements and the module
```
pip install -r requirements.txt
python setup.py install
```

### enable the widgets extension (just in case it isn't already enabled)
```
jupyter nbextension enable --py --sys-prefix widgetsnbextension
```

Note: We are upgrading the repository to work with the latest ipywidgets and iPython
releases.  If you have problems installing the package please post an issue at
[https://github.com/simonsfoundation/jp_gene_viz](https://github.com/simonsfoundation/jp_gene_viz).

ERM

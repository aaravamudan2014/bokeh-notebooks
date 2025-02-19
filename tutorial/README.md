## Clone or download the repo
First get local copies of the tutorial notebooks:

```
$ git clone https://github.com/bokeh/bokeh-notebooks.git
```

Or download from: https://github.com/bokeh/bokeh-notebooks/archive/master.zip

## Install the dependencies

This tutorial has been tested on:

* bokeh 0.12.7
* pandas 0.20.3
* notebook 5.0.0
* phantomjs 2.1.1
* pillow 4.2.1
* selenium 3.5.0

Other combinations may work also.

The quickest, easiest way to install is to use Anaconda (or Miniconda):

#### Installing with anaconda

Install [anaconda](http://anaconda.com/downloads)

Anaconda should come with all the dependencies included, but you may need to update your versions.

#### Installing with miniconda

Install [miniconda](http://conda.pydata.org/miniconda.html).

Use the command line to create an environment and install the packages:

```bash
$ conda env create
$ source activate bokeh-notebooks
```

NOTE: Run this in the `tutorial` directory where `environment.yml` file is.

----

Once you've got a base install, you can install the remaining dependencies with:

```bash
conda install phantomjs pillow selenium
```

## Get the sample data

Bokeh has a sample data download that gives us some data to build demo visualizations. To get
it run the following command at your command line:

```bash
$ bokeh sampledata
```

### Install Datashader and Holoviews (optional)

Some optional sections require the additional packages Flask, Datashader, and Holoviews.
These  can be installed with:

```bash
$ conda install -c pyviz datashader holoviews flask
```

## Run the Jupyter notebook

From this folder run jupyter notebook, and open the [00 - Introduction and Setup.ipynb](00 - Introduction and Setup.ipynb) notebook.

```
$ jupyter notebook
```

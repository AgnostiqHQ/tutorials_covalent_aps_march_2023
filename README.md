# APS March 2023: Covalent Workshop

<div align="center">

<img src="https://raw.githubusercontent.com/AgnostiqHQ/covalent/master/doc/source/_static/covalent_readme_banner.svg" width=150%>

</div>

This repository contains all the of the needed material to complete the `covalent` workshop hosted at APS March 2023, Las Vegas, Nevada.

You will find:

1. The slides from the talk part of the workshop (`slides.pdf`)

2. Jupyter notebooks needed for the hands-on workshop (`workshop/machine_learning/similarity_learning.ipynb`)

3. `code_examples` contains several simple examples different features/aspects of Covalent

## Install instructions

To run the jupyter notebooks used in the hands-on workshops, you will need a new `conda` environment with all of the dependencies.

First, clone or download this repository to your local machine.

Next, if you don't already have conda, navigate to <https://conda.io/projects/conda/en/latest/user-guide/install/download.html> and install the correct version for your OS for either Miniconda or Anaconda.

In a terminal window, navigate to root directory of this repo (`~/tutorials_covalent_aps_march_2022`) and issue

`> conda env create -f environment.yml`

This will install the `aps_march_covalent` environment. Let's activate it

`> conda activate aps_march_covalent`

If you are confident with making this environment visible to your existing Jupyter Notebook viewer, you are done! If not, please continue with

`> python -m ipykernel install --user --name=aps_march_covalent`

then issue

`> jupyter notebook &`

which will open a browser window in the Jupyter explorer. Navigate to the `*.ipynb` file you are interested in looking at within this repo and click it.

From the top drop-down menu, select `kernel > change kernel > aps_march_covalent`. You are now good to go!


### Start Covalent

After successfully creating the conda environment, the Covalent server can be started as follows

```bash
covalent start
```

Covalent can optionally be started in debug mode for more verbose logging as follows

```bash
covalent start -d
```

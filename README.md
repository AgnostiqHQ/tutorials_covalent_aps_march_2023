# APS March 2023: Covalent Workshop

<div align="center">
<img src="https://raw.githubusercontent.com/AgnostiqHQ/covalent/master/doc/source/_static/covalent_readme_banner.svg" width=150%>
</div>

This repository contains materials for the [Covalent](https://github.com/AgnostiqHQ/covalent) workshop hosted at APS March 2023, Las Vegas, Nevada.

## 🤔  What is Covalent?

Covalent is a Pythonic workflow tool that makes it easy to run and monitor *reproducible* experiments on a *distributed* patchwork of local and/or remote resources. Accessing HPC clusters, quantum computers, and other cloud services with Covalent requires little more than adding a handful of [decorators](https://realpython.com/primer-on-python-decorators/) to your existing codebase.

Please see the links below for more information.

## 🔗 Quick Links

### Covalent

_If you enjoy this workshop, please support the project by starring the GitHub repository!_ 😎

- [GitHub](https://github.com/AgnostiqHQ/covalent) ⭐️
- [Website](https://covalent.xyz)
- [Documentation](https://covalent.readthedocs.io/en/latest/index.html)
- [Tutorials](https://covalent.readthedocs.io/en/latest/tutorials/tutorials.html)

### Workshop

- [Jupyter notebook](https://github.com/AgnostiqHQ/tutorials_covalent_aps_march_2023/blob/main/workshop/machine_learning/similarity_learning.ipynb) 
- [Slides PDF](https://github.com/AgnostiqHQ/tutorials_covalent_aps_march_2023/blob/main/slides.pdf)
- [Minimal Covalent example](https://github.com/AgnostiqHQ/tutorials_covalent_aps_march_2023/blob/main/code_examples/covalent_101/source.ipynb)

## 💻 Setup Instructions

**NOTE:** _Setup requires a working [`conda` installation](https://docs.conda.io/en/latest/miniconda.html#latest-miniconda-installer-links)._

Follow the steps below to set up a local environment for this workshop.

1. Download or clone this repository:
```bash
git clone https://github.com/AgnostiqHQ/tutorials_covalent_aps_march_2023/tree/main/code_examples/covalent_101
```

2. Navigate to the root directory (`tutorials_covalent_aps_march_2022`) on your local filesystem.

3. Create new conda environment:
```bash
conda env create -f environment.yml
```

5. Activate the new conda environment:
```bash
conda activate aps_march_covalent
```

6. Start the Covalent server:
```bash
covalent start
```

7. Start Jupyter Notebook:
```bash
jupyter notebook
```

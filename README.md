# OpenBBSDKexplorer

## Project description

An exploration of OpenBB features.

[OpenBB Platform](https://my.openbb.co) is a collection of open source tools for investment research.

The goal of this repository is to explore what can be done with the OpenBB platform.

## Environment & Package management

This project uses [Miniconda](https://docs.conda.io/projects/miniconda/en/latest/) as enviroment manager
and [Poetry](https://python-poetry.org/) as package manager.

### Setting up the environment

1. Install miniconda ([Installation instructions](https://docs.conda.io/projects/miniconda/en/latest/miniconda-install.html))

2. Create the conda environment

```bash
conda env create -f environment.yml
```

3. Use Poetry to install the packages

```bash
poetry install
```

## Using the notebooks

### On VSCode

The `extensions.json` contains the recomended jupyter extension that allows you to use the notebooks directly on vscode

### Using `ipykernel`

You can also use [`ipykernel`](https://ipython.readthedocs.io/en/stable/install/kernel_install.html) to start a local jupyter notebook server and access them through your browser.

## About Open BB

> !TODO: add openBB modules descriptions
# Dask Tutorial - Advanced

[![Build](https://github.com/dask-contrib/dask-tutorial-advanced/actions/workflows/build.yml/badge.svg)](https://github.com/dask-contrib/dask-tutorial-advanced/actions/workflows/build.yml)

This repository contains materials for the "Advanced Dask Tutorial" that will be presented at SciPy 2023.

## Running the tutorial

Download the tutorial notebooks and install the necessary packages (via `conda`) locally. Setting things up locally can take a few minutes, so we recommend going through the installation steps prior to the tutorial.

### 1. Clone the repository

First clone this repository to your local machine via:

```
git clone https://github.com/dask-contrib/dask-tutorial-advanced
```

### 2. Download conda (if you haven't already)

If you do not already have the conda package manager installed, please follow the instructions [here](https://docs.conda.io/en/latest/miniconda.html).

### 3. Create a conda environment

Navigate to the `dask-tutorial-advanced/` directory and create a new conda environment with the required
packages via:

```terminal
cd dask-tutorial-advanced
conda env create --file environment.yml
```

This will create a new conda environment named "dask-tutorial-advanced".

### 4. Activate the environment

Next, activate the environment:

```
conda activate dask-tutorial-advanced
```

### 5. Launch JupyterLab

Finally, launch JupyterLab with:

```
jupyter lab
```

### Instructions for Notebook 4

We will be launching the last notebook on the cloud and creating bigger clusters. From a terminal where you have the `dask-tutorial-advanced` environment activated:

```
coiled login --token f5924259c2b04a54a8f25a1e07941177-bed7217e66f325cdd64c69d4c63e2a893dc02b86 --account dask-tutorials
coiled notebook start --software dask-tutorial-advanced
```

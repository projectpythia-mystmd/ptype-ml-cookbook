<img src="thumbnail.png" alt="thumbnail" width="300"/>

# Precipitation Cookbook

[![nightly-build](https://github.com/ProjectPythia/cookbook-template/actions/workflows/nightly-build.yaml/badge.svg)](https://github.com/ProjectPythia/cookbook-template/actions/workflows/nightly-build.yaml)
[![Binder](https://binder.projectpythia.org/badge_logo.svg)](https://binder.projectpythia.org/v2/gh/ProjectPythia/cookbook-template/main?labpath=notebooks)
[![DOI](https://zenodo.org/badge/475509405.svg)](https://zenodo.org/badge/latestdoi/475509405)

This Project Pythia Cookbook covers an extremely basic precipitation classification project. This notebook will introduce learners to the scikit-learn API, basic exploratory data analysis (EDA), and evaluations. It is meant to be a very early and basic introduction to these concepts, it is not meant to be an in-depth intorduction to machine learning. It could be the first introduction to machine learning for learners familiar with weather data. 

## Motivation

This cookbook is meant to be a companion to Unidata's CyberTraining project.

## Authors

[Ana Castaneda Montoya](https://github.com/anacmontoya), [Thomas Martin](https://github.com/ThomasMGeo)

### Contributors

<a href="https://github.com/ThomasMGeo/ptype-ml-cookbook/graphs/contributors">
  <img src="https://contrib.rocks/image?repo=ProjectPythia/cookbook-template" />
</a>

## Structure

This notebook has a few sections, from inital data loading to 

### Exploratory Data Analysis

This section gives some nice examples of pair plots in Seaborn, and Correlation Matricies. 

### Dataset Splitting

For machine learning, we need a testing, training, and validation dataset. This section covers how to do that, and gives some great refrences on the why. 

### Dataset Scaling

For (most) machine learning models, scaling is necessary. This sections covers how to do that.

### Machine Learning(!!!)

The part where we actually train a model! We also see how good it is. 

## Running the Notebooks

You can either run the notebook using [Binder](https://binder.projectpythia.org/) or on your local machine.

### Running on Binder

The simplest way to interact with a Jupyter Notebook is through
[Binder](https://binder.projectpythia.org/), which enables the execution of a
[Jupyter Book](https://jupyterbook.org) in the cloud. The details of how this works are not
important for now. All you need to know is how to launch a Pythia
Cookbooks chapter via Binder. Simply navigate your mouse to
the top right corner of the book chapter you are viewing and click
on the rocket ship icon, (see figure below), and be sure to select
“launch Binder”. After a moment you should be presented with a
notebook that you can interact with. I.e. you’ll be able to execute
and even change the example programs. You’ll see that the code cells
have no output at first, until you execute them by pressing
{kbd}`Shift`\+{kbd}`Enter`. Complete details on how to interact with
a live Jupyter notebook are described in [Getting Started with
Jupyter](https://foundations.projectpythia.org/foundations/getting-started-jupyter.html).

### Running on Your Own Machine

If you are interested in running this material locally on your computer, you will need to follow this workflow:

(Replace "cookbook-example" with the title of your cookbooks)

1. Clone the `https://github.com/ProjectPythia/cookbook-example` repository:

   ```bash
    git clone https://github.com/ProjectPythia/cookbook-example.git
   ```

1. Move into the `cookbook-example` directory
   ```bash
   cd cookbook-example
   ```
1. Create and activate your conda environment from the `environment.yml` file
   ```bash
   conda env create -f environment.yml
   conda activate cookbook-example
   ```
1. Move into the `notebooks` directory and start up Jupyterlab
   ```bash
   cd notebooks/
   jupyter lab
   ```

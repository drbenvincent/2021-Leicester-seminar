# A beginners guide to Bayesian cognitive modelling

This repository contains code to accompany a talk I was invited to give in 2021 at the University of Leicester, UK.

We have some [Jupyter](https://jupyter.org) notebooks full of Julia code. These were run with Julia version 1.5.3
- Example 1 - [Bayesian linear regression](bayesian_linear_regression.ipynb)
- Example 2 - [Hyperbolic discounting](hyperbolic_discounting.ipynb)
- Example 3a - [Covert attention](covert_attention_1.ipynb) This uses the same methods that I used to calculate Bayesian optimal observer predictions a number of years ago.
- Example 3b - [Covert attention](covert_attention_2.ipynb) This version uses a more conceptually appealing approach of specifying a generative model then letting the computer do the hard work. If I do Bayesian optimal observer models again, this is the approach I would use.

## Running the code

You can of course just look at the rendered Jupyter notebooks here on GitHub. But if you want to run them and explore for yourself then follow these steps:

### 1. Download Julia 
This is easy - you can download from [julialang.org](https://julialang.org/).

### 2. Make sure you are set up with Jupyter notebooks
There are a number of good guides to get set up with Jupyter notebooks (eg [here](https://datatofish.com/add-julia-to-jupyter/)). It is not that hard (the "ju" in Jupyter does stand for Julia) to do, but I believe you'll need a Python installation.

### 3. Use the environment
To avoid any version clashes with other Julia packages, you can use the environment provided. 
- Make sure your working directory is set to the location to where you saved this repository locally. 
- In a Julia session, simply type `]` to enter package mode.
- Type `activate .` to activate the environment
- The first time you run, you should also type `instantiate` (in package mode). This will install any required packages that you do not already have.
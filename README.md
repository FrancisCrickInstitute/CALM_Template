# CALM Template

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/FrancisCrickInstitute/CALM_Template/HEAD?labpath=blob%2Fmain%2Fsegment_image.ipynb)
[![Python 3.11](https://img.shields.io/badge/python-3.11-blue.svg)](https://www.python.org/downloads/release/python-3115/)
![Commit activity](https://img.shields.io/github/commit-activity/y/FrancisCrickInstitute/CALM_Template?style=plastic)
![GitHub](https://img.shields.io/github/license/FrancisCrickInstitute/CALM_Template?color=green&style=plastic)

This is a template repository that we recommend as a starting point for making available online any code you use for the purposes of image analysis. This might include, but is not limited to...
* ImageJ/FIJI Macros
* CellProfiler pipelines
* ilastik projects
* Jupyter notebooks
* Python scripts
* MATLAB scripts

## Why?

It is often the case that publishing code is left until the last minute when a paper is being submitted, which results in published code that is in no way reusable. If the code is not reusable and cannot be run by anyone other than you, then nobody is going to be able to reproduce your published results! So, put as much time and effort into publishing your code as you do into writing the methods section of your paper.

## What Should You Include?

When publishing image analysis protocols, we recommend following the guidance in the following article:

> Schmied, C., Nelson, M.S., Avilov, S. et al. Community-developed checklists for publishing images and image analyses. _Nat Methods_ (2023). https://doi.org/10.1038/s41592-023-01987-9

But at the absolute minimum, your repository should include the following:
* All required code
  * Ideally, this should be structured in a logical fashion using directories and sub-directories as necessary.
* Instructions on how to run your code
  * This is crucial - do not assume that anyone will be able to figure out what your code does! Provide basic, step-by-step instructions on how to run your code, including any prerequisites that need to be installed.
* Test Data
  * Your repository should contain some test data that anyone can run your code on to verify that it is performing as it should be. You should also provide the corresponding output data to validate the code.

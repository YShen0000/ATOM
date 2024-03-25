## Project Overview
The project dedicates to transform drug discovery from a slow, sequential, and high-failure process into a rapid, integrated, and patient-centric model. We are integrating high performance computing, diverse biological data, and emerging biotechnologies to create a new pre-competitive platform for drug discovery.

## Project Objective
The first part of the project takes a look at Quantum Mechanical Properties of Drug-like Molecules([QMugs](https://www.nature.com/articles/s41597-022-01390-7)).

We aim to find out that
- how featurizer and splitting methods impact model performance
- which combination of featurizer and splitter in the model could yield highest prediction accuracy
- how accurately our models could predict DFT gap values of different functional groups

The second part of the project is to look at another dataset which has compounds with similar structure and apply the previsou models so as to validate them. If the general prediction accuracy is below expectation, the next step is to train a new set of models and investigate the potential of applying a model trainned with small amount of data to a large dataset.

## Table of contents
- QMUGS
    - import packages
    - data loading
    - data curation using AMPL
    - EDA
    - seach for functional group
    - model training
    - view results and create visulaizations for presentation use
- QMUGS1.1
    - import packages
    - data loading
    - data curation using AMPL
    - EDA
    - model re-testing using QMUGS Models
    - model training
    - view results and create visulaizations for presentation use

## Pipeline & Packages
The ATOM Modeling PipeLine ([AMPL](https://github.com/ATOMScience-org/AMPL)) extends the functionality of DeepChem and supports an array of machine learning and molecular featurization tools. AMPL is an end-to-end data-driven modeling pipeline to generate machine learning models that can predict key safety and pharmacokinetic-relevant parameters. <br>

An [article describing the AMPL project](https://pubs.acs.org/doi/abs/10.1021/acs.jcim.9b01053) was published in JCIM. For those without access to JCIM, a preprint of the article is available on [ArXiv](http://arxiv.org/abs/1911.05211). [Documentation is available here.](https://ampl.readthedocs.io/en/latest/pipeline.html)

Below is a quick guide from installation to some usage, more information is provided in this [link](https://github.com/ATOMScience-org/AMPL).
- [Install](#install)
   - [Quick Install](#installation-quick-summary)
   - [Jupyter kernel](#create-jupyter-notebook-kernel-optional)
   - [Docker](#install-with-docker)
   - [Uninstall](#uninstall)
- [AMPL Features](#ampl-features)
- [Running AMPL](#running-ampl)
- [Tests](#tests)
- [Advanced AMPL usage](#advanced-ampl-usage)
- [Advanced testing](#advanced-testing)
- [Tutorials](#ampl-tutorials)
- [Development](#development)
- [Project information](#project-information)  
- [Suggestions or Report Issues](#suggestions-issues)

## Useful links
- [Pipeline parameters (options)](atomsci/ddm/docs/PARAMETERS.md)
- [Library documentation](https://ampl.readthedocs.io/en/latest/index.html)

*Created by the [Accelerating Therapeutics for Opportunities in Medicine (ATOM) Consortium](https://atomscience.org)*

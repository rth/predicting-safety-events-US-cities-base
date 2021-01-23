# Predicting safety events in US cities -- starting repository

Starter repository for Manning LP: Predicting safety events in US cities with Machine Learning

## Setup

This project requires Python 3.7+. It is recommended to use the Anaconda
distribution of Python and conda for managing packages.

Following steps setup an environment with all the requirements for this
project,
 1. Clone this repository.
 2. To create a virtual environment and install requirements, run
    ```
    conda create -n predicting-safety-events python=3.8
    conda activate predicting-safety-events
    conda install -c conda-forge --file requirements.txt
    ```
    from the root of the repository. The installation process can take a few minutes.
 3. Additional packages can be installed with `conda install` or `pip install`
    inside this environment. You can make sure you are inside the correct
    virtual environment by checking the output of `conda info` command.

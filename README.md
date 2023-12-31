# ai-nanodegree-conda-env
My conda environment for Udacity's Artificial Intelligence Nanodegree program

Clone the repo and run:

    conda env create -f environment_myaind.yml

Activate the repo:

    conda activate myaind

This environment file was created by creating a conda environment and then incrementally installing packages as follows:

    conda create -n myaind
    conda activate myaind
    conda install python=3.9
    conda install pandas
    conda install pytest
    conda install pytest-cov
    conda install pypy
    conda install flake8 
    conda install black 
    conda install isort
    conda install pre-commit
    conda install notebook
    conda install matplotlib
    conda install seaborn
    pip install udacity-pa

Then export the environment:

    conda env export > environment_myaind.yml
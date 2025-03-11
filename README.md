This repository contains the following structure:
Root Directory

    datasets.ipynb: This Jupyter Notebook was responsible for preprocessing the data for the DNRI model.

dnri Directory

This directory contains the necessary scripts and subdirectories to run the DNRI experiments.

    run_gnr_springs.sh: A bash script responsible for executing the GNR experiment.
    results/: A directory containing the results from the three experiments.
    dnri/experiments/gnr_springs_experiment.py: A Python script that defines the GNR Springs experiment.
    dnri/datasets/gnr_spring_data.py: A python script that loads the data
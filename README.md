# Sample PyTorch Project Repository



<p align="center">
    <img src="./statics/brain.png" alt="Brain Image" width="450"/>
</p>
<p align = "center">A Repository/Project Structure for Pytorch Projects</p>


## Description

Here describe the overall aims/goal of the project and the project. A description of previous work in this field and inspiration for this
approach are pretty good things to include as well as overall good descriptions of the guiding research questions and ideas being explored
in this repostiory. The most commonly used notebook is the training notebook, which is used in actually running experiments. A sample training notebook is attached to see what is left to be written after all OOP is defined for other aspects of the model.

## Contents

The repository file structure consists of: 

    ├── datasets                # PyTorch dataset models corresponding to the various data types
    ├── models                  # PyTorch neural network models used for experiments
    ├── losses                  # Custom losses for the network training
    ├── raw_data                # The raw data stored in a .pkl/.csv/etc. Alternatively links to other data.
    ├── saved_models            # Saved models (.pt files) corresponding to saved runs
    ├── statics                 # Static resources (i.e. images) for the readme
    ├── utils                   # Utility functions for data preprocessing, visualization, etc
    ├── demos                   # Jupyter notebooks of demo utilizations of the github repo
    ├── experiments.json        # The experiment hyperparameters stored in a JSON file as well as associated outputs
    ├── requirements.txt        # List of python and other dependencies utilized in this network. 
    ├── Trainer.ipynb           # Jupyter Notebook utilized in training the networks
    └── README.md

To clone this repository locally simple enter into terminal:

```
git clone https://github.com/{githandle}/{project_name}.git
```

Note: dependencies in the `requirements.txt` file will still be needed to be installed independently.

## Data Sources

Here one should list the sources for their datasets, includings links to where they can be found. 

The data files and their sources are all listed below: 


## Citations

Here list enumerated citations of the inspiring works in this repository/dependencies (say like BERT). For example:

[1] Oord, Aäron van den et al. “WaveNet: A Generative Model for Raw Audio.” ArXiv abs/1609.03499 (2016): n. pag.

[2] Franceschi, Jean-Yves et al. “Unsupervised Scalable Representation Learning for Multivariate Time Series.” NeurIPS (2019).

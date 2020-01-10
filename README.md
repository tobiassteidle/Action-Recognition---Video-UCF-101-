# Video Classification

## Objectives
Classification of Human Actions in a Video 

## Download and Prepare Data
[Download the UCF101 data set](https://www.crcv.ucf.edu/data/UCF101/UCF101.rar)  
Unzip to [data/](data/) directory

## Additional Information
Tensorflow Version: GPU 2.0

## Installation
1. Create and activate a new environment.
```
conda create -n action python=3.6
source activate action
```
2. Install Dependencies.
```
pip install -r requirements.txt
```

### Launch Jupyter notebook
```
jupyter notebook "Action Recognition.ipynb"
```

### Additional commands
Starts Tensorboard Visualisation.
```
tensorboard --logdir=logs/
```

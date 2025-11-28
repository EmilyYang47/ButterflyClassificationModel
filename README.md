# Butterfly Species Classification CNN

This repository contains a class project for **DS542: Deep Learning for Data Science**.

## Project Description

In this project, we built and trained a multi-class classification convolutional neural network (CNN) for classifying butterfly species from images. The model learns to distinguish different butterfly species based on the training data provided.

Due to some technical issues with the SCC (Shared Computing Cluster) when this project was implemented, training was limited and did not run for enough epochs to reach full convergence.

## Files

- `project2.ipynb` — Jupyter notebook with model design, training code, and evaluation  
- `checkpoint_butterfly.pth` — Saved model checkpoint after limited training  
- `train-onehot.csv` — Training dataset with one-hot encoded labels  
- `validation-onehot.csv` — Validation dataset with one-hot encoded labels  
- `test-predictions.csv` — Model predictions on the test dataset  

## Usage

You can open and run the notebook `project2.ipynb` to review the model and training process. The checkpoint file can be loaded to evaluate or further train the model. 

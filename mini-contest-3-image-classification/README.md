# Parasite Eggs Identification
This repository contains the solution proposed for the second Mini-Contest of the **Data Mining** course (AY 20/21) at the *University of Naples Federico II*.

## Assignment
The contest aims at the detection of parasite eggs in microscopic images. The task is to determine whether a parasite egg appears or not in a given image. You can find more about the competition [here](https://www.kaggle.com/c/unina-data-mining-2021-minicontest-n3/overview).

## Solution
The solution shown in the Notebook, implemented by means of **PyTorch**, is made up of different stages:
- **Data understanding**: extract some useful information from the training images.
- **Data preparation**: prepare data for the next stage.
- **Modeling**: exploit *Convolutional Neural Networks* (CNNs) and transfer learning.
- **Evaluation**: evaluate model's performance.

The final model choosed for the submission is GoogLeNet, that achieved an accuracy of 0.98897.

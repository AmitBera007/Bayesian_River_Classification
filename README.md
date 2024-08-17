# Bayesian_River_Classification
This project implements a Bayesian decision rule for classifying River and Non-river areas using satellite images.

## Dataset
The dataset consists of four satellite images in .gif form which can be downloaded from [here](https://www.isical.ac.in/~murthy/).

## Requirements
- Python 3.x
- numpy
- pandas
- matplotlib
- scikit-image
- scikit-learn
- seaborn
- opencv-python

## Installation
```
pip install numpy pandas matplotlib scikit-image scikit-learn seaborn opencv-python
```
## Usage
### 1. Annotate Points:
Run the following script to manually annotate 50 points from the river and 150 points from non-river in band4 image:
```
python annotate_image_points.py
```
### 2. Run Classification:
Run the band_image_read.ipynb to classify the River and Non-river areas and plot the confusion matrix:


# Scripts
- **`annotate_image_points.py`**
Script for annotating points on the image.
- **`band_image_read.ipynb`**
Script for classifying River and Non-river areas and plotting confusion matrix.
- **`Results`**
The output will be a classified image saved as image.png and a confusion matrix plot.

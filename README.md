# Smiling-Longevity
Author: Kamila Magiera

# Introduction
Through the understanding of past studies done on similar topics, my study focuses on whether happiness instead of smiling would hold similar results as previous literature. Rather than only focusing on an individual’s smile, I used DeepFace to calculate the individual’s happiness overall by looking at the entirety of their facial mannerisms in the photos. I aimed to see if overall happiness has an effect on the age of death of celebrities. In addition to the use of DeepFace a simple linear regression showed whether the variables have a statistically significant impact on the age of death of the celebrities.
# Data
Ages.csv - contains data including celebrity names, average happiness percentage (taken from the python DeepFace pre-trained model), happiness category, sex, and year born.
Celeb Photos - The Celeb Photos folder contains all the photos of the celebrities used in this study.
# Code
SmilingLong.Rmd - contains the R code used to obtain the regression model in Table 1. Does not require any packages to be imported. R version 4.2.1 (2022-06-23) -- "Funny-Looking Kid". Directory must be changed in order to run.
comilescores.ipynb - contains the python code used to obtain the happiness percentage scores for each celebrity using DeepFace. Run in JupyterLab and requires packages: os, cv2, deepface, and matplotlib.pyplot to be imported. Directories must also be changed in order to run.

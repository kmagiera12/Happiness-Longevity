# Smiling-Longevity
Author: Kamila Magiera

# Introduction
Longevity is something many individuals strive for, but not many would think that whether they smile in photos or not plays a role in how long they will live. Many studies have been conducted to link the correlation between smiling in photos and longevity. My study takes a similar approach, but instead of looking at smile intensity, I looked at the level of happiness found in each found using a pre-trained facial attribute analysis model. My data includes a total of 899 images of 293 celebrities who have passed away (3 photos of each celebrity). My main goal was to test whether the happiness score in photos has an effect on longevity as other studies have found with smile intensity. With the use of a pre-trained model called DeepFace in python which uses facial attribute analysis to output facial expression predictions, I specifically looked at the happiness emotion for each of the images and used this percentage to find an average happiness score for each of the celebrities. Once found, I categorized these percentages into 5 different categories which range from a happiness score from 0-100%, with 20% intervals dividing each category.  I then ran a regression model to also test for other factors that may have contributed to their longevity such as sex, birth year, and cause of death. This found that the happiness score did not have a statistically significant impact on the age of death, but did find that celebrities born in later years died earlier. So although other studies have found that smile intensity affects longevity, the overall happiness score of a person using the DeepFace pre-trained model does not have a significant effect on longevity.

# Data
Ages.csv - contains data including celebrity names, average happiness percentage (taken from the python DeepFace pre-trained model), happiness category, sex, and year born.

Celeb Photos - The Celeb Photos folder contains all the photos of the celebrities used in this study.

# Code
SmilingLong.Rmd - contains the R code used to obtain the regression model in Table 1. Does not require any packages to be imported. R version 4.2.1 (2022-06-23) -- "Funny-Looking Kid". Directory must be changed in order to run.

compilescores.ipynb - contains the python code used to obtain the happiness percentage scores for each celebrity using DeepFace. Run in JupyterLab and requires packages: os, cv2, deepface, and matplotlib.pyplot to be imported. Directories must also be changed in order to run.

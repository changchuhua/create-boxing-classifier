# An Investigation into Creating a Boxing Move Classifier

This project requires installation and requirements not included in the files provided.<br/> Please refer to 02_Installation and Requirements.ipynb for installation instructions.

---
## File Directory Structure
The files and folders provided in the GitHub should be arranged in the following manner:<br/>
![](folder_structure.jpg)
<br/><br/>
The project should be accessed through the ipynb files in numerical order, from<br/>
- 01_Background and Rationale.ipynb, to
- 10_Deployment.ipynb

## Please Note:
For privacy reasons, not all training data and results are provided.<br/>
Please contact the GitHub owner for access to any data not provided. 

---
# Project Overview

## Problem Statement
> What is the best method for us to create a classifier for boxing moves?

## Executive Summary
> In this project, we aim to create a boxing move classifier as part of our milestones to create an interactive boxing trainer. <br/><br/>
Through our investigations, we find that modelling based purely on keypoints does not give us a good result.<br/>
We obtained our best results through feature engineering and utilizing a Support-Vector-Machine classifier (SVC).<br/>
We also tried using Artificial Neural Networks, however we found that they did not perform as well as our SVC, possibly due to a lack of training data.<br/><br/>
We will proceed to improve the performance of our models before moving on to other milestones.

## Conclusion and Recommendations
> We find that a best classifier can be made from a Support-Vector-Machine model with a 'Radial Basis Function' kernel and a C value of 0.95.<br/>
The data has to be feature engineered where we should normalize all datapoints over to the neck keypoint, and create scaled features of hand to shoulder distances.


# Training and testing ML models to recognize seizures

## Overview
### Please see assignment_4.docx for a full description

<img align="right" src="https://upload.wikimedia.org/wikipedia/commons/2/26/Spike-waves.png">
*image_caption*

This is an example of how to train machine learning models with SciKit-Learn packages to classify [EEG data](https://www.mayoclinic.org/tests-procedures/eeg/about/pac-20393875) as either indicative of a seizure or not. 'Final_MachineLearning.ipynb' demonstrates each of the the data manipulation steps using EEG data from the 'dataBig' folder. The accuracy of four different machine learning models (K Nearest Neighbors, SVM, Decision Tree, and Naive Bayes) are compared for accuracy in the final step.

Instructions modified from an assignment by Yao Li at the University of Illinois at Urbana-Champaign, yaoli90@illinois.edu.

## Files

The contents of the 'dataBig' folder come from this source:
- Stevenson, N. J., et al. ["A dataset of neonatal EEG recordings with seizure annotations."](https://www.nature.com/articles/sdata201939) Scientific data 6 (2019): 190039.

The contents of the 'data' folder come from this source: 
- Andrzejak RG, Lehnertz K, Rieke C, Mormann F, David P, Elger CE (2001) [Indications of nonlinear deterministic and finite dimensional structures in time series of brain electrical activity: Dependence on recording region and brain state](http://epileptologie-bonn.de/cms/front_content.php?idcat=193&lang=3), Phys. Rev. E, 64, 061907

The 'pyeeg' folder is a required Python package which helps to extract features from EEG data. 

## Notes

Please see the solution for python library dependencies. '.ipynb' file extensions are Jupyter Notebook files run from Anaconda with Python 3. Instructions for downloading Anaconda can be found by scrolling to the bottom of this [Software Carpentry site](https://swc-uiuc.github.io/2020-07-researchpark/) or on Anaconda's own website.


 




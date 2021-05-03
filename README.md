# Autism Classification Project

**Objective**: To achieve a higher classification accuracy for the classifier on the functional MRI scans; To delineate functional differences between individuals with ASD and typically developed individuals using machine learning algorithms.

**Data**: http://fcon_1000.projects.nitrc.org/indi/abide/.

To follow the analysis I conducted, the notebooks should be viewed/run as follows:

## Preliminary Research
five classifiers in traditional machine learning after PCA transformation: linear discriminant analysis, k-nearest neighbor, naïve Bayes, support vector machine and random forest

## DenseNet Model
A PyTorch-based framework MONAI with DenseNet169 architecture

## Searchlight Analysis
By visiting all voxels and analyzing their respective (partially overlapping) neighborhoods, one obtains a whole-brain map

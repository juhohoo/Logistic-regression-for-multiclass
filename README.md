# Logistic-regression-for-multiclass
Multiclass classification using logistic regression in Python.

This repository has a Python notebook "Multiclass_classification.ipynb" introducing logistic regression classifier. 
The training data file "npf_train.csv" contains several variables measured on different days (rows of the
file) at the Hyytiälä forestry field station (mainly at the SMEAR II mast, shown in the picture). The
variables are daily means and standard deviations of various measurements between sunrise and sunset. 

The task is to make a binary classifier (labels "event" vs "nonevent") for a new
variable “class2”, defined as follows: “class2” = nonevent if “class4” is nonevent and “class2” = event if
“class4” is one of Ia, Ib, or II. 

Python notebooks outputs a csv file with predicted labels and class probabilities for the test set "npf_test_hidden.csv".

More accurate description of data can be found here: https://wiki.helsinki.fi/pages/viewpage.action?pageId=243959901

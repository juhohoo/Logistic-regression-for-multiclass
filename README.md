# Logistic-regression-for-multiclass
Multiclass classification using logistic regression.

The training data file npf_train.csv contains several variables measured on different days (rows of the
file) at the Hyytiälä forestry field station (mainly at the SMEAR II mast, shown in the picture). The
variables are daily means and standard deviations of various measurements between sunrise and sunset.

The task is to make a binary classifier (event vs nonevent) for a new
variable “class2”, defined as follows: “class2” = nonevent if “class4” is nonevent and “class2” = event if
“class4” is one of Ia, Ib, or II. Python notebook Multiclass_classification.ipynb introduces logistic regression classifier to complete the task.

Description of data can be found here: https://wiki.helsinki.fi/pages/viewpage.action?pageId=243959901

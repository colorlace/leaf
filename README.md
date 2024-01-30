# LEAF
A Python framework for the quantitative evaluation of eXplainable AI methods.

## Environment Setup
`conda env create -f environment.yaml python=3.8` creates an env called `leaf` w/ all the necessary packages.
`conda activate leaf` runs the environment

The *LEAF* project directory contains the following files:
 
* _leaf.py_: the main code of *LEAF*, with the evaluation procedures for the LLE explaners LIME and SHAP
* _LEAF_test.ipynb_: a Jupyter notebook with a simple example of how to use *LEAF* to compute the
                     basic metrics for XAI evaluation
* _heartrisk-dataset.txt_: the sample HeartRisk dataset provided by Shivakumar Doddamani, in csv format. 
	                       See [www.kaggle.com/shivakumarcd/heart-risk-problem](www.kaggle.com/shivakumarcd/heart-risk-problem) for reference.

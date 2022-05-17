# Conventional Machine Learning 

Workshop on Machine Learning organised at the Data Science Center on 20 May 2022. 

# Conventional Machine Learning

In the past decade, Deep Learning, originally a subfield of Machine Learning, has gained considerable influence and momentum. 
In order to distinguish "traditional" Machine Learning such as Random Forest or Regularised Regression from Deep Learning models, we decided to coin this workshop _"conventional Machine Learning"_.

__Note:__ Machine Learning is often abbreviated as ML.

## Learning objectives

1) Get familiarised with Machine Learning terminology and terms. 
2) Learn about automated Machine Learning: choosing the best ML model 
3) Practice autoML implementations on two simple datasets, one for classification and one for regression.  

# Python package

To perform autoML, we will use the [TPOT Python package](https://epistasislab.github.io/tpot/) that has a great documentation linked to it. 

## Installation

__Option 1:__ To install TPOT using conda/mamba:  
`conda install -c conda-forge mamba && conda create --name tpot -c conda-forge tpot=0.11.6`  

A faster alternative to conda is called [mamba](https://github.com/mamba-org/mamba) and is used here. 

__Option 2:__ To install TPOT using pip:  
1. `pip install virtualenv` (if not available)  
2. `virtualenv tpot_env`  
3. `source tpot_env/bin/activate`  
4. `pip install tpot==0.11.6`  

Link to the Python package repository of TPOT: [https://pypi.org/project/TPOT/](https://pypi.org/project/TPOT/) 

# Datasets used

Datasets can be found under [`00_datasets/`](./00_datasets/) as a .csv file and a .txt file describing the dataset. 

## Breast Cancer Wisconsin Data Set (Classification problem)
Taken from the UCI Machine Learning Repository [Link](https://www.kaggle.com/datasets/uciml/breast-cancer-wisconsin-data)

## Student grades (Regression problem)

Taken from the UCI Machine Learning Repository [Link](https://archive-beta.ics.uci.edu/ml/datasets/student+performance)

# References

## Credits

__Authors:__  
- Iris van der Knaap @Library, UvA Data Science Center Digital Skills Coordinator.    
- Casper Thuis, data scientist @IBED, UvA.  
- Marc Galland, support data scientist, @SILS, UvA.    

## Sources of inspiration

1) Machine Learning at the Vrije University of Amsterdam: [https://mlvu.github.io/](https://mlvu.github.io/)  
2) Genetic programming in Python: https://towardsdatascience.com/genetic-algorithm-implementation-in-python-5ab67bb124a6

## TPOT Python package

1) [TPOT home page](https://epistasislab.github.io/tpot/)  
2) [Data Camp tutorial on TPOT](https://www.datacamp.com/tutorial/tpot-machine-learning-python#!)

## MJLAR 

[MJLAR GitHub repository](https://github.com/mljar/mljar-supervised)
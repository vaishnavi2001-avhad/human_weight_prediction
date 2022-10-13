# Human Weight Prediction


## Table of Content
  * [Introduction](#introduction)
  * [Installation](#installation)
  * [Directory Tree](#directory-tree)
  * [Result](#result)
  * [Conclusion](#conclusion)


## Introduction

The objective of this project is to predict the Human Weight Prediction using Machine Learning algorithms and to analyzing significant patterns features that results in increase in Weight.


## Installation
The Code is written in Python 3.6.10. If you don't have Python installed you can find it [here](https://www.python.org/downloads/). If you are using a lower version of Python you can upgrade using the pip package, ensuring you have the latest version of pip. To install the required packages and libraries, run this command in the project directory after [cloning](https://www.howtogeek.com/451360/how-to-clone-a-github-repository/) the repository:
```bash
pip install -r requirements.txt
```

## Directory Tree 
```

├── Human Weight Prediction.ipynb
├── README.md
├── Person_Gender_Height_Weight_Index.csv


```

## Technologies Used

![](https://forthebadge.com/images/badges/made-with-python.svg)

[<img target="_blank" src="https://upload.wikimedia.org/wikipedia/commons/3/31/NumPy_logo_2020.svg" width=200>](https://numpy.org/doc/) [<img target="_blank" src="https://upload.wikimedia.org/wikipedia/commons/e/ed/Pandas_logo.svg" width=200>](https://pandas.pydata.org/pandas-docs/stable/reference/api/pandas.DataFrame.html)
[<img target="_blank" src="https://upload.wikimedia.org/wikipedia/commons/8/84/Matplotlib_icon.svg" width=100>](https://matplotlib.org/)
[<img target="_blank" src="https://scikit-learn.org/stable/_static/scikit-learn-logo-small.png" width=200>](https://scikit-learn.org/stable/) 


## Result

Accuracy of various model used for Weight Prediction
<br>

<br>

||ML Model|	Train Accuracy|  Test Accuracy|	Train RMSE| Test RMSE
|---|---|---|---|---|---|
0|	Random Forest  |	0.907|	0.810|	0.176|	0.253|
1|	Decision Tree|	        0.872|	0.803|	0.206|	0.258|
2|	k-Nearest Neighbours Regression| 	        0.844|	0.803|	0.228|	0.257|
3| Linear Regression|	        0.798|	0.747|	0.259|	0.292|




## Conclusion
1. The final take away form this project is the working of different machine learning models on a dataset and understanding their parameters.
2. Creating this notebook helped me to learn a lot about the parameters of the models, how to tuned them and how they affect the model performance. 
3. The final conclusion on the Weight dataset are that the irrespective of Gender and Height. Index 5 is more prone to increase in Weight than remaining index.

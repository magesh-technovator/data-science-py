This is an implementation of logistic Regression based on the example used in Andrew Ng's Machine Learning Course.

Algorithm:
	Logistic Regression with Regularization is implemented in "LogReg.py" file, wich can be imported to work on any kind of logistic Regression problems.
	Note:
	1. Configure your learning rate, no. of iterations, regularization parameter
	2. Specify whether to use Optimization technique for gradient descent or use thousands of iterations(can be configured)

Dataset:
	Dataset is available as a text file "ex1data2.txt" which is then converted to .csv file using my script in my repo "data-science-py\PythonTools\Text2CSV\txtToCsv.py"

Data Preprocessing:
	Data is extracted from .csv file and preprocessed in "DataPreprocessing.py" which also has an implementation of Logistic Regression(our own algorithm) and evaluation of the model as well.

Logistic Regression using scikit-learn:
	The above procedures being directly implement in "LogReg_scikit.py" using scikit-learn's Logistic Regression model. 

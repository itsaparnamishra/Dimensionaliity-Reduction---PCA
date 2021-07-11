# Dimensionaliity-Reduction---PCA
PCA - 1 : Used breast cancer dataset from skearn library and applied PCA algorithm for dimensionality reduction method.
PCA - 2 : Used University dataset and applied PCA algorithm for dimensionality reduction step by step.


PCA steps :

a) read the dataset 
b) eliminate any categorical data and chhose numerical data in the dataframe
c) convert the numerical data into array 
d) from sklearn.preprocessing import StandardScaler / MinMaxScaler for standardisation or Normalisation.
  The main aim for standardisation or normalisation is that our features are of different units so after standardisation / normalisation the data becomes unit free 
  and the mean = 0 and standard deviation = 1.
d) from sklearn.decomposition import PCA and build pca components and create visualisation 
e) PCA is important as it eliminates the problem of multicollinearity. What is Multicollinearity? Multicollinearity occurs when two or more independent variables are highly correlated with one another in a regression model. We can also say that when we change an independent variable and expect a change in a dependent variable, we see that another independent variable has also changed. These two independent variables are now codependent, or collinear of each other which is a serious problem.
f) With fewer variables visualisation also becomes much more meaningful.
g) PCA is more useful when dealing with 3 or higher dimensional data.

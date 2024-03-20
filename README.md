# Eda-of-iris-dataset
_A basic table is a two-dimensional grid of data, in which the rows represent individual elements of the dataset, and the columns represent quantities related to each of these elements. In general, we will refer to the rows of the matrix as samples, and the number of rows as n_samples and the the columns of the matrix as features, and the number of columns as n_features._

_**Features matrix -** This table layout makes clear that the information can be thought of as a two-dimensional numerical array or matrix, called the features matrix with shape [n_samples, n_features]_

_**Target array.-** In addition to the feature matrix X, we also generally work with a label or target array, which by convention we will usually call y. The target array is usually one dimensional, with length n_samples, and is generally contained in a NumPy array or Pandas Series._
## Machine Learning Terminology

_Each row is an observation (also known as : sample, example, instance, record)_

_Each column is a feature (also known as: Predictor, attribute, Independent Variable, input, regressor, Covariate)_

_Classification is supervised learning in which the response is categorical_

_Regression is supervised learning in which the response is ordered and continuous
The classes in sklearn.neighbors can handle either Numpy arrays or scipy.sparse matrices as input. For dense matrices, a large number of possible distance metrics are supported._
_Requirements for working with data in scikit-learn_
_1) Features and response are separate objects
2) Features and response should be numeric
3)Features and response should be NumPy arrays
4)Features and response should have specific shapes_

### K - Nearest Neighbours (KNN) Algorithm

_sklearn.neighbors provides functionality for unsupervised and supervised neighbors-based learning methods. Supervised neighbors-based learning comes in two flavors: classification for data with discrete labels, and regression for data with continuous labels. Unsupervised nearest neighbors is the foundation of many other learning methods, notably manifold learningand spectral clustering._

_Despite its simplicity, nearest neighbors has been successful in a large number of classification and regression problems, including handwritten digits or satellite image scenes. Being a non-parametric method, it is often successful in classification situations where the decision boundary is very irregular_

### Linear regression

_We will start with the most familiar linear regression, a straight-line fit to data. A straight-line fit is a model of the form y=ax+b where a is commonly known as the slope, and b is commonly known as the intercept.
We can use Scikit-Learn's LinearRegression estimator to fit this data and construct the best-fit line._




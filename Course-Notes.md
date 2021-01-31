#### Notes from Lecture 1

1. Using Deepnote
-> Cloud to use coding; allows users to share and work on a notebook with many people at once.


#### Chapter 1. Preliminaries

** *Essential Python Libraries **
1. NumPy (Numerical Python)
- Provides the data structures, algorithms, and library glue needed for most scientific applications involving numerical data in python.
Contains 
-	A fast and efficient multidimensional array object *ndarray*. 
-	Functions for performing element-wise computations with arrays or mathematical operations between arrays.
-	Tools for reading and writing array-based datasets to disk.
-	Linear algebra operations, Fourier transform, and random number generation.
-	A mature C API to enable Python extensions and native C or C++ code to access NumPy’s data structures and computational facilities.
2. pandas
- The pandas name is derived from an econometric term for multidimensional structured dataset *panel data*.
- Provides high level data structures and functions designed to make working with structured or tabular data fast, easy, and expressive.
- DataFrame, a tabular, column-oriented data structure with both row and column labels, and the
Series, a one-dimensional labeled array object are most used in pandas.
3. matplotlib
- Produces plots and other two-dimensional data visualizations. 
- Widely used for publication.
4. IPython and Jupyter
-  IPython was designed from the ground up to maximize your productivity in both interactive computing and software development and encourages an *execute-explore* workflow instead of the typical *edit-compile-run* workflow of many other programming languages. 
- Jupyter project was announced in2014 as a broader initiative to design language-agnostic interactive computing tools.
- The Jupyter notebook system also allows you to author content in Markdown and HTML, providing you a means to create rich documents with code and text.
5. SciPy
- A collection of packages addressing several different standard problem domains in scientific computing.
- Examples:
**scipy.integrate** : Numerical integration routines and differential equation solvers.
**scipy.linalg** : Linear algebra routines and matrix decompositions extending beyond those provided
in *numpy.linalg*.
**scipy.optimize** : Function optimizers (minimizers) and root finding algorithms.
**scipy.signal** : Signal processing tools.
**scipy.sparse**: Sparse matrices and sparse linear system solvers.
**scipy.special**: Wrapper around SPECFUN, a Fortran library implementing many common mathematical functions, such as the gamma function.
**scipy.stats**: Standard continuous and discrete probability distributions (density functions, samplers, continuous distribution functions), various statistical tests, and more descriptive statistics
6. scikit-learn
- The premier general-purpose machine learning toolkit for Python programmers. 
Model examples: 
**Classification** : SVM, nearest neighbors, random forest, logistic regression, etc.
**Regression** : Lasso, ridge regression, etc.
**Clustering** : k-means, spectral clustering, etc.
**Dimensionality reduction** : PCA, feature selection, matrix factorization, etc.
**Model selection** : Grid search, cross-validation, metrics
**Preprocessing** : Feature extraction, normalization
7. statmodels
- A statistical analysis package that contains algorithms for classical (primarily frequentist) statistics and econometrics. Submodules example: 
**Regression models** : Linear regression, generalized linear models, robust linear models, linear mixed effects models, etc.
**Analysis of variance (ANOVA) **
**Time series analysis** : AR, ARMA, ARIMA, VAR, and other models.
**Nonparametric methods** : Kernel density estimation, kernel regression.
**Visualization of statistical model results**


#### Chapter 2. Python Language Basics, IPython, and Jupyter Notebooks

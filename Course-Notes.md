### Notes from Lecture 1

1. Using Deepnote
-> Cloud to use coding; allows users to share and work on a notebook with many people at once.


### Chapter 1. Preliminaries

#### Essential Python Libraries 
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

####

### Chapter 2. Python Language Basics, IPython, and Jupyter Notebooks

**1.	The Python Interpreter**
-	The Python interpreter runs a program by executing one statement at a time.
-	Type exit() or press Ctrl-D to exit Python interpreter and return to the command prompt.

**2.	IPython Basics**
-	Ipython shell can be launched on the command like similarly to launching the regular Python interpreter.
-	Arbitrary Python statements can be executed by typing them in and pressing Return (or Enter).
-	Jupyter project is a type of interactive document for code, text, data visualizations, and other output. It interacts with kernels and uses the IPython system for its underlying behavior.
-	Tab Completion helps user to search the namespace for any variables matching the characters the user typed. 
-	The question mark before or after a variable will display general information about the object which is called object introspection.
-	The %run command runs any file as a Python program inside the environment of your IPython session.
-	The %load command imports a script into a code cell.
-	Keyboard Interrupt will be ran when Ctrl-C is pressed while a code is running. 
-	%paste takes whatever text is in the clipboard and executes it as a single block in the shell; %cpaste is similar, except that it gives you a special prompt for pasting code into.
-	Magic commands are designed to facilitate common tasks and enable you to easily control the behavior of the IPython system. They can be viewed as command-line programs to be run within the IPython system.

**3.	Python Language Basics**
-	The Python language design is distinguished by its emphasis on readability, simplicity, and explicitness. It uses indention rather than braces.
-	Every number, string, data structure, function, class, module, and so on exists in the Python interpreter in its own “box,” which is referred to as a Python object.
-	Any text preceded by the hash mark (pound sign) # is ignored by the Python interpreter. This is often used to add comments to code.
-	You call functions using parentheses and passing zero or more arguments, optionally assigning the returned value to a variable.
-	When assigning a variable (or name) in Python, you are creating a reference to the object on the righthand side of the equals sign.
-	In contrast with many compiled languages, such as Java and C++, object references in Python have no type associated with them.
-	Objects in Python typically have both attributes (other Python objects stored “inside” the object) and methods (functions associated with an object that can have access to the object’s internal data).
-	In Python a module is simply a file with the .py extension containing Python code. We can import different variable names by using keywords. 
-	Most objects in Python, such as lists, dicts, NumPy arrays, and most user-defined types (classes), are mutable. This means that the object or values that they contain can be modified.
-	The primary Python types for numbers are int and float. An int can store arbitrarily large numbers.
-	String literals are written by using single quotes or double quotes. 
-	Boolean values are written as True of False. 
-	The str, bool, int, and float types are also functioning that can be used to cast values to those types.
-	None is the Python null value type. It is also a common default value for function arguments. 
-	The built-in Python datetime module provides datetime, date, and time types.
-	The if statement is one of the most well-known control flow statement types. It checks a condition that, if True, evaluates the code in the block that follows. Also, it can be optionally followed by one or more elif blocks and a catchall else block if all of the conditions are False. If any of the conditions is True, no further elif or else blocks will be reached.
-	for loops are for iterating over a collection (like a list or tuple) or an iterater.
-	A while loop specifies a condition and a block of code that is to be executed until the condition evaluates to False or the loop is explicitly ended with break.
-	pass is the “no-op” statement in Python. It can be used in blocks where no action is to be taken (or as a placeholder for code not yet implemented).
-	The range function returns an iterator that yields a sequence of evenly spaced integers.
-	A ternary expression in Python allows you to combine an if-else block that produces a value into a single line or expression.


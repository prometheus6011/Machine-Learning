# Supervised vs. Unsupervised Machine Learning
 
### Supervised Machine Learning
- refers to algorithms that x to y or input to output mappings
- key characteristic of supervised learning is that you give your learning algorithm examples to learn    from

##### Regression
- predict a number infinitely many possible outputs
- attach a line of best fit to a set of (x, y) data
 
##### Classification
- predict categories, small number of possible outputs
- if given two or more inputs, draw a boundary line to categorize data

### Unsupervised Machine Learning
- find something interesting in unlabeled data
- data only comes with inputs x, but not output labels y
- algorithm has to find structure in the data

##### Clustering
- groups data that have similiar characteristics together

##### Anamoly detection
- find unusual data points

##### Dimensionality reduction
- compress data using fewer numbers

# Regression Model
- regression model predicts numbers
- classification model predicts categories, small number of possible outputs
- terminology
-   training set: data used to train the model
- notation
-   $x$ is the input variable feature
-   $y$ is the output or target variable
-   $m$ number of training examples
-   ($x$, $y$) is a single training example
-   ($x^i$, $y^i$) is the $i^{th}$ training example

- traing set (features, targets) -> learning algorithm -> $f$
-   $x$ -> $f$ -> $y_{hat}$
-   feature -> model -> prediction (estimated $y$)
- $f_{w, b}(x) = wx+b$
- linear regression with one variable
-   univariate linear regression

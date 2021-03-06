## Assignments for DATA 310!
### This is where I will post my projects:

##### 1. Hello World. <img src="https://user-images.githubusercontent.com/67921324/107276197-aa160680-6a20-11eb-8ffe-8132b19cee3e.png" alt="turtle" width="120" height="80">

##### 2. [Lab 1 Working](https://colab.research.google.com/github/skrofman/Applied-Machine-Learning/blob/master/Lab1_working.ipynb)

##### 3. [Lab 2 Working](https://github.com/skrofman/Applied-Machine-Learning/blob/master/Lab2_working.ipynb)

##### 4. [Lab 3 Working](https://github.com/skrofman/Applied-Machine-Learning/blob/master/Lab3_working.ipynb)

##### 5. [Lab 4 Working](https://github.com/skrofman/Applied-Machine-Learning/blob/master/lab4_working.ipynb)

##### 6. [Midterm Working](https://github.com/skrofman/Applied-Machine-Learning/blob/master/midterm_working.ipynb)

##### 7. [Lab 5 Working](https://github.com/skrofman/Applied-Machine-Learning/blob/master/lab5_working.ipynb)

##### 8. [Lab 6 Working](https://github.com/skrofman/Applied-Machine-Learning/blob/master/Lab6_working.ipynb)

##### 9. [Lab 7 Working](https://github.com/skrofman/Applied-Machine-Learning/blob/master/lab7_working.ipynb)

##### 10. [Final Working](https://github.com/skrofman/Applied-Machine-Learning/blob/master/final_project.ipynb)

***

## Lectures:
[Lecture 1:](https://github.com/skrofman/Applied-Machine-Learning/blob/master/DATA_310_Lecture_1.ipynb)
   * Types of Data
   * Basic Python
      * Graphing
        * iloc, arange
      * Importing data
        * numpy, pandas
      * Dealing with discrete (nominal) data
      * How to replace missing values
         *  NaN

[Lecture 2:](https://github.com/skrofman/Applied-Machine-Learning/blob/master/DATA_310_Lecture_2.ipynb)
  * Functions in Python
  * Probability
    * Bayesian Theorem
    * Monte Carlo Simulation
    * Histograms, Normal Distributions

[Lecture 3:](https://github.com/skrofman/Applied-Machine-Learning/blob/master/DATA_310__Lecture_3.ipynb)
  * Imputations
  * Random
  * Scaling
  * More Monte Carlo


[Lecture 4:](https://github.com/skrofman/Applied-Machine-Learning/blob/master/DATA_310_Lecture_4.ipynb)
  * More More Monte Carlo
  * More Probability


[Lecture 5:](https://github.com/skrofman/Applied-Machine-Learning/blob/master/DATA_310_Lecture_5.ipynb)
  * More More More Monte Carlo
    * Iterations with Monte Carlo
  * Turtle drawings and animations
  
[Lecture 6:](https://github.com/skrofman/Applied-Machine-Learning/blob/master/DATA_310_Lecture_6_Spring_2021.ipynb)
  * Data Standardizations
    * Quantiles
    * Displaying Quantiles
  * Ordinary Least Squares Regression
  
[Lecture 7:](https://github.com/skrofman/Applied-Machine-Learning/blob/master/DATA_310_Lecture_7_Spring_2021.ipynb)
  * More Data Standardizations
    * More Quantiles
  * Linear Fit

[Lecture 8:](https://github.com/skrofman/Applied-Machine-Learning/blob/master/DATA_310_Lecture_8_Spring_2021.ipynb)
  * Ordinary Least Squares Regression (Linear Regression)
  * Linear Fit and Slope

[Lecture 9:](https://github.com/skrofman/Applied-Machine-Learning/blob/master/Data_310_Lecture_9_Spring_2021.ipynb)
  * Ordinary Least Squares (OLS)
  * Multiple Linear Regression (Linear models with more features)
  * Linear vs Non-linear models

[Lecture 10:](https://github.com/skrofman/Applied-Machine-Learning/blob/master/DATA_310_Lecture_10_Spring_2021.ipynb)
  * Linear Regression and Residuals
  * Linear vs Non-linear models
    * When OLS may not work
    * A solution for rank defficient Multiple Linear Regression: Regularization
    * Main Idea: minimize the sum of the square residuals plus a constraint on the vector of weights 

[Lecture 11:](https://github.com/skrofman/Applied-Machine-Learning/blob/master/DATA_310_Lecture_11_Spring_2021_(1).ipynb)
  * What does Rank Deficiency means and why we need Regularization
  * L1 Regdularization (LASSO)
  * L2 Regularization (RIDGE)
  * Elastic Net Regularization
  * Main idea: if we get strong multiple linear correlations among the input features, we NEED regularization because we are in "rank deffficient situation"
  * Polynomial Regression

[Lecture 12:](https://github.com/skrofman/Applied-Machine-Learning/blob/master/DATA_310_Lecture_12_Spring_2021(1).ipynb)
  * The Effects of Regularization
    * How do we know we may need regularization?
  * Why we need data scaling?
    * In linear models we need scaling so we can combine feature values that are on the same units of measurement.
  * Polynomial Regression
    * Main idea: Linear combination of different powers of the feature values.

[Lecture 13:](https://github.com/skrofman/Applied-Machine-Learning/blob/master/DATA_310_Lecture_13_Spring_2021.ipynb)
  * Elastic Net Regularization
  * Polynomial Regression
  * How do we know we are on the right track?
   * Use Train and Test Sets
   * Use Regularization.
   * Compute (R)MSE on the test set.
   * Compute the coefficient of determination on the test set.
   * Determine the normality of the residuals by using a test statistic (such as Shapiro-Wilk or Kolmogorov-Smirnov), density plots and quantile-quantile plots.
 * Model Validation via k-Fold Cross-Validations

[Lecture 14:](https://github.com/skrofman/Applied-Machine-Learning/blob/master/DATA_310_Lecture_14_Spring_2021(1).ipynb)
  * Validation- we want an unbiased estimator
  * Overfit: if MSE on the Train set is much lower than the MSE on the Test set.
  * Model Validation via k-Fold Cross-Validations

[Lecture 15:](https://github.com/skrofman/Applied-Machine-Learning/blob/master/DATA_310_Lecture_15_Spring_2021.ipynb)
  * Model Validation via k-Fold Cross-Validations

[Lecture 16:](https://github.com/skrofman/Applied-Machine-Learning/blob/master/DATA_310_Lecture_16_Spring_2021.ipynb)
  * Model Validation via k-Fold Cross-Validations
    * Make a cross-validated comparison between SVR, OLS, Lasso and RIDGE regression.
  * Support Vector Regression
  * Regression Trees
    * Main Idea: Things are different for subsets in the data. Nonlinear relationships may exist and we should be able to accommodate them.
  * Ensemble Learning - Random Forests
    * More resilient to outliers, better for external validity. You can also provide information on how certain or uncertain you are about a result.

[Lecture 17:](https://github.com/skrofman/Applied-Machine-Learning/blob/master/DATA_310_Lecture_17_Spring_2021.ipynb)
  * Support Vectors is a method used in Machine Learning for both regression and classification problmes.
    * The main idea is to map the input features into a higher dimensional space and then, in that higher dimensional space, address the problem to solve.
    * We have at least two different hyperparameters in this case such as 𝜖 and  𝐶.
  * Regression Trees
  * Ensemble Learning - Random Forests
  * Support Vector Regression with Slack Variables
  * Decision Tree Regression
  * Random Forest

[Lecture 18:](https://github.com/skrofman/Applied-Machine-Learning/blob/master/DATA_310_Lecture_18_Spring_2021.ipynb)
  * Support Vector Regression
  * Regression Trees
  * Ensemble Learning - Random Forests
  * Support Vector Regression with Slack Variables
  * Decision Tree Regression
  * Random Forest

[Lecture 19:](https://github.com/skrofman/Applied-Machine-Learning/blob/master/DATA_310_Lecture_19_Spring_2021.ipynb)
  * Support Vector Regression
  * Regression Trees
  * Random Forests
  * KFold Validation

[Lecture 21:](https://github.com/skrofman/Applied-Machine-Learning/blob/master/DATA_310_Lecture_21_Spring_2021.ipynb)
  * Root Mean Squared Error
  * Do we need scaling for Random Forest? NO!!
  * Kfold example

[Lecture 22:](https://github.com/skrofman/Applied-Machine-Learning/blob/master/DATA_310_Lecture_22_Spring_2021.ipynb)
  * Classification Algorithms
    * We want to predict the corect class given the input features
  * Logistic Regression
  * K-Nearest Neighbors Algorithm
    * The classification is decided by the votes of the  𝑘 -nearest neighbors, an odd natural number such as  2𝑝+1 .
    * The votes can be weighted (if we want) by the inverse of the Euclidean distance.

[Lecture 23:](https://github.com/skrofman/Applied-Machine-Learning/blob/master/DATA_310_Lecture_23_Spring_2021(1).ipynb)
  * Classification Algorithms
  * Confusion Matrix
    * Visualization of the Classification Model
  * KNN
  * Support Vector Machine Classification
  * Naive Bayes Classifier
  * Decision Tree classifier
  * Random Forest

[Lecture 24:](https://github.com/skrofman/Applied-Machine-Learning/blob/master/DATA_310_Lecture_24_Spring_2021.ipynb)
  * Classification Algorithms - Real Data Application with Validation (Breast Cancer Dataset)
    * Creating a validation function
    * [Classification Overview](https://github.com/skrofman/Applied-Machine-Learning/blob/master/Classification_Techniques_Examples.ipynb)
    * [Classification Comparison (NB, DT, RF)](https://github.com/skrofman/Applied-Machine-Learning/blob/master/DATA_310_Classification_3_classes_NB_DT_RF.ipynb)

[Lecture 25:](https://github.com/skrofman/Applied-Machine-Learning/blob/master/DATA_310_Lecture_25_Spring_2021.ipynb)
  * SVM with Radial Basis Function Kernel (the kernel "trick")
  * Naive Bayes Classifier
  * Breast Cancer Dataset Validation Function
  * The Receiver Operating Characteristic (ROC)
    * False Positives/Negatives

[Lecture 27:](https://github.com/skrofman/Applied-Machine-Learning/blob/master/DATA_310_Lecture_27_Spring_2021.ipynb)
  * Example of Artificial Neural Network (based on SKLearn library)

[Lecture 28:](https://github.com/skrofman/Applied-Machine-Learning/blob/master/DATA_310_Lecture_29_(Notebook_I)_Spring_2021.ipynb)
  * Neural Networks for Classification
  * The Rosenbrock Function
  * Convolutional Neural Networks Example

[Lecture 29:](https://github.com/skrofman/Applied-Machine-Learning/blob/master/DATA_310_Lecture_29_(Notebook_II)_Spring_2021.ipynb)
  * Examples of optimization with different algorithms
  * Convolutional Neural Network on the MNIST Data

[Lecture 30:](https://github.com/skrofman/Applied-Machine-Learning/blob/master/DATA_310_Lecture_30_(Notebook_I)_Spring_2021.ipynb)
  * Neural Networks for Classification
  * Examples of optimization with different algorithms
  * Convolutional Neural Networks Example

[Lecture 31:](https://github.com/skrofman/Applied-Machine-Learning/blob/master/DATA_310_Lecture_31_Spring_2021.ipynb)
  * Examples of optimization with different algorithms
  * Convolutional Neural Networks Example

[Lecture 32:](https://github.com/skrofman/Applied-Machine-Learning/blob/master/DATA_310_Lecture_32_Spring_2021.ipynb)
  * Convolutional Neural Networks
    * Image Recognition Example
    * Another Example - Cifar10

[Lecture 33:](https://github.com/skrofman/Applied-Machine-Learning/blob/master/DATA_310_Lecture_33_Spring_2021_(1).ipynb)
  * Another design example for CNN's with the MNIST data (hint: the accuracy improves)
  * Dimensionality Reduction
    * Algorithms for feature selection and feature extraction.
    * Regression Problems
    * Classification Problems

[Lecture 34:](https://github.com/skrofman/Applied-Machine-Learning/blob/master/DATA_310_Lecture_34_Spring_2021.ipynb)
  * Dimensionality Reduction
    * Big data is characterized not just by a large number of observations, but also by very large number of input features. Very often the problem is that not all features in the data are important for solving the regression or the classification problems. At the same time, it is difficult to computationally accomodate too many input features into the model.
    * Feature Selection: What data should you put into your model? For linear regression models the variable selection approaches include backward elimination, forward selection, bidirectional elimination and penalized regression techniques such as LASSO or Elastic Net.
    * General Heuristics: Reducing the number of variables can greatly aid interpretability, reduce the chances your violating key assumptions, and let you go beyond simple prediction. Furthermore, smaller models (parsimonious models) are easier to update and interpret - every column of data you add is a column of data you have to collect in the future if you ever want to use your model again. Less is better - don’t invest resources to collect data you don’t need!
  * Penalized regression can be used for variable selection
  * Relationship between Coefficients and Regularization

[Lecture 35:](https://github.com/skrofman/Applied-Machine-Learning/blob/master/DATA_310_Lecture_35_Spring_2021.ipynb)
  * Dimensionality Reduction and Feature Extraction
    * We can summarize the contribution of a subset of features based on finding the direction of the biggest variablity or variance. Such directions, that summarize most of the variablility in the data, are called principal components.
  * Classification Problems

[Lecture 36:](https://github.com/skrofman/Applied-Machine-Learning/blob/master/DATA_310_Lecture_36_Spring_2021.ipynb)
  * Linear Projective Methods
  * Main Common Idea: Preserve important qualitative properties from the original features and summarize them by using fewer dimensions. The projective methods are primarily used for classification problems.
  * Principal Component Analysis
  * Linear Discriminant Analysis
  * Nonlinear Projective Methods
    * 1. t-SNE (t-distributed Stochastic Neighbor Embedding)
    * 2. UMAP (Uniform Manifold Approximation and Projection)

[Lecture 37:](https://github.com/skrofman/Applied-Machine-Learning/blob/master/DATA_310_Lecture_37_Spring_2021.ipynb)
  * Grid Search Algorithms
    * Main Idea: We can use algorthms for discrete optimization in order to estimate the value for the hyperparameters and thus complete the model selection process.
  * Swarm Algorithms - Particle Swarm Optimization
  * Simulated Annealing

[Lecture 38:](https://github.com/skrofman/Applied-Machine-Learning/blob/master/DATA_310_Lecture_38_Spring_2021.ipynb)
  * Natural Language Processing
  * Use speech and words along with computer run algorithms.
  * Regular Expressions (regex)
  * The Bag of Words model (BoW)
  * NLTK Examples
    * Application to Amazon customer reviews
      * Naive Bayes Classifier and Random Forest Classifier
    * Application to wine ratings based on customer reviews

[Lecture 39:](https://github.com/skrofman/Applied-Machine-Learning/blob/master/DATA_310_Lecture_39_Spring_2021.ipynb)
  * More Natural Language Processing (NLP)
  * Probabilistic Language Modeling
  * Text Pre-Processing
  * CBOW (continuous Bag of Words)
  * Global Vectors for Word Representations (GloVe)
  * Word2Vec

***

<a href="https://drive.google.com/uc?export=view&id=1BdkPd5TPel2dvpmKRVGs9qYYfgkMvgha">
  <img src="https://drive.google.com/uc?export=view&id=1BdkPd5TPel2dvpmKRVGs9qYYfgkMvgha" width="300" height="400">
  
  ## Other Useful Stuff:
  [Poisson Python Function](https://github.com/skrofman/Applied-Machine-Learning/blob/master/Poisson.ipynb)

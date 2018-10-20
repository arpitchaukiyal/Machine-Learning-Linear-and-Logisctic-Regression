# Machine Learning - Linear and Logisctic-Regression <br>

**Linear Regression**: Linear regression attempts to model the relationship between two variables by fitting a linear equation to observed data. One variable is considered to be an dependent variable, and the other is considered to be explanatory variable.<br>
**Logistic Rgression**: Logistic regression predicts the probability of an outcome that can only have two values (i.e. a dichotomy). The prediction is based on the use of one or several predictors (numerical and categorical).<br>
In this project I have used [Student Performance dataset](https://archive.ics.uci.edu/ml/datasets/Student+Performance#) to predict the final grades of the student depending up the eplanatory variables present in the dataset.<br>
<br>
Converted this problem into a binary classification problem. The target variable should have two grade categories.<br>
**1**: for all marks greater than or equal to median: *Good_Marks*<br>
**0**: for all marks less than median: *Not_Good_Marks*<br><br>
Implemented Logistic regression for this classification problem.<br><br>
Experimented with various model parameters for both linear and logistic regression and reported the findings as how the error varies for train and test sets with varying these parameters. Implemented the ``Gradient Boosting`` algorithms as learning method.<br>
![alt text](https://github.com/arpitchaukiyal/Machine-Learning-Linear-and-Logisctic-Regression/blob/master/costvsiterarion2.png, "Graph of Cast vs Iterations for Different Values of Alpha")

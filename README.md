# Multiple-Linear-Regression
In statistics, linear regression is a linear approach to modeling the relationship between a scalar response (or dependent variable) and one or more explanatory variables (or independent variables). The case of one explanatory variable is called simple linear regression. For more than one explanatory variable, the process is called multiple linear regression.

Multiple Linear Regression (MLR) method helps in establishing correlation between the independent and dependent variables.

I have develop a multiple linear regression on a real world dataset which is about car pricing prediction.

Firstly, I have find out the statistics of every atrribute and the null values(missing value) in the dataset.

Then, find out the relation between every attritubes by using seaborn graphs and matplotlib.

This dataset is mixture of both numerical data and categorical data. For categorical data, encoding is very necessory.
So, I have used One Hot Encoding.

Finding corelation is also very important so I cannot ignore this and applied it in this problem.

After finding corelation, i have assigned a threashold of 0.3 such that I find out the attributes who's corelation is greater than 0.3.

Then, I have develop a multiple linear regression with only those attributes which are highly corelated with the predicted variable.

We get a multiple regression model. Now I find out the following to find out the goodness of my model;
1. R-Square value
2. Root Mean Square Error
3. Mean Absolute Err
4. The Model Score

all the above error finding techniques shows the goodness of the model which mean model is good.

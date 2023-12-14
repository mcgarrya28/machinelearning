# Machine Learning

### This repository relates to all tasks and project assigned in the machine learning module. The tasks and project are written in juypther notebooks. 

The Python libraries required are part of the Anaconda package and are preinstalled.

__Required Packages:__

- Numpy
- scipy
- Seaborn
- Matplotlib
- sklearn
- Pandas


## __1. Newton's Method__

This begins by setting the function 'newton' with the parameters:

  (i) 'x' which represents the number that we want to find the square root.
  
  (ii) 'guess' which is an initial attempt at approximating the square root and represented as a float

  (iii) 'tol' which is the acceptable tolerance for the precison for the results.


x is the number for which we want to find the square root, guess is the current guess, and next_guess is an improved guess.

The function is set to iterate through the formula using a 'While Loop' until it reaches an acceptable level of precision where the difference between guess and next_guess is smaller than a specified tolerance (e.g., 1e-10 or a smaller value).




__Reference Material__
*  https://thirumalai2024.medium.com/python-program-to-find-square-root-of-the-number-using-newtons-method-937c0e732756



__2. Chi Square__

The chi-squared statistic, a measure of how far the observed values are from the expected values. Larger values indicate a greater difference between observed and expected, suggesting a significant association.

The p-value associated with the test. This tells you the probability of observing the data if there is no association between the categorical variables. A small p-value (usually less than 0.05) indicates that you can reject the null hypothesis of independence.

 Degrees of freedom. This is calculated based on the dimensions of the contingency table and is used to determine the critical value from the chi-squared distribution.

 Ann array containing the expected frequencies under the assumption of independence. It shows what you would expect to observe if there were no association between the variables.

 After running this code, you can interpret the results. If the p-value is less than your chosen significance level (commonly 0.05), you may reject the null hypothesis of independence and conclude that there is evidence of a significant association between the categorical variables. The expected frequencies can be used to explore where the differences between observed and expected values lie in the contingency table.

 __3. Pengiun Data Set__

 The code performs an independent two-sample t-test using SciPy's ttest_ind function. This test is used to determine if there is a significant difference between the means of two independent groups in this case the body mass of male and females. The code assumes that male_body_mass and female_body_mass are arrays or lists containing the body masses of males and females, respectively.

 Within the code the equal_var=False argument indicates that the variances of the two groups are not assumed to be equal.

 After running this code, you'll get the t-statistic and p-value, which you can use to determine whether there is a statistically significant difference between the means of the two groups. Typically, if the p-value is below a chosen significance level (0.05), you reject the null hypothesis and conclude that there is a significant difference. In this case the p value is               1.8677596749117468e-28.


__4. Iris Dataset - Setosa__

 Here, using Seaborn and Matplotlib to create a pairplot for the Iris dataset. This pairplot is used to visualize the relationships between different features in the dataset, with different species represented by different markers.

 The code then goes on to create a number of individual boxplots to show the distribution of sepal length, sepal width, petal length, and petal width for each species in the dataset, helping to identify potential differences or patterns in the data.

 __5. Principal Component Analysis on the iris data set__

 PCA aims to transform the original features of a dataset into a new set of uncorrelated features called principal components. These components are ordered in terms of the amount of variance they capture in the data. The first principal component captures the maximum variance, the second principal component,uncorrelated with the first, captures the second most significant variance, and so on.

After performing PCA on the Iris dataset, you can analyse the contribution of each principal component to the total variance. This analysis helps in understanding which features contribute the most to the variance in the data and may facilitate dimensionality reduction for further analysis or visualisation.
 




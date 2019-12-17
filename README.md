# concrete-regression

Develop Multivariate Regression Model

Our Dependent variable is CMS and all others are independent variables.

# The Multivariate Linear Regression model can be depicted as:

CMS= 35.95 + 13.03*(Cement) + 8.95*(Blast) + 5.96*(Fly Ash) – 2.85*(Water) + 1.74*(Superplasticizer) + 1.59*(CA) + 2.04*(FA) + 7.22*(Age)

# Evaluate the Algorithm (i.e. performance)

The R2 value is 62% which indicates a poor linear model.

Along with this, as the value of root mean squared error is 10.66, which is more than 10% of the mean value of the percentages of CMS (35.817961), our algorithm was not very accurate but can still make reasonably good predictions. For our algorithm to be accurate and to perform well the mean value of the percentages of the dependent variable should be less than the Root Mean Squared Error.

# Summarizing key insights based on key findings

With the model that we have built, we can see that the variable that impacts the most positively is Cement, Blast, Age and Fly Ash in descending order. Whereas Water is the only variable that has a negative impact. 

This depicts that the strength of the concrete can be altered mainly by Cement, Blast, Age, Fly Ash, and Water. All these variables impact differently on the Concrete Compressive Strength based on its nature.

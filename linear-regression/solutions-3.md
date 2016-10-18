# Solution to lesson 3

# 1. 
- The indivisual p-values in table 3.4 help us answer the question as to which medium is important in predicting sales.
- It tests the following null hypotheses:
H0: beta1 = 0, H0: beta2 = 0, H0: beta3 = 0
- We reject the null hypothesis for the first two hypotheses.
- TV and radio are significany in predicting sales
- We may coclude that newspaper budget is not significant in predicting sales

# 2.
KNN Classification:
Classifies a new point as the class with the highest probability among the k nearest neighbours to that point

KNN Regression:
Predicts a value Y for a given feature vector X as the average of the response Y for all X in the neighbourhood of that point

# 3.

a. (iii) 
- For males:   Y = (beta0) + beta1 * X1 + Beta2 * X2 + Beta4 * X2 * X1
- For females: Y = (beta0 + beta3 + beta5 * X1 )+ beta1 * X1 + Beta2 * X2 + Beta4 * X2 * X1

the part in parentheses is what differentiates the two
beta0 = 50
beta0 + beta3 + beta5 * X1 = 85 - 10X1
If GPA is sufficiently high, the male offset will exceed that of the female.

b. Y = beta0 + beta3 + (beta1 + beta5) * X1 + beta2 * X2 + beta4 * X2 * X1 = 137.1

c. False-the coefficient indicates the strength of the interaction. Evidence of the interaction is indicated by the p-value

# 4.
a. The training residual sum of squares for the cubic regression would be less because the cubic model would overfit to the training data.
b. The test RSS for the cubic regression would be more because the cubic model would overfit the training data and cannot generalize to the test data
c. The training RSS for the cubic model would be less as it better fits the data
d. the test RSS for the cubic model would also be less as it better fits the data

# 5.
a. The training RSS for he cubic model would be lower than the RSS for the linear model as the cubic model will fit the noise in the data and will therefore overfit the data resulting in lower training MSE.
b. The cubic model will have a higher test RSS as this model does not truly fit the pattern in the data and cannot generalize to test data.
c. The training RSS for the cubic model would be lower as it better fits the data
d. We cannot determine whether the test RSS would be different. this depends on the test data. If the data is closer to linear, then the cubic model will have a higher test RSS.
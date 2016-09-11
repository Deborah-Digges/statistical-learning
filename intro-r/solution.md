# Solution for chapter 2

## 1.

a. n is extremely large and p is small - a more flexible model is better to take advantage of the large amount of data

b. p is large, n is small - a more flexible model is worse as it may fit to the noise in the small amount of data

c. the relationship between the predictors and the response is highly non linear - a more flexible model would be better as it would helo to better approximate a function for this complex relationship

d. variance(epsilon) is high - a more flexible model would be worse as it may fit to the noise in the data rather than the actual signal

## 2. 

a. - regression problem as the response variable(CEO salary) is quantitative
- we are interested in inference as we want to know which factors affect the CEO salary and how
- each observation is a firm. n = 500 (number of firms)
- p is the number of predictors(3) - profit, number of employees, industry

b. - classification
- prediction
- n = 20(products)
- p = 13

c. - regression
- prediction
- n = 52(weeks of 2012)
- p = 3

## 4.
a. - will a patient survive 
- will a company succeed
- identify the parts of speech
All of the above are prediction

b. - company returns based on things like number of employees, advertising, money spent on innovation
- students' marks based on input like hours studied, hours of exercise, hours of TV and computer gaming
- house value given things like the locality, size of the house, age
these are all prediction

c. - customer segmentation
- land classification
- gene clustering

## 5. 
More flexible approach
- suitable when the underlying data is highly non linear
Less flexible
- suitable when the underlying data is not very non linear
- suitable when the end goal is inference

## 6. in the parametric approach, we predetermine the functional form f and estimate f by estimating a set of parameters
Advantages
- Reduces the problem of estimating an arbitrary function f to the problem of estimating a set of parameters
- Generally requires less data than non parametric models
Disadvantages
- We may assume the wrong functional form for f which does not properly fit the data

## 7. 
uclid_dist([0,3,0], [0, 0, 0])
3

uclid_dist([2, 0, 0], [0, 0, 0])
2

uclid_dist([0, 1, 3], [0, 0, 0])
3.16

uclid_dist([0, 1, 2], [0, 0, 0])
2.23

uclid_dist([-1, 0, 1], [0, 0, 0])
1.414

uclid_dist([1, 1, 1], [0, 0, 0])
1.732

k=1 => Green
k=3 => Red
We would expect the best value for k to be small because as 1/k increases, the flexibility increases
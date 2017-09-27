#### 1. A regression tries to predict student GPA percentile (on a zero-100 scale) from their SAT-Math score. You are to make the relevant prediction for a student who has a SAT math score of 600 (note that SAT scores go from 200 to 800). He would be expected to be closest to the -- percentile of GPA on the basis of the regression output below:
| Feature | Coefficient | t-stat |
| Intercept | 20 | 0.3|
| SAT-Math | 0.1 | 5.0|
R-squared: 0.36
  * A. 10th percentile 
  * B. 20th percentile 
  * C. 60 th percentile 
  * D. 80th percentile 
  * E. 100th percentile
Answer: D. Write the regression equation as GPA percentile = 20 + 0.1 * SAT math, so
GPA percentile = 20 + 0.1 * 600 = 80

#### 2. We know, on the basis of the above regression, that the strongest part of the explanation of the score
is due to the coefficent of the:
  * A. intercept term, because the coefficient is larger.
  * B. intercept term, because the t-stat is smaller
  * C. SAT-math term, because the coefficient is smaller.
  * D. SAT-math term, because the t-stat is larger.
Answer: D. The size of the t-statistic, not the size of the coefficient, indicates the explanatory strength of a
variable.

#### 3. We know that the correlation coefficient between SAT-math and the GPA percentile is closest to:
  * A. zero 
  * B. 0.30 
  * C. 0.60 
  * D. 0.80 
  * E. 1.00
Answer: C. The R-squared is the square of the correlation coefficent r, so r = sqrt(.36) = 0.6

#### 4. If we knew that the SD of the SAT math score was 100 and the SD of the GPA percentile was 25, wecould calculate the standard error of the regression (the RMSE) to be closest to (look at the next question for a hint at the formula):
  * A. 20 
  * B. 40 
  * C. 60 
  * D. 80 
  * E. 100

#### 5. The formula for the standard error of the regression (RMSE) is
  * A. (1 - R2) * SD(x)
  * B. Covariance (x,y) / SD(x) * SD(y)
  * C. sqrt(1- R2) * SD(y)
  * D. sqrt(1-R2) * SD(x)
  * E. r * SD(y) / SD(x)
Answer: C. The standard error of the regression gets smaller as the R-squared gets larger; if R-sq = 1, error = 0

#### 6. The formula for the slope of the regression line is (same options as the previous question)
  * A. (1 - R2) * SD(x)
  * B. Covariance (x,y) / SD(x) * SD(y)
  * C. sqrt(1- R2) * SD(y)
  * D. sqrt(1-R2) * SD(x)
  * E. r * SD(y) / SD(x)
Answer: E

#### 7. The formula for the correlation coefficient is (same options as the previous question)
  * A. (1 - R2) * SD(x)
  * B. Covariance (x,y) / SD(x) * SD(y)
  * C. sqrt(1- R2) * SD(y)
  * D. sqrt(1-R2) * SD(x)
  * E. r * SD(y) / SD(x)
Answer: B

#### 8. The regression line is drawn so that:
  * A. The line goes through more points than any other possible line, straight or curved
  * B. The line goes through more points than any other possible straight line.
  * C. The same number of points are below and above the regression line.
  * D. The sum of the absolute errors is as small as possible.
  * E. The sum of the squared errors is as small as possible.
Answer: E

#### 9. In a regression, the --- that the standard error of the regression is, the greater the accuracy of the
prediction will be.
  * A. smaller.
  * B. larger
  * C. we do not know unless we know whether the slope of the regression is positive or negative.
Answer: A.

#### 10. In order for the regression technique to give the best and minimum variance prediction, all the following conditions must be met, EXCEPT for:
  * A. The relation is linear.
  * B. We have not omitted any significant variable.
  * C. Both the X and Y variables (the predictors and the response) are normally distributed.
  * D. The residuals (errors) are normally distributed.
  * E. The variance around the regression line is about the same for all values of the predictor.
Answer: C

#### 11. If a regression has the problem of heteroscedasticity,
  * A. The predictions it makes will be wrong on average.
  * B. The predictions it makes will be correct on average, but we will not be certain of the RMSE
  * C. It will also have the problem of an omitted variable or variables.
  * D. It will also be based on a non-linear equation.
Answer: B. Heteroscedasticity implies that the variance will differ for different values of the regressor.

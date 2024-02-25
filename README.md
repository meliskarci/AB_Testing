# AB Testing

 ### What is AB Testing?
Fundamentally, an A/B test is the comparison of means and it compares two different groups. In concept,
it is a user experience research methodology. "A" represents a group and "B" represents another group that includes
same variable for comparison.


### AB Testing Process ###

# 1. Construct Hypotheses
# 2. Assumption Checking
#   - Normality Assumption (Shapiro-Wilk)
#   - Homogeneity of Variance (Levene)
# 3. Hypothesis Testing
# 4. Interpret Results Based on the p-value.


### Business Problem ###
########################

# Facebook offers various bidding strategies, and X company is interested in comparing two different bidding methods.
# The company has two datasets that include variables such as "impression" "click" "purchase" and "earning".
# Target variable is "purchase" and it is company's success criterion.




### Summary of A/B Testing and Interpretation of Results ###

The Shapiro-Wilk test was applied to check if the observations followed a normal distribution.
Since the variables exhibited a normal distribution, it was decided to apply a parametric test,
which is the T-test. The homogeneity of variances assumption was tested using the Levene test,
and it was found that the variances were homogeneous, as stated within the relevant T-test.


Due to p value (0.349) is greater than 0.05 H0 hypothesis can not be denied, in simple terms, difference between
means of the two groups occured due to chance, there is no statistically significant difference.
When the means of the control and test applications were compared,
it was determined that the difference in means was due to chance, and therefore,
there was no need for the new test application. #

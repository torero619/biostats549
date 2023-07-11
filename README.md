# biostats549
# Module 1

# Module 2
# Module 3

## Exercises for Section 6.1 (Question 1) on page 196

### 1. Use the Hospital charges worksheet in the file Chpt 4-1.xls.
   
   a. Calculate the mean and median for Age, LOS, and Charges by using the =AVERAGE() and =MEDIAN() functions.
   
   b. Based on these, in what direction are these distributions skewed, if at all?
   
   c. Calculate the variance and standard deviation of Age, LOS, and Charges by using the formulas in Equations 6.3 and 6.4.
   
   d. Calculate the variance and standard deviation of Age, LOS, and Charges by using the =VAR() and =STDEV() functions. Make sure that the results in (c) match those in (d)

## Exercises for Section 6.2 (Questions 1) on page 208

### 1. Use the Hospital charges worksheet in the file Chpt 4-1.xls.
   
   a. Based on the mean and standard deviation for LOS, generate a frequency distribution in terms of 1 standard deviation unit around the mean.
   
   b. Develop the Excel chart to show the frequency distribution generated in (a).

## Exercises for Section 7.1 (Question 1) on page 243

### 1. Using =TINV() and Equation 7.1, calculate the exact 95 percent upper and lower confidence limits for the following:

   a. n = 40, mean = 32, S.E. = 1.23

   b. n = 40, mean = 32, S.E. = 3.23

   c. n = 140, mean = 32, S.E. = 1.23

   d. n = 140, mean = 32, S.E. = 3.23

## Exercises for Section 9.1 (Questions 1 and 2) on page 302

### 1. Calculate the t value for the following hypotheses, given the sample outcomes indicated.

   a. H0∶ 𝜇 = 11, H1∶ 𝜇 ≠ 11, x = 12.2 , standard deviation = 8.9, n ≠ 40.

   b. H0∶ 𝜇 = 11, H1∶ 𝜇 ≠ 11, x = 14.0 , standard deviation = 8.9, n = 40.

   c. H0∶ 𝜇 = 11, H1∶ 𝜇 ≠ 11, x = 13.7, standard deviation = 8.9, n = 40.

   d. H0∶ 𝜇 = 234, H1∶ 𝜇 ≠ 234, x = 228.4, standard deviation = 40.53, n = 120.

   e. H0∶ 𝜇 = 234, H1∶ 𝜇 ≠ 234, x = 226.4, standard deviation = 40.53, n = 120.

   f. H0∶ 𝜇 = 234, H1∶ 𝜇 ≠ 234, x = 226.4, standard deviation = 40.53, n = 120.

### 2. Determine the probability of t in each example in Exercise 1, and decide for each whether you would accept or reject H0.


# Module 4
## 10.1 (Question 1)
### 1. Use the data on the Costs worksheet of Chpt 10–1.xls, and replicate the calculations in Figure 10.3.


   a. Use a pivot table and the formula in Equation 10.1 to calculate the between group sum of squares (SSB) for the costs in the four hospitals.

$$SS_B=\sum_{j=1}^{n}n_j(\overline{x}_{j}-\overline{\overline{x}})^{2}$$

   b. Use the results of the pivot table from (a) and the formula in Equation 10.2 to calculate the within groups sum of squares (SSW) for the costs in the four hospitals.

$$SS_W=\sum_{j=1}^{m}\sum_{i=1}^{n_j}(x_{ij}-\overline{x}_j)^{2}$$

   c. Use the formula in Equation 10.3 to calculate the total sum of squares (SST) for the costs in the four hospitals.

$$SS_T=\sum_{j=1}^{m}\sum_{i=1}^{n_j}(x_{ij}-\overline{\overline{x}}_j)^{2}$$

   d. Determine the appropriate degrees of freedom, and use the formula in Equation 10.4 to calculate the F value for a test of the null hypothesis that the mean costs in the four hospitals are all the same.

   e. Use the =FDIST() function to obtain the probability of the F value, and draw the appropriate conclusion in regard to the null hypothesis
$$F= \frac{MS_B}{MS_W}$$

## 11.1 (Question 1 and 2)

### 1. Use the data on the Hospital charges worksheet of Chpt 4-1.xls, and generate the following xy charts. (The first variable in each case should be considered the independent variable.)

   a. Age with LOS

   b. Age with Charges

   c. Charges with Medicare

### 2. Which, if any, of the charts in (a), (b), or (c) (preceding) appear to be the best to fit a linear model and why? Which appear to be the worst?

## 11.5 (Question 1)

### 1. Use the data on the Cost worksheet of Chpt 9-1.xls that show the hospital cost for a randomly selected sample of 34 women and 34 men.
   
   a. Rearrange the data so that they can be analyzed using regression, and add an independent variable that is 1 for women and 0 for men
   
   b. Test the hypothesis that the cost for women is equal to the cost for men (against the alternative that they are not equal) using regression.

# Module 5

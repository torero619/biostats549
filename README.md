# biostats549
[Textbook](https://iro.uiowa.edu/esploro/outputs/textbook/9984376757802771)

# Module 1

## Exercises for Section 3.2 (Questions 1 & 2) on page 93

### 1. Use the data set from Figure 3.2 (Chpt 3-1.xls) and do the following:

   a. Use the =RAND() function to draw a random sample of 5 patients from the 20 patients given in the file.
   
   b. Use the uniform distribution option in the Data Analysis add-in to generate random numbers between 0 and 1, and use these numbers to select a simple random sample of 7 patients from the 20 in the file. Specify a random seed of 1325.
   
   c. Use the normal distribution option in the Data Analysis add-in to generate random numbers with a mean of 0 and a standard deviation of 1, and use these numbers to select a simple random sample of 10 patients from the 20 in the file. Specify a random seed of 7936.

### 2. The file Chpt 3-2.xls contains data from the State and Metropolitan Area Data book for 1998 on nurses and health insurance coverage by state, plus the District of Columbia. Use the data from this file and do the following:

   a. Use the =RAND() function to draw a random sample of 10 states from among all the states, including the District of Columbia.

   b. Use the uniform distribution option in the Data Analysis add-in to generate random numbers between 1 and 100, and use these to select a random sample of 15 states from among all the states, including the District of Columbia. Specify a random seed of 1359.

   c. Use the normal distribution option in the Data Analysis add-in to generate random numbers with a mean of 20 and a standard deviation of 4, and use these numbers to select a simple random sample of 10 states from among all the states, including the District of Columbia. Specify a random seed of 8109.



## Exercises for Section 3.3 (Question 1) on page 107

### 1. Using the data in Chpt 3-3.txt (this is the data set discussed in Section 3.3), do the following:

a. Import the data to a spreadsheet by using the Text Import Wizard.

b. Make the data century-correct as discussed in relation to Figure 3.15.

c. Provide a label line above the data (it will become row 1) and label the data, as shown in Figure 3.16.

d. Insert a column after DOD, as shown in Figure 3.17, and calculate the LOS for each observation.

e. Insert a column after DOB and calculate Age for each person, as shown in Figure 3.18.

f. Insert a column after Sex and create a variable Sex1, as shown in Figure 3.19.

g. Save the result as an Excel file.

# Module 2

## Exercises for Section 4.1 (Question 1, a-f) on page 129

### 1. Select the variable Age, and do the following:

   a. Using the =MIN(), =MAX(), and =FREQUENCY() functions, replicate Figure 4.2.

```diff
! use Data Analysis>Histogram function
```

   b. Using the results just obtained, generate the chart shown in Figure 4.8 and put in the relevant labels as shown in that chart. Show this chart on the spreadsheet.
   
   c. Modifying the data as shown in Figure 4.9, generate a line chart as shown in that figure, and show this chart on the spreadsheet.
   
   d. Create a bar chart as shown in Figure 4.10, and show it on the spreadsheet.
   
   e. Create a pie chart as shown in Figure 4.11, and modify it to look as much like that figure as possible; show this chart on the spreadsheet.
   
   f. Replicate the chart of Age and LOS as shown in Figure 4.12. Show this chart on the spreadsheet

## Exercises for Section 4.2 (Questions 1 and 2) on page 135

### 1. Use the variable Sex on the Hospital Charges sheet in Chpt 4-1.xls, and do the following.

   a. Create a frequency distribution using the pivot table that replicates the one in Figure 4.23, using Count of Sex in the DATA field.

   b. Create a frequency distribution using the pivot table that replicates the one in Figure 4.23, using Count of Age in the DATA field.

   c. Is there any difference between the two tables you just created? Why or why not?

### 2. Use the variable LOS on the Hospital Charges sheet in Chpt 4-1.xls, and do the following:

   a. Using a nested =IF() function, create a new variable, LOS1, which will take on the value “Short” when LOS is less than 4 days, “Medium” when LOS is 4 days to 9 days, and “Long” when LOS is 10 days or more.

   b. Create a frequency distribution of LOS1 using the pivot table.

## Exercises for Section 4.3 (Questions 1 and 2) on page 140

### 1. Use the data on the MS-DRG worksheet in Chpt 4-2.xls, and use the pivot table capability to replicate Figure 4.26.

-pivot table of DRG Category, breakdown by sex

### 2. Use the data on the Late Delivery worksheet in Chpt 4-2.xls, and do the following.
   
   a. Generate a cross-tabulation using the pivot table capability with Ward as the column heading and Reason as the row heading.
   
   b. Add a new variable, Reason1, to the Late Delivery worksheet, assigning Other as the label for all but the two most common reasons for late delivery, and generate a cross-tabulation with Ward as the column headings and the reasons in Reason1.

# Module 3

## Exercises for Section 6.1 (Question 1) on page 196

### 1. Use the Hospital charges worksheet in the file Chpt 4-1.xls.

```diff
! use Data Analysis>Descriptive Statistics function
```
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

```diff
! Can use Data Analysis>One Way Anova function
```

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

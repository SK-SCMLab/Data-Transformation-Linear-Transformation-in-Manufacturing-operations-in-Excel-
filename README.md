# 😀 Data-Transformation-Linear-Transformation-in-Manufacturing-operations-in-Excel-
This repository contains simple theoritical information that demonstrates the use of data and linear transformation techniques to clean, prepare and analyze manufacturing data for process improvement

---

## 😃 Data Transformation
Data transformation involves changing the format, structure, or values of data to make it suitable for analysis, modeling, or control. It is crucial in manufacturing to:
- Normalize or standardize measurements across resources
- Convert units (e.g. tons to kilograms)
- Handle non-linearity in sensor data
- Identify hidden trends or prepare data for statistical models
Generally, normally distributed data is preferred in order to use a no. of statisical tools like:
- Individual value control charts
- Capability analysis
- T-Tests
- ANOVA
When data is not normally distributed, the cause for non-normality should be determined and appropriate remedial actions should be taken

<pre> 
+-------------+
|Non-normal data|
+-------------+
      |
      v
+-------------+
|Data transformation|
+-------------+
      |
      v
+----------+      +-----------+    
|Linear|          |Box and Cox|
+----------+      +-----------+
             |
             v
+---------+
|Normal data|
+----------+
</pre>

---

## 😄 Linear Transformation
- A linear transformation is a specific type of data transformation where we apply a linear function to a variable, usually of the form:

                        Y = aX + b
  - This is useful for normalizing machine measurements and simplifying multivariate analysis
  - The original data is multiplied or divided by a coefficient or a constant is subtracted or added
  - It does not change the shape of the data distribution

---

## 😁 Box and Cox transformation
- The Box-Cosx transformation is a powerful statistical method used to stabilize variance, make data more normal, and improve the performance of predictive models - especially useful in manufacturing data that often includes skewed or non-linear patterns
- The Lambda value (λ) indicates the power to which all data should be raised
- The family of the power transformations are used for:
         1. Converting a dataset to use parametric statistics
         2. Any continuous data > 0
- The use of transformation will not guarantee normality

For a variable y and transformation parameter (λ):

                        y(λ) = {y^λ -1, if λ ≠ 0
                               { ln(y), if λ = 0

---

*"If your data isn't normal, don't fix the process - fix the scale"*

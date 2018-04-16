# Variance
This measures of how far a set of variables are from the mean. 
$$
\bf{var(x)} = \frac{\sum_{i=1}^n(x_i - \bar{x})^2} {N}
$$
In the case whereby the variance of a sample is to be computed, the formula changes to:
$$
S^2 = \frac{\sum_{i = 1}^n(x_i - \bar{x})^2}{n-1}
$$
or a simple method:
$$
S^2 = \frac{\sum x_i^2 - \frac{(\sum x_i)^2}{N}} {n-1}
$$

---
### Application of Variance in Finance
In finance, variance plays a critical role in determining the volatility of an investment. The higher the variance of a given portfolio, the greater the risk.

---
# Covariance
This is the measure of how two similar variables vary together. It is similar to variance the only difference being unlike variance that looks at one variable, covariance looks at two variables.
$$
cov(x,y) = \frac{\sum_{i=1}^n(x_i -\bar{x})(y_i -\bar{y})}{N}
$$
In case of a sample:
$$
S_{xy} = \frac{\sum_{i=1}^n(x_i-\bar{x})(y_i - \bar{y})}{n-1}
$$


# Variance-Covariance Matrix
This is a type of matrix where the variances are displayed in the main diagonal while the covariance in the minor diagonal.


$$
M=
  \begin{bmatrix}
    \color{blue}{var_{1}} & \color{red}{cov_{1,2}} & \color{yellow}{cov_{1,3}} & .. & \color{maroon}{cov_{1,n}} \\
    \color{red}{cov_{2,1}} & \color{blue}{var_{2}} & cov_{2,3} & .. & cov_{2,n} \\
    \color{yellow}{cov_{3,1}} & cov_{3,2} & \color{blue}{var_{3}} & .. & cov_{3,n} \\
    ... &....&...&...&... \\
    \color{maroon}{cov_{n,1}} & cov_{n,n-1} & cov_{n,n-2} & .. & \color{blue}{var_{n}}
  \end{bmatrix}
$$
### Finding a Var - Covar Matrix

---




$$
x_i
$$
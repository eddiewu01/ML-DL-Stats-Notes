# Basic Statistical Concepts
This note outlines some of the basic statistical concepts, explained in simple terms without substantial mathematical equations and derivations (yay!), which I had to learn for my interests and career development.

## Standard deviation
It quantifies how much the data is spread out. 

## Standard Error
The standard deviation of all sample mean's mean: quantifies how far the sample mean is from the true population mean

## Variance
![](imgs/variance_equation.jpg)

## Hypothesis Testing
Example <br />
* H<sub>0</sub> (null hypothesis): Defendant is not guilty <br />
* H<sub>a</sub> (alternative hypothesis): Defendant is guilty

Always assume that the null hypothesis is true, so null hypothesis can be thought as our initial assumption

Look at the following tables for possible scenarios:

| Decision/Actual            | Null Hypothesis (H<sub>0</sub>) | Alternative Hypothesis (H<sub>a</sub>)  |
| ---------------------------|:-------------------------------:| :--------------------------------------:|
| Do not reject H<sub>0</sub>|                OK               |             Type II Error               |
| Reject H<sub>a</sub>       |            Type I Error         |                  OK                     |

Type I Error: Reject null hypothesis when it's true<br />
Type II Error: Do not reject null hypothesis when it's false<br />

Three kinds of settings for hypothesis testing:<br />
* Right tailed, H<sub>0</sub>: μ=3, H<sub>a</sub>: μ>3 <br />
* Left tailed <br />, H<sub>0</sub>: μ=3, H<sub>a</sub>: μ<3
* Two tailed, H<sub>0</sub>: μ=3, H<sub>a</sub>: μ≠3

## Normal Distribution
![](imgs/normal_distribution.png)
![](imgs/normal_distribution_eqn.png) <br />
<center>-∞ < x < ∞, -∞ < μ < ∞</center>

Example <br />
X is a random variable with normal distribution with mean μ and variance σ<sup>2</sup> (σ is the standard deviation), then it's written as 
X ~ N(μ, σ<sup>2</sup>)

Standard normal distribution is Z ~ N(0, 1) where 0 is the mean and 1 is the variance.

## P-Value

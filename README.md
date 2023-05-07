Download Link: https://assignmentchef.com/product/solved-math4387-exam1
<br>
<strong>Problem 1 </strong>

Write down a linear regression model with assumptions.

<h1>Problem 2</h1>

In fitting a simple linear regression model <em>Y </em>= <em>β</em><sub>0 </sub>+ <em>β</em><sub>1</sub><em>X </em>+ , it was found that observation <em>Y<sub>i </sub></em>fell directly on the fitted regression line. If this case were deleted, would the least square regression line fitted on the remaining <em>n − </em>1 cases be changed? [Hint: try to use the function that we minimize in the least square

procedure.]

<h1>Problem 3(a)</h1>

In this problem, you will simulate data with 5000 observations. About 50% of them are male. Use a binomial distribution to choose the number of males randomly (Hint: You are flipping a fair coin and counting the number of heads). Call the variable Gender. Diastolic blood pressure of male and female follows a normal distribution with mean <em>µ</em><sub>male </sub>= 82, <em>µ</em><sub>female </sub>= 80 mmHg and standard deviation <em>σ</em><sub>male </sub>= <em>σ</em><sub>female </sub>= 10<em>.</em>5. Total cholesterol in blood follows a normal distribution with a mean of 5.69 and variance 1.31. Glucose follows a normal distribution with a mean 5.12 and a standard deviation of 1.24. Gender, cholesterol, and glucose are predictor variables. The response variable is BMI. The error term, <em> N</em>(0<em>,</em>9) accounts for the randomness and effect of other factors that affect BMI. The mean BMI while all the predictors are zero is 23. Simulate BMI so that the effect sizes (regression coefficients) of Gender (Male), blood pressure, cholesterol, and blood glucose are 0.01, 0.07, 0.1, and -0.1, respectively. Run a multiple linear regression and discuss if the regression model could identify the simulated relationship. You should also discuss if you find an estimated coefficient for a variable that is much different than the parameter used in the simulation.

<strong>Problem 3(b) </strong>

Run the same analysis as problem 3(a) multiple times. Do you get the same or different estimates? Why?

<h1>Problem 4</h1>

<ol>

 <li>What does it mean for a regression model to be a linear model? (Specifically, explain what linear model means in the context of a regression model.)</li>

 <li>Consider a setting where there are four observations (<em>n </em>= 4) and two predictors (<em>p </em>= 3). Construct a 4 <em>× </em>3 design matrix <em>X </em>that would lead to an unidentifiable model but where no two columns are identical.</li>

</ol>

Consider the figure below for parts (c) and (d) of this question.

x

<ul>

 <li>Is the relationship between <em>x </em>and <em>y </em>linear? Why?</li>

 <li>Explain how the relationship between <em>y </em>and <em>x </em>can be approximated reasonably well by a linear model.</li>

</ul>

<h1>Problem 5</h1>

Consider the model

log(ppgdp) = <em>β</em><sub>0 </sub>+ <em>β</em><sub>1</sub>fertility + <em>β</em><sub>2 </sub>log(pctUrban)


You can find the description of the data and the variables using ?alr4::UN11. Fit the model, print the summary of the model and, interpret the coefficient of pctUrban.

You will not get full credit for using generic terms or variable names like fertility or pctUrban. Clearly indicate what these variables are measuring/representing.

<h1>Problem 6</h1>

Assume that the observations for the response variable are correlated i.e. cov(<em>y<sub>i</sub>,y<sub>j</sub></em>) <em>6</em>= 0. So the variancecovariance matrix <em>V ar</em>() <em>6</em>= <em>σ</em><sup>2</sup><em>I</em>, where <em>σ </em>is a constant and <em>I </em>is the identity matrix. Instead assume that <em>V ar</em>() = <em>σ</em><sup>2</sup><em>I </em>+ <em>γ</em><sup>2</sup><em>K</em>, where <em>K </em>is not a diagonal matrix. How does this phenomena effects the estimates <em>β</em><sup>ˆ</sup>.

(More specifically is <em>E</em>[<em>β</em><sup>ˆ</sup>] and <em>V ar</em>(<em>β</em><sup>ˆ</sup>) in this case and how they vary from that under usual linear regression model assumption?)

<h1>Problem 7</h1>

Consider a simple linear regression model

<em>Y </em>= <em>β</em><sub>0 </sub>+ <em>β</em><sub>1</sub><em>X </em>


with usual notations and assumptions.

<ol>

 <li>How does the parameter <em>β</em><sub>0 </sub>and <em>β</em><sub>1 </sub>chaanges if we center the predictor variable <em>X </em>(i.e. substract <em>X </em>from <em>X</em>).</li>

 <li>How do the parameters changes if we scale the predictor variable <em>X </em>(i.e. divide <em>X </em>by its standard deviation?)</li>

 <li>If <em>X </em>and <em>Y </em>are uncorrelated what can be said about <em>β</em><sub>0 </sub>and <em>β</em><sub>1</sub>?</li>

</ol>

<h1>Problem 8</h1>

Download the data simu_exam1.txt from the canvas. Fit a multiple linear regression model with <em>Y </em>as the response variable and <em>x</em>1<em>,x</em>2<em>,x</em>3 as predictors (just one model with three predictors). Perform model diagnostic for structure. If there are issues, suggest a model that is more appropriate for the data. Give the coefficients of the final model and interpret them.

<table>

 <tbody>

  <tr>

   <td width="891"></td>

  </tr>

  <tr>

   <td></td>

   <td></td>

  </tr>

 </tbody>

</table>

<h1>Problem 9</h1>

Select data from <a href="https://archive.ics.uci.edu/ml/datasets.php">http://archive.ics.uci.edu/ml/datasets.php.</a> On the left sidebar select Regression,

Numerical, and Multivariate. You can choose any data from the list that has Default Task = Regression and the number of instances more than 500. Do not select data that has Time Series in the Default Task column. You will describe the data, run an appropriate multiple linear regression model, perform diagnostic for model structure, and transform variable if appropriate, and at the end interpret your result.

<h1>Problem 10</h1>

Consider the linear regression model

<em>Y </em>= <em>β</em>0 + <em>β</em>1<em>X</em>1 + <em>··· </em>+ <em>β</em><em>jX</em><em>j </em>+ <em>··· </em>+ <em>β</em><em>p−</em>1<em>X</em><em>p−</em>1

Show that the OLS linear fit to the data in an added variable plot for predictor <em>x<sub>j </sub></em>will have slope <em>β<sub>j </sub></em>and intercept 0.
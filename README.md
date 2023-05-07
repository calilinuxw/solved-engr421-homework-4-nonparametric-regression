Download Link: https://assignmentchef.com/product/solved-engr421-homework-4-nonparametric-regression
<br>
In this homework, you will implement three nonparametric regression algorithms in Matlab, Python, or R. Here are the steps you need to follow:

<ol>

 <li>Read Section 8.8 from the textbook.</li>

 <li>You are given a univariate regression data set, which contains 133 data points, in the file named csv. Divide the data set into two parts by assigning the first 100 data points to the training set and the remaining 33 data points to the test set.</li>

</ol>




<ol start="3">

 <li>Learn a regressogram by setting the bin width parameter to 3 and the origin parameter to 0. Draw training data points, test data points, and your regressogram in the same figure.</li>

</ol>

Your figure should be similar to the following figure.

<ul>

 <li><strong>= 3</strong></li>

</ul>

<ol start="4">

 <li>Calculate the root mean squared error (RMSE) of your regressogram for test data points. The formula for RMSE can be written as</li>

</ol>

!.

’$%&amp;$

Your output should be similar to the following sentence.

Regressogram =&gt; RMSE is 24.7260 when h is 3

<ol start="5">

 <li>Learn a running mean smoother by setting the bin width parameter to 3. Draw training data points, test data points, and your running mean smoother in the same figure. Your figure should be similar to the following figure.

  <ul>

   <li><strong>= 3</strong></li>

  </ul></li>

 <li>Calculate the RMSE of your running mean smoother for test data points. Your output should be similar to the following sentence.</li>

</ol>

Running Mean Smoother =&gt; RMSE is 23.8403 when h is 3

<ol start="7">

 <li>Learn a kernel smoother by setting the bin width parameter to 1. Draw training data points, test data points, and your kernel smoother in the same figure. Your figure should be similar to the following figure.

  <ul>

   <li><strong>= 1</strong></li>

  </ul></li>

 <li>Calculate the RMSE of your kernel smoother for test data points. Your output should be similar to the following sentence.</li>

</ol>

Kernel Smoother =&gt; RMSE is 24.1672 when h is 1




<strong> </strong>
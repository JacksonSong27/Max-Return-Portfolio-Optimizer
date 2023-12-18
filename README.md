# Max-Return-Portfolio-Optimizer
Data Science Project 

Goal: Input Maximum Risk you are willing to take, desired rate of return (this is not that relevant, this more for a comparison to product). Allow user to input these information on Interactive HTML page.

Why? Our original goal is to help the elderly maximize their rate of return in the stock market so that they can retire. But we want to apply this algorithm for people of all ages depending on their maximum risk.

How to do that?  Steps:  1) Get Historical Stock Market Data 
	1) Use Index Funds 
	2) Use bonds
	3) we are not using crypto yet because not that applicable

2. Get the average annual rate of return and risk of each financial instrument (ex: index funds, or bonds)
How?
We use simple math for annual rate of return, we use standard deviation to calculate risk.

3. Use Machine Learning Model to predict FUTURE DATA
How?

We use very old data as “training data”. We use “newer” data as “testing” data. Then, we use this to compute future annual rate of return and risk for each financial instrument,.

Why?
 We need a machine learning model. We want more data.

4. We input data into a Markowitz Model (this is not machine learning, this is a mathematical algorithm to get the maximum rate of return given a certain algorithm). This will give us maximum rate of return (which we want).

5. Additional Code: We write additional code to give us the ideal portfolio of index funds/bonds that an individual with a certain risk level wants

(Done!)

6. (If we wanna be fancy), we make a fancy HTML page with graphs and visuals. 

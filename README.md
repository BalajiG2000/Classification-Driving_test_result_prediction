# Classification-Driving_test_result_prediction

The dataset used for this task is "DMV driving test results dataset". Based on the pass/fail prediction a Driving License will be awarded for the applicants.

I implemented all the machinery, including gradient descent, cost function, and logistic regression, of the various learning algorithms to have a deeper understanding of the fundamentals.

I tried  to build a logistic regression model using Python and NumPy, conduct basic exploratory data analysis, and implement gradient descent from scratch.

NOTE:

We can interpret the output of the logistic sigmoid function as a probability, since this function outputs in the range 0 to 1 for any input.
We can threshold the function at 50% to make our classification.

If the output is greater than or equal to 0.5, we classify it as passed, and less than 0.5 as failed.

The maximal uncertainty, we can easily see if we plug in 0 as the input. So when the model is most uncertain it tells you the data point has a 50% probability of being in either of the classes.

We’re going to be using this function to make our predictions based on the input.


Steps Involved:

Introduction and Project Overview

Load the Data and Import Libraries

Visualize the Data

Define the Logistic Sigmoid Function 𝜎(𝑧)

Compute the Cost Function 𝐽(𝜃) and Gradient

Cost and Gradient at Initialization

Implement Gradient Descent

Plotting the Convergence of 𝐽(𝜃)

Plotting the Decision Boundary

Predictions Using the Optimized 𝜃 Values

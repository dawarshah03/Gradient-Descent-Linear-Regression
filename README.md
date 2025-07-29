# Gradient-Descent-Linear-Regression

I used Gradient Descent to predict CS scores from Math scores using Python. We use Gradient Descent to find the best-fitting line by slowly adjusting values (like slope and intercept) to reduce prediction error. It helps in minimizing the cost function step by step until we reach the best result.

It starts with random values of m and b, then keeps improving them to fit the best line.

I used:

Learning rate: 0.0001

Iterations: 100000

Cost function: to check how far the guess is from real answer

prev_cost: to stop early if the cost is not changing

In the end, it prints the best m, b, and cost.
Then I also used SkLearn’s LinearRegression to compare — both gave the same result.

Code and dataset are in the repo.

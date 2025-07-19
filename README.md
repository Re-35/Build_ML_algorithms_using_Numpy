# ML algorithms using Numpy

**Projects: Build ML algorithms from scratch using Numpy**

## Goal from Projects:
  - Use Numpy to build some simple ML algorithms from scratch to understand how they're work.

## Algorithm Types:
1 - **Precepteron - Adaptive Linear:**
The first and the simpleset ML algorithm. It classify as supervised machine learning, linear binary classification(the classes are 2).
Adaptive Linear is enhanced Preceptron that uses Gradient Descent to update the weights and bias.
How it work:
predict the data.
calculate the error.
calculate the loss function.
update weight and bias using Gradient descent, which use derivatives to update them and decrease the loss faster and smoother.

2 - **Logistic Regression:**
The supervised algorithm for binary classification, also used for multi-classes as default (in sklearn).
The difference between it and Preceptron: The function of it is like S, which classify one class after 0.5, and another classify befor 0.5,
this function based on Odds function which calculate the probaplty of each data point.
sigmuid function: exponent function resulted from (Odds function = sigma(z) , z = w*x + b).
loss function: use algorithm to calculate the loss, it has 2 parts, one if the probaplaty is to class (1), and another if the probaplaty
is to class (0).

3 -**K-Nearest Naighbor:**
The supervised lazy machine learning that used for both classification and regression.
Instead of learn from data, it memorize it until the new data gaven to it, then mesure the distence between the new data point and
other data points, then classify it depend on the nearest k number of points.
the metric used in my project was Euclidean distance.

## File formates:
each project has 2 file formats: **.ipynb** (jupyter notebook forsmt), and **.pdf** for quick review.

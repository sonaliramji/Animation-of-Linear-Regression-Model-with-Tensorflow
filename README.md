# Animation of Linear Regression Model with Tensorflow
In this project, we utilize Tensorflow's animation capabilities to visualize a Linear Regression model built for predicting House Prices.

As outlined in [Jerry Kurata's](https://www.linkedin.com/in/jerrykurata/) wonderful course from [Pluralsight](https://www.pluralsight.com/courses/tensorflow-getting-started), Training a Model with TensorFlow has two prime aspects:
- Concept
- Implementation

We achieve the Conceptualization phase by following these steps:
- Preparation of the Data
- Inference
- Loss Measurement
- Optimizer to Minimize Loss

The corresponding Implementation steps followed are:
- Generation house size and price data
- Defining inference as : Price = (sizeFactor * size) + priceOffset
- Using *Mean Square Error* for loss measurement
- using Gradient Descent Optimizer

## Python Libraries and funcations used include:
- tensorflow, numpy, math, matplotlib.pyplot, matplotlib.animation, numpy.random, plt.plot, plt.xlabel, plt.ylabel, plt.show
- [matplotlib.animation](https://matplotlib.org/api/animation_api.html) used for animation of the plot to watch fitting of the line IN ACTION!


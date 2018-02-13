>Mathematics is the science of skillful operations with concepts and rule invented just for this purpose — Eugene Wigner

Data Science is not an event, it’s a process in which we use data to understand the world. Data Science is when you have a model, the hypothesis of problems and by using data you solve or make an insight, Data will lead you towards right path If you are roaming in a vain!

Data Science is a blend of skills in three major areas: 
1. Mathematics Expertise
2. Technology and Hacking Skills
3. Strong Business ability

![Data Science](https://photos.app.goo.gl/16HkaPWXbBlMoqeJ3)

Mathematical expertise does not only refer to **Statistics**. While it is important but it is not the only type of math utilised in Data Science. Several machine learning techniques are based on **Linear Algebra**, several deep learning techniques require **Calculus** also **Probability** is essential.

---

**Statistics** are again categorized into descriptive and inferential statistics, descriptive statistics summarise the data but not generalize it, whereas inferential statistics help in making judgements from the data.

Data Scientists use statistics in several occasions:
1. Weather forecasting is held using statistics, several computing models are made using statistical concepts which make prediction of weather by comparing prior and present weather data.
2. Technical Analysis: Technical analysis is a trading tool employed to evaluate securities and attempt to forecast their future movement by analyzing statistics gathered from trading activity, such as price movement and volume.
3. In the domain of medicines, scientists can not prescribe any drug without statistically validating the rate of effectiveness of the drug.
4. News reporter makes a prediction of winner for elections based on political campaigns. 

---

**Linear Algebra** is the branch of mathematics concerning vector spaces and mappings between such spaces. It includes the study of lines, planes, and subspaces, but is also concerned with properties common to all vector spaces. In Data Science it is needed to understand how algorithms work. What are their limitations and in case they make any underlying assumptions.
Let’s see why linear algebra is important in data science.

![Plant Image](https://photos.app.goo.gl/0JPahkCp6Ewm3OLE2)

A human brain can easily recognise the above image as a plant because it has gone through million years of evolution and our brains are trained to identify the images, but the same task, when given to the computers that understand only 0 and 1 processes. The computers store the pixel intensities in a construct called Matrix, then this matrix can be processed to identify the image. 
So any operation which you want to perform on this image would likely use Linear Algebra and matrices in the back end.

---

Calculus is important for several key machine learning applications. For example. You’ll need to be able to calculate derivatives and gradients for optimizations such as gradient desent technique.

Machine learning uses derivatives to find optimal solutions to problems. It’s useful in optimization functions like Gradient Descent because it helps us decide whether to increase or decrease our weights in order to maximize or minimize some metrics (e.g. loss)

It also helps us model nonlinear functions as linear functions (tangent lines), which have constant slopes. With a constant slope we can decide whether to move up or down the slope (increase or decrease our weights) to get closer to the target value (class label).

Let’s write code to calculate the derivative for f(x) = x². We know the derivative should be 2x

```
def xSquared(x):
    return x**2

def getDeriv(func, x):
  h = 0.0001
  return (func(x+h) - func(x)) / h

x = 3
derivative = getDeriv(xSquared, x)
actual = 2*x

derivative, actual = 6.0001, 6
```
---

Probability is an essential and back-bone concept used in data science, the journey of learning statistics begin with learning probability. 

Life is full of uncertainties. We don’t know the outcomes of a particular situation until it happens. Will it rain today? Will I pass the next math test? Will my favorite team win the toss? Will I get a promotion in next 6 months? All these questions are examples of uncertain situations we live in. 

Let’s face it, life is uncertain!

Conclusion
At the heart of mining data, insight and building data product is the ability to view the data through a quantitative lens. There are dimensions and correlations in data that can be expressed mathematically. Finding solutions utilizing data becomes a brain teaser of quantitative technique. Solutions to many business problems involve building analytic models grounded in the hard math, where being able to understand the underlying mechanics of those models is key to success in building them.

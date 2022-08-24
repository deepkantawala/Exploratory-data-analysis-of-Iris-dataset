Exploratory data analysis is a process of analysing the data; it is usually first step we take to find a solution to our problem.

(1.1) Iris Dataset

For the first part ill be using Iris dataset which i believe every data analyst knows about [https://en.wikipedia.org/wiki/Iris_flower_data_set].
The dataset consist information for 3 flowers of iris species;  50 samples from each of three species of Iris (Iris setosa, Iris virginica and Iris versicolor) are present in the dataset. Four features were measured from each sample: the length and the width of the sepals and petals, in centimeters. The dataset contains features such as petal length, petal width, sepal length, and sepal width.


(1.2) 2-D and 3-D scatter plot


Using sepal_length and sepal_width features, we can distinguish Setosa flowers from others.
Seperating Versicolor from Viginica is much harder as they have considerable overlap. To distungish between flowers in plots i used seaborn.

3D scatter plots are used to plot data points on three axes in the attempt to show the relationship between three variables. Each row in the data table is represented by a marker whose position depends on its values in the columns set on the X, Y, and Z axes.

(1.3) Pair-plot

Pair Plots are a really simple (one-line-of-code simple!) way to visualize relationships between each variable.
It produces a matrix of relationships between each variable in your data for an instant examination of our data.

(1.4) Histogram, PDF, CDF


A histogram is a graphical display of data using bars of different heights. In a histogram, each bar groups numbers into ranges.
Probability Density Function (PDF) is used to define the probability of the random variable coming within a distinct range of values, as opposed to taking on anyone value.

(1.5) Median, Percentile, Quantile, IQR, MAD

Median : Median is a value separating the higher half from the lower half of a data sample, a population or a probability distribution. For a data set, it may be thought of as "the middle" value.
Percentile and quantile : Consider an array consisting of 100 sorted values as shown below. array Aᵢ= [A₁, A₂, A₃, A₄, A₅, A₆, A₇, A₈, A₉, A₁₀, ………, A₉₉, A₁₀₀]
Interquartile range: In descriptive statistics, the interquartile range, also called the midspread, middle 50%, or H‑spread, is a measure of statistical dispersion, being equal to the difference between 75th and 25th percentiles, or between upper and lower quartiles, IQR = Q₃ − Q₁.
Median absolute deviation (MAD) is a robust measure of the variability of a univariate sample of quantitative data. ... that is, starting with the residuals (deviations) from the data's median, the MAD is the median of their absolute values.

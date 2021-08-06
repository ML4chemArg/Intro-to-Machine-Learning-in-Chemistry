<p align="center">
  <img src="https://github.com/ML4chemArg/Intro-to-Machine-Learning-in-Chemistry/blob/main/images/banner5.jpg" alt="banner" width="800" />
</p>

# Introduction to Machine Learning for chemists

Machine Learning, a subdomain of Artificial intelligence, is a pervasive technology that would mold how chemists interact with data. Therefore, it is a relevant skill to incorporate into the toolbox of any chemistry students. Here we present a course that introduces machine learning for chemistry students based on a set of Python Notebooks and assignments. Python language, one of the most popular programming languages, allows for free software and resources, which ensures availability. The course is constructed for students without previous experience in programming, leading to an incremental progression in depth and complexity that covers both programming and machine learning concepts. The examples used are related to real data from physicochemical characterizations of wines, producing an attractive material that captures the interest of students.

Topics included are:
* **Introduction to Python**

The first notebook is focused on introducing students to Python from a practical point of view,
mainly teaching how to use functions and advanced libraries. Variables, data types, value assignment,
and value comparison are covered to complement with functions. Pandas library is presented for data
handling, Pandas DataFrames and Seaborn library are applied for fitting and plotting a linear
regression.

* **Basic Statistics**

Different ways for importing data are covered and the wine dataset is presented. This dataset is the
main data analyzed for the rest of the course. After loading the data in a DataFrame, basic methods for
Pandas DataFrames are explored (head, min, max, mean, std, describe). A confidence interval is
calculated as an introduction to errors and statistics. Histograms, box plots, and violin
plots are examined using Seaborn. Finally, hypothesis tests (one-sample and two-unpaired-samples
two-tailed t-tests) and analysis of variance (ANOVA) are performed using the Pingouin library.

* **Data Visualization and Dimension Reduction**

Visualization is a key aspect to understanding complex datasets with several variables.
Accordingly, box plots and violin plots are used for representing multivariable data. Another important
tool to explore data is correlation analysis, as several methods assume a dependency between
variables. The Pearson correlation coefficient is calculated using Scipy and it is represented with
heatmaps and pair plots using Seaborn. Afterwards, dimension reduction is explored for high
dimensional data. Principal Component Analysis (PCA), t-distributed Stochastic Neighbor Embedding
(t-SNE), and Uniform Manifold Approximation and Projection (UMAP) methods are implemented.
Finally, advanced plots such as interactive plots with Ipywidgets and 3D plots with Matplotlib and
Plotly are also covered.

* **Classification**

The task of classifying implies dividing the data among classes accordingly to predictor variables.
In this case, the challenge is to discriminate between red and white wine using physicochemical
attributes. Logistic regression and decision tree are the classification methods covered. Also, the
concepts of data splitting, data standardization, Confusion Matrix, and metrics calculation (Accuracy,
Precision, and Recall) are examined.

* **Regression**

Regression analysis is performed to predict wine density based on other physicochemical
properties. Correlations between other attributes and density are calculated. Both simple and multiple
linear regression analyses are performed, and the importance of standardization is exhibited. Lastly, LASSO regularization strategy is applied, paying attention to the magnitude and meaning of the regularization constant.


<p align="center">
  <img src="https://github.com/ML4chemArg/Intro-to-Machine-Learning-in-Chemistry/blob/main/images/Fig1.png" alt="fig1" width="400"/>
</p>

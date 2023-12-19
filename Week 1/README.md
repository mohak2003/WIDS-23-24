Hi Mentees,

I am delighted to welcome you to the WIDS 2023-24, where we'll start Algorithmic trading and apply Deep learning approaches to predict stock market prices. You have been selected from a pool of talented and motivated applicants, and I am proud to be your mentor for this journey.

In week 1, we will start with revising python and learning about basic data science libraries, such as numpy, pandas, matplotlib. These libraries are essential tools for data manipulation, visualization, and machine learning. You will also get familiar with Jupyter notebooks, which are interactive environments for coding and documenting your data science projects.

I hope you are excited and ready for this program, as I am. Embrace the challenge, explore the vast resources available on the internet, and take the initiative to learn and grow. Collaboration with your fellow mentees is encouraged, but also be prepared to tackle difficulties independently.

### **Installation and Setup**

Visit this link for a detailed guide on installing and setting up Python - [Python Installation and Setup](https://wiki.python.org/moin/BeginnersGuide/Download)

### **Introduction to Jupyter Notebooks**

Jupyter notebook is a web based notebook environment which is widely used for interactive programming, that is, code execution combined with rich markdown text and much more. The Jupyter notebook runs a local Ipython kernel on your machine and launches in your web browser. These notebooks are also called as Ipython notebooks, and have a '.ipynb' extension instead of traditional '.py' extension for Python files. All the assignments for this course are made in Jupyter notebooks and you are expected to complete them in the notebook itself. Hence, it is important for you to get aquainted with Jupyter notebooks.

Visit this link for installing and setting up a basic notebook - [Setting up Jupyter Notebook](https://realpython.com/jupyter-notebook-introduction/). The link also teaches you to write and execute a basic Python code in a Notebook cell.

### **Google Colab**
Google Colab is a platform provided by Google, which runs a Jupyter notebook in the cloud. While it is a convenient way to get set up, there are some caveats you would like to know before it.
The setup is platform agnostic i.e. all you need is a browser. The recommended way to get started is first logging in to Google. Sign in > Head to the home page for Google Colab [here](https://colab.research.google.com/notebooks/intro.ipynb#recent=true) > click on New Notebook.
From this point, everything is basically the same as a Jupyter notebook.


### Instructions on downloading and using notebooks

1. Open the respective `.ipynb` file on GitHub
2. In the upper right corner, there are several buttons and icons including the ones shown below. Click on the Raw Button.
       Raw | Blame
      --- | ---
      
3. The python notebook opens as raw text in browser. Right click->Save as OR just press CTRL + S. Save the notebook, open it using Jupyter Notebook you just installed and start learning! 


Below are some resources for you to follow :

1. Python:
https://github.com/wncc/TSS-2021/tree/main/Python%20%26%20its%20Applications/Week-1
https://www.kaggle.com/learn/python
https://github.com/topics/python-tutorial-notebook
https://colab.research.google.com/github/jckantor/CBE30338/blob/master/docs/01.02-Python-Basics.ipynb

2. Data Science Libraries:

## Numpy
### What is NumPy?
NumPy stands for Numerical Python. One of the most fundamental packages in Python, NumPy is a general-purpose array-processing package.It is a Python library used for working with arrays.It provides high-performance multidimensional array objects and tools to work with the arrays. NumPy is an efficient container of generic multi-dimensional data.
NumPy’s main object is the homogeneous multidimensional array where their dimensions are called axes and the number of axes is called rank. NumPy’s array class is called ndarray aka array.To read more about NumPy head over to this [link](https://numpy.org/doc/stable/user/whatisnumpy.html)

### Installation of Numpy
For installation you can refer [this](https://www.w3schools.com/python/numpy/numpy_getting_started.asp)
Once you are done with the installation part , you can use it by importing it in your applications by adding **import** keyword. 
  
## Pandas
Pandas is an open-source Python package that provides high-performance, easy-to-use data structures and data analysis tools for the labeled data in Python programming language. Pandas stand for **Python Data Analysis Library**.
**When to use?**
Pandas is a perfect tool for data wrangling or munging. It is designed for quick and easy data manipulation, reading, aggregation, and visualization.
Pandas take data in a CSV or TSV file or a SQL database and create a Python object with rows and columns called a data frame. The data frame is very similar to a table in statistical software, say Excel or SPSS.

### What can you do with Pandas?
* Indexing, manipulating, renaming, sorting, merging data frame
* Update, Add, Delete columns from a data frame
* Impute missing files, handle missing data or NANs
* Plot data with histogram or box plot

## Matplotlib
Matplotlib is a data visualization library and 2-D plotting library of Python.It is a close resemblance to MATLAB embedded in Python programming language.
Histogram, bar plots, scatter plots, area plot to pie plot, Matplotlib can depict a wide range of visualizations. With a bit of effort and tint of visualization capabilities, with Matplotlib, you can create just any visualizations.
Matplotlib also facilitates labels, grids, legends, and some more formatting entities with Matplotlib. Basically, everything that can be drawn!

### Installation of Matplotlib
For installation you can refer [this](https://www.w3schools.com/python/matplotlib_getting_started.asp)
Once you are done with the installation part , you can use it by importing it in your applications by adding **import** keyword. 
 
## Seaborn
Check out [this](https://www.w3schools.com/python/numpy/numpy_random_seaborn.asp) or [this](https://www.datacamp.com/community/tutorials/seaborn-python-tutorial).
You can also look at [Seaborn documenation](http://seaborn.pydata.org/introduction.html) to know more about Seaborn.

## Scikit-learn

Scikit-learn is a free software library for Machine Learning coding primarily in the Python programming language.Scikit-learn is built on top of other Python libraries like NumPy, SciPy,  Matplotlib, Pandas, etc. and so it provides full interoperability with these libraries.You can implement various Supervised and Unsupervised Machine learning models on Scikit-learn like Classification, Regression, Support Vector Machines, Random Forests, Nearest Neighbors, Naive Bayes, Decision Trees, Clustering, etc. with Scikit-learn. 

### Components of scikit-learn
Scikit-learn comes loaded with a lot of features. Here are a few of them to help you understand the spread:
* **Supervised learning algorithms**: Think of any supervised machine learning algorithm you might have heard about and there is a very high chance that it is part of scikit-learn. Starting from Generalized linear models (e.g Linear Regression), Support Vector Machines (SVM), Decision Trees to Bayesian methods – all of them are part of scikit-learn toolbox.
* **Cross-validation**: There are various methods to check the accuracy of supervised models on unseen data using sklearn.
* **Unsupervised learning algorithms**: Again there is a large spread of machine learning algorithms in the offering – starting from clustering, factor analysis, principal    component analysis to unsupervised neural networks.
* **Feature extraction**: Scikit-learn for extracting features from images and text

Check out https://www.tutorialspoint.com/scikit_learn/scikit_learn_introduction.htm and [this documentation](https://scikit-learn.org/stable/) to get a deeper understanding of deploying it in machine learning, pre-processing, cross-validation and visualization algorithms.

## Data Collection
→ The quantity & quality of your data dictate how accurate our model is

→ The outcome of this step is generally a representation of data (Guo simplifies to specifying a table) which we will use for training

→ Using pre-collected data, by way of datasets from [Kaggle](https://www.kaggle.com/), [UCI](https://archive.ics.uci.edu/ml/datasets.php), etc., still fits into this step

→ Another way of collecting data is **[Web Scraping](https://www.geeksforgeeks.org/what-is-web-scraping-and-how-to-use-it/)** using packages like BeautifulSoup. Learn web scraping in python from [here](https://www.geeksforgeeks.org/implementing-web-scraping-python-beautiful-soup/). Also here's a good [Youtube Video](https://www.youtube.com/watch?v=uufDGjTuq34) .

## Data Preparation
→ Wrangle data and prepare it for training

→ Clean that which may require it (remove duplicates, correct errors, deal with missing values, normalization, data type conversions, etc.)

→ Randomize data, which erases the effects of the particular order in which we collected and/or otherwise prepared our data

→ Visualize data to help detect relevant relationships between variables or class imbalances (bias alert!), or perform other exploratory analysis

→ Split into training and evaluation sets

Learn more about [Data Preparation](https://www.alteryx.com/glossary/data-preparation) and **Exploratory Data Analysis** which is arguably the most important step. Here's a good [Youtube Playlist](https://youtube.com/playlist?list=PLZoTAELRMXVPQyArDHyQVjQxjj_YmEuO9) for EDA. [Here's](https://www.youtube.com/watch?v=v5dqavbyE-I) a short video recap for EDA.

## *File Handling*
Since we have covered a good number of topics , we are keeping File Handling as optional.Those who are interested in learning this can go through the article below.

Files are named locations on disk to store related information. They are used to permanently store data in a non-volatile memory (e.g. hard disk). Since Random Access Memory (RAM) is volatile (which loses its data when the computer is turned off), we use files for future use of the data by permanently storing them. When we want to read from or write to a file, we need to open it first. When we are done, it needs to be closed so that the resources that are tied with the file are freed.

Hence, in Python, a file operation takes place in the following order:

* Open a file
* Read or write (perform operation)
* Close the file

To read more about File Handling refer [this](https://www.geeksforgeeks.org/file-handling-python/)


This brings us to the end of this week's material. By now you should  be familiar with the basics of python. You should have a good enough idea about concepts like data types, loops, operators, iterators, functions, modules and packages, classes in python. Do go through the assignment after finishing the reading material. It will give you a chance to apply these concepts and practice your skills. Next week we will learn to use python in the field of data analysis. 

## Assignment

You should now be able to complete the snippet of code designed to read a particular piece of text and answer user's queries about certain words by printing the context in which these words appeared in the text. You can find it as a Jupyter Notebook [here](https://github.com/mohak2003/WIDS-23-24/blob/main/Week%201/assignment-1.ipynb).


# Project - Programming for Data Analysis

* **Author:** John Paul Lee
* **Github:** JPLee01
* **Email:** G00387906@gmit.ie
* **Created:** 26-11-2020, **Last update:** 03-01-2021
------------------------------------------------------------------------------------------------
**Programming for Data Analysis:** 

This Jupyter Notebook has been created to simulate a data set of real-world data using the numpy.random packge in Python. This notebook will investigate the types of variables involved, their likely distributions, and their relationships with each other. While also synthesising/simulating the data set as closely matching the properties as possible.

**Lecturer:** Dr. Brian McGinley

The Project instructions can be found at [here](https://github.com/JPLee01/Programming_for_Data_Analysis-Project/blob/main/Project%20Instructions.pdf)

**Table of Contents**
------------------------------------------------------------------------------------------------

[Project - Programming for Data Analysis](#Project-Programming-for-Data-Analysis)

[1. Introduction](#1-introduction)

[2. Project Repository](#2-project-repository)

[3. Real-World Phenomenon](#3-real-world-phenomenon)

[4. Problem Statement](#4-Problem-Statement)

[5. User Guide](#5-User-Guide)

  [5.1 Downloading the Repository](#5.1-Downloading-the-Repository)

  [5.2  Running the Program](#5.2-Running-the-Program)

  [5.3  Libraries](#5.3-Libraries)

[6. Summary, Conclusion and Future Analysis of of the Simulated Data Set](#6.-Summary,-Conclusion-and-Future-Analysis-of-the-Simulated-Data-Set)

[7. References](#7-References)

[8. Bibliography](#8-Bibliography)

## 1 Introduction
------------------------------------------------------------------------------------------------
As part of the Project for the Programming for Data Analysis module a Jupyter Notebook has been created to simulate a data set of real-world data using the *numpy.random* package in Python. This notebook will investigate the types of variables involved, their likely distributions, and their relationships with each other. While also synthesising/simulating the data set as closely matching the properties as possible.
This analysis will be conducted through a Jupyter Notebook which will contain markdown text, images, Python code and Plots. 

## 2 Project Repository
------------------------------------------------------------------------------------------------
The Project Repository is the source where all the work associated with
the project will be stored. It contains the following files and can be
located [here](https://github.com/JPLee01/Programming_for_Data_Analysis-Project):

  **File**    |     **Description**
  ---------   |   --------------------------------------------------------
  .gitignore | A Text File explicitly explaining to Git which files or folders to ignore in the Assignment
  Project Instructions.pdf | A PDF copy of the Poject Instructions
  LICENSE     |    MIT License for the project
  Programming_for_Data_Analysis-Project.ipynb | Jupyter Notebook created to  in Python
  README.md   |    This file; A Description of the project and instructions

## 3  Real-World Phenomenon
------------------------------------------------------------------------------------------------
 For the purpose of this project the author chose the use of mobile devices by children for the simulation a real-world phenomenon. The reason this topic was chosen by the author is that it is an area in which the author is activly interested in. As an expectant father, the author is acutely aware that todays generation are exposed to more mobile devices at a younger age than ever before. The author is conscious that while there are benefits to children using mobile devices, there are also potential negative effects and it is something which the author would like to explore.

## 4 Problem Statement
------------------------------------------------------------------------------------------------
As part of the project, the student was given a set of instructions which can be viewed [here](https://github.com/JPLee01/Programming_for_Data_Analysis-Project/blob/main/Project%20Instructions.pdf). As seen, within the instructions a problem statement was printed. It stated that for this project the student must create a data set by simulating a real-world phenomenon of their choosing. The student may pick any phenomenon they wish and may one of interest to the student in your personal or professional life. Then, rather than collect data related to the phenomenon, the student should model and synthesise such data using Python. The instructions suggest the *numpy.random* package is used for this. Specifically, the instruction state the project should:
* Choose a real-world phenomenon that can be measured and for which you could
collect at least one-hundred data points across at least four different variables.
* Investigate the types of variables involved, their likely distributions, and their
relationships with each other.
* Synthesise/simulate a data set as closely matching their properties as possible.
* Detail your research and implement the simulation in a Jupyter notebook – the
data set itself can simply be displayed in an output cell within the notebook.

## 5 User Guide
------------------------------------------------------------------------------------------------
This section will describe the steps required to download and run the files in the repository.

### 5.1 Downloading the Repository
The repository is stored at the following: https://github.com/JPLee01/Programming_for_Data_Analysis-Project

To download the repository, do the following:
1.  Click on the above link to open the repository
2.  Once in the repository, click on the green “clone or download” button on the right side of the screen.
3.  Select "Download ZIP". This will open a prompt allowing you to save the file to a desired location on your computer.
4.  Navigate to where  the ZIP files are located on your computer and extract the compressed (.zip) files.

### 5.2 Running the Program
Once the repository has been downloaded, you will need to ensure that you are running it in the correct environment. It should be noted that this repository has been written using Python 3.8.2 and consequently it will require a Python version of 3.7 at a minimum to run as designed. The repository also requires a number of external Python libraries [seen below](#5.3-Libaries) to execute correctly. Once the correct version of Python has been installed complete with necessary libraries and the ZIP has been downloaded and extracted the user can run the program. The running of any of the programs from the command line can be executed as follows:
1.  Open a command prompt (cmd) or equivalent on your computer.([Cmdr](https://cmder.net) is recommended for Windows computers, Mac Computers via the terminal)
2.  Navigate to the desired location through the use of the change directory (cd) command.
3. Run Jupyter Notebook by typing the following at the command prompt (do not close the command prompt window throughout):
```
jupyter notebook
```
4. A notebook server should automatically launch in your default web browser (URL should be http://localhost:8888). If this does not happen, read the command prompt output. You can copy and paste the above URL into your web browser to access Jupyter Notebook.
6. Using the menu on the left side of the page, double click the jupyter notebook file:
```
Programming_for_Data_Analysis-Project.ipynb
```
7. The notebook should open in a new tab. You can run each cell with the keyboard shortcut SHIFT+ENTER, alternatively use the "play" button on the menu bar. Please note that certain cells must be run before others e.g. the cells importing the various Python libraries. You may find it convenient to use the "Run all Cells" option in the "Run" dropdown menu.

### 5.3 Libraries
The following Python libraries were used in the writing of the projects code and are required to successfully run the programs:
* [Numpy](https://www.numpy.org/) - Used for mathematical functions in the [Programming_for_Data_Analysis-Project.ipynb](https://github.com/JPLee01/Programming_for_Data_Analysis-Project/blob/main/Programming_for_Data_Analysis-Project.ipynb) notebook.
* [Pandas](https://pandas.pydata.org/) - Used for import, management, data manipulation and analysis in the [Programming_for_Data_Analysis-Project.ipynb](https://github.com/JPLee01/Programming_for_Data_Analysis-Project/blob/main/Programming_for_Data_Analysis-Project.ipynb) notebook.
* [Matplotlib.pyplot](https://matplotlib.org/tutorials/introductory/pyplot.html) - Used for the manipulation of elements and the creation of certain plots graphs and plots within the [Programming_for_Data_Analysis-Project.ipynb](https://github.com/JPLee01/Programming_for_Data_Analysis-Project/blob/main/Programming_for_Data_Analysis-Project.ipynb) notebook.
* [seaborn](https://seaborn.pydata.org/) - Used for the creation and manipulation of all plots in the [Programming_for_Data_Analysis-Project.ipynb](https://github.com/JPLee01/Programming_for_Data_Analysis-Project/blob/main/Programming_for_Data_Analysis-Project.ipynb) notebook.
* [sklearn](https://scikit-learn.org/stable/) - Used to implement machine learning on the data set within the [Programming_for_Data_Analysis-Project.ipynb](https://github.com/JPLee01/Programming_for_Data_Analysis-Project/blob/main/Programming_for_Data_Analysis-Project.ipynb) notebook.

## 6 Summary, Conclusion and Future Analysis of the Simulated Data Set
------------------------------------------------------------------------------------------------
In summary, the author chose to create a data set based around the the use of mobile devices by children. The author chose this for personal reasons as it was an area close to thier heart. The author selected gender, age, screen time (hours a week) and number of apps interacted with as the four variables and chose a sample size of 1250. The author then attempted to model each variable as closely as possible to real-world conditions by referencing a multitude of sources including acamedic papers, studies and media reports. The author then merged the four variables into a data set and analysed the relationships of variables in terms of correlation, covariance and regression. Each area was discussed in detail and observations and potential areas for further exploratory analysis were highlighted. Finally, the possibility of implementing machine learning on the data set and the opportunities it can create were observed through the use of a simplistic example. 

In conclusion the author is of the opinion that the project was a very worthwile and rewarding experience. While the project at times pushed the author outside their comfort zome, it allowed for an experience and an appreciation for the construction and simulation of data sets to be gained. This the author feels can only benefit them as they continue thier studies. While the jupyter notebook created the author feels will become a valuable learning aid into the future. 

In terms of future analysis of the simulated data set the possibilities are limitless. As the name suggests, the simulated data set has the potential to be reanalysed and reassessed using entirely different distributions for the variables, as well as, completely different exploratory functions. The author also in their research identified some relationships which could benefit from further exploratory analysis and alluded to them in the [Programming_for_Data_Analysis-Project.ipynb](https://github.com/JPLee01/Programming_for_Data_Analysis-Project/blob/main/Programming_for_Data_Analysis-Project.ipynb) notebook. The author would also feel that the machine learning examples demonstrated in the [Programming_for_Data_Analysis-Project.ipynb](https://github.com/JPLee01/Programming_for_Data_Analysis-Project/blob/main/Programming_for_Data_Analysis-Project.ipynb) notebook could certainly benefit from further analysis.

## 7 References
------------------------------------------------------------------------------------------------
References will be indicated numerically throughout the Jupyter Notebook and will be listed in full at the end.

## 8 Bibliography
------------------------------------------------------------------------------------------------
Within the course of this project the following sources were used for research purposes:

* Analytics Vidhya - 6 Common Probability Distributions every data science professional should know, <https://www.analyticsvidhya.com/blog/2017/09/6-probability-distributions-data-science/>

* Audrey Conklin - People spending 3.1 hours a day on smartphone apps: Study, <https://www.foxbusiness.com/technology/average-time-spent-phone-apps> 

* BC Campus - The Exponential Distribution, <https://opentextbc.ca/introstatopenstax/chapter/the-exponential-distribution/>

* Bee Guan Teo - Hands-On Python Data Visualization — Seaborn Count Plot, <https://towardsdatascience.com/hands-on-python-data-visualization-seaborn-count-plot-90e823599012>

* Catherine Scruggs - How to Determine the Sample Size in a Quantitative Research Study, <https://sciencing.com/determine-size-quantitative-research-study-8072459.html>

* Charlie Custer - How to Analyze Survey Data with Python for Beginners, <https://www.dataquest.io/blog/how-to-analyze-survey-data-python-beginner/>

* Christopher Bratkovics - Exploratory Data Analysis Tutorial in Python, <https://towardsdatascience.com/exploratory-data-analysis-tutorial-in-python-15602b417445>

* Coursera - Getting Started Analyzing Data in Python, <https://www.coursera.org/lecture/data-analysis-with-python/getting-started-analyzing-data-in-python-236Ip>

* Data Science - make seaborn heatmap bigger, <https://datascience.stackexchange.com/questions/17540/make-seaborn-heatmap-bigger>

* David Amos - How to Round Numbers in Python, <https://realpython.com/python-rounding/>

* Edureka - How to fix this ValueError invalid literal for int with base 10 error in Python, <https://www.edureka.co/community/30685/this-valueerror-invalid-literal-for-with-base-error-python>

* ESRI - Growing Up in Ireland: National Longitudinal Study of Children, <https://www.esri.ie/system/files?file=media/file-uploads/2015-07/BKMNEXT284.pdf>

* ESRI - Later is Better: Mobile Phone Ownership and Child Academic Development, <https://www.esri.ie/system/files/publications/RB201903_01.pdf>

* EW Weisstein - Beta Distribution: Definition, Calculation, <https://www.statisticshowto.com/beta-distribution/>

* EW Weisstein - Correlation Coefficient: Simple Definition, Formula, Easy Steps, <https://www.statisticshowto.com/probability-and-statistics/correlation-coefficient-formula/>

* EW Weisstein - Exponential Distribution / Negative Exponential: Definition, Examples, <https://www.statisticshowto.com/exponential-distribution/>

* Geeks for Geeks - Python | Remove square brackets from list, <https://www.geeksforgeeks.org/python-remove-square-brackets-from-list/>

* Grepper - Create Age-Groups in Pandas, <https://www.codegrepper.com/code-examples/python/create+age-groups+in+pandas>

* Hossein Pishro-Nik - Exponential Distribution, <https://www.probabilitycourse.com/chapter4/4_2_2_exponential.php>

* Hosokawa et al. - Association between mobile technology use and child adjustment in early elementary school age, <https://www.ncbi.nlm.nih.gov/pmc/articles/PMC6059409/>

* Investopedia - How do you interpret the magnitude of the covariance between two variables?, <https://www.investopedia.com/ask/answers/041515/how-do-you-interpret-magnitude-covariance-between-two-variables.asp>

* Janux - 3.7.1. Discrete Uniform Probability Distribution, <https://www.youtube.com/watch?v=pc92J_DIwZo>

* James Chen - Skewness, <https://www.investopedia.com/terms/s/skewness.asp>

* Jim Frost - How to Identify the Distribution of Your Data, <https://statisticsbyjim.com/hypothesis-testing/identify-distribution-data/>

* Jim Frost - Interpreting Correlation Coefficients, <https://statisticsbyjim.com/basics/correlations/>

* Jim Frost - Regression Analysis, <https://statisticsbyjim.com/glossary/regression-analysis/>

* Jim Frost - When Should I Use Regression Analysis?, <https://statisticsbyjim.com/regression/when-use-regression-analysis/>

* JMP - Correlation, <https://www.jmp.com/en_au/statistics-knowledge-portal/what-is-correlation.html>

* Joshua Ebner - How To Use Numpy Random Choice, <https://www.sharpsightlabs.com/blog/numpy-random-choice/>

* Jupyter Notebook - Markdown Cells, https://jupyter-notebook.readthedocs.io/en/stable/examples/Notebook/Working%20With%20Markdown%20Cells.html

* Kaggle - Detailed exploratory data analysis with python, <https://www.kaggle.com/ekami66/detailed-exploratory-data-analysis-with-python>

* KDnuggets - Probability Distributions in Data Science , <https://www.kdnuggets.com/2020/02/probability-distributions-data-science.html>

* Keith Galli - Generating Mock Data with Python! (NumPy, Pandas, & Datetime Libraries), <https://www.youtube.com/watch?v=VJBY2eVtf7o>

* KidsHealth Medical Experts - Screen Time Guidelines for Teens, <https://kidshealth.org/en/parents/screentime-teens.html>

* Laerd Statistics - Linear Regression Analysis using SPSS Statistics, <https://statistics.laerd.com/spss-tutorials/linear-regression-using-spss-statistics.php>

* Learning about Electronics - How to Create a Countplot in Seaborn with Python, <http://www.learningaboutelectronics.com/Articles/How-to-create-a-countplot-in-seaborn-with-Python.php>

* Lumen - The Exponential Distribution, <https://courses.lumenlearning.com/introstats1/chapter/the-exponential-distribution/>

* Manu Jeevan - Step by step approach to perform data analysis using Python, <https://bigdata-madesimple.com/step-by-step-approach-to-perform-data-analysis-using-python/>

* Margriet Groenendijk - Analyze open data sets using pandas in a Python notebook, <https://medium.com/@MargrietGr/analyze-open-data-sets-using-pandas-in-a-python-notebook-64e93776370a>

* Matplotlib Manual Version 3.1.2 - matplotlib.axes.Axes.hist, <https://matplotlib.org/3.1.1/api/_as_gen/matplotlib.axes.Axes.hist.html>

* Minitab - Interpret the key results for Covariance, <https://support.minitab.com/en-us/minitab-express/1/help-and-how-to/modeling-statistics/regression/how-to/covariance/interpret-the-results/>

* Mirko Stojiljković - NumPy, SciPy, and Pandas: Correlation With Python, <https://realpython.com/numpy-scipy-pandas-correlation-python/#linear-regression-scipy-implementation>

* Natassha Selvaraj - A Beginner’s Guide to Data Analysis in Python, <https://towardsdatascience.com/a-beginners-guide-to-data-analysis-in-python-188706df5447>

* OpenStax - Descriptive Statistics: Skewness and the Mean, Median, and Mode, <https://cnx.org/contents/bE-w34Vi@9/Descriptive-Statistics-Skewness-and-the-Mean-Median-and-Mode>

* Pandas Manual Version 1.2.0 - How do I select a subset of a DataFrame?, <https://pandas.pydata.org/docs/getting_started/intro_tutorials/03_subset_data.html>

* Pandas Manual Version 1.2.0 - Merge, join, concatenate and compare, <https://pandas.pydata.org/pandas-docs/stable/user_guide/merging.html>

* Primary Times - I’ve Got Your Number: Mobile Phones and kids, <https://www.primarytimes.ie/news/2017/03/i-ve-got-your-number-mobile-phones-and-kids>

* Psycom.net – Teenage Cell Phone Addiction: Are You Worried About Your Child?, <https://www.psycom.net/cell-phone-internet-addiction>

* Python-course.eu - Synthetical Test Data With Python,<https://www.python-course.eu/synthetical_test_data_with_python.php>

* Rebecca Vickery - Tips and Tricks for Fast Data Analysis in Python, <https://towardsdatascience.com/tips-and-tricks-for-fast-data-analysis-in-python-f108ad32fa90>

* Ritika Singh - Exploratory Data Analysis(EDA) in Python!, <https://www.analyticsvidhya.com/blog/2020/08/exploratory-data-analysiseda-from-scratch-in-python/>

* Ruth et al. - U.S. High School Teenager Mobile App Usage, <https://askwonder.com/research/customer-demographics-u-s-high-school-teenager-mobile-app-usage-jvhvea91v>

* Sachin Date - Assumptions of Linear Regression, <https://towardsdatascience.com/assumptions-of-linear-regression-5d87c347140>

* Sarah Littler - The Importance and Effect of Sample Size, <https://select-statistics.co.uk/blog/importance-effect-sample-size/>

* Sarah Perez - Time Spent In Apps Up 63 Percent Over Past Two Years, But Apps Used Monthly Show Little Change, <https://techcrunch.com/2015/06/11/time-spent-in-apps-up-63-percent-over-past-two-years-but-apps-used-monthly-shows-little-change/?_ga=2.136615664.1796286822.1608671755-1393211290.1608671755>

* Science Direct - Power Law Distribution, <https://www.sciencedirect.com/topics/mathematics/power-law-distribution>

* Seaborn Manual Version 0.11.1 - Scatterplot with varying point sizes and hues, <https://seaborn.pydata.org/examples/scatter_bubbles.html>

* Shane Lynn - Using iloc, loc, & ix to select rows and columns in Pandas DataFrames, <https://www.shanelynn.ie/select-pandas-dataframe-rows-and-columns-using-iloc-loc-and-ix/>

* Srishti Saha - Baffled by Covariance and Correlation??? Get the Math and the Application in Analytics for both the terms, <https://towardsdatascience.com/let-us-understand-the-correlation-matrix-and-covariance-matrix-d42e6b643c22>

* Stack Exchange - Logistic regression score is negative, <https://datascience.stackexchange.com/questions/40670/logistic-regression-score-is-negative>

* Stack Overflow - Determine Whether Integer Is Between Two Other Integers?, <https://stackoverflow.com/questions/13628791/determine-whether-integer-is-between-two-other-integers?

* Stack Overflow - How to map numeric data into categories / bins in Pandas dataframe, <https://stackoverflow.com/questions/49382207/how-to-map-numeric-data-into-categories-bins-in-pandas-dataframe>

* Stack Overflow - How to select rows from a DataFrame based on column values, <https://stackoverflow.com/questions/17071871/how-to-select-rows-from-a-dataframe-based-on-column-values>

* Stack Overflow - In Python pandas, start row index from 1 instead of zero without creating additional column, <https://stackoverflow.com/questions/32249960/in-python-pandas-start-row-index-from-1-instead-of-zero-without-creating-additi/32249984>

* Stack Overflow - matplotlib: Controlling pie chart font color, line width, <https://stackoverflow.com/questions/1915871/matplotlib-controlling-pie-chart-font-color-line-width?lq=1>

* Stack Overflow - Random experiment of Binomial distribution using stats in python, <https://stackoverflow.com/questions/55113404/random-experiment-of-binomial-distribution-using-stats-in-python>

* Stan Brown - Measures of Shape: Skewness and Kurtosis, <https://brownmath.com/stat/shape.htm>

* Statistics Solutions - Pearson’s Correlation Coefficient, <https://www.statisticssolutions.com/pearsons-correlation-coefficient/>

* Statista - Population of Ireland by age group in 2019, <https://www.statista.com/statistics/710767/irish-population-by-age/>

* Study.com - Skewed Distribution: Examples & Definition, <https://study.com/academy/lesson/skewed-distribution-examples-definition-quiz.html>

* Vlad Bezden - How to set seaborn plot size in Jupyter Notebook, <https://medium.com/@vladbezden/how-to-set-seaborn-plot-size-in-jupyter-notebook-63ffb1415431>

* Walum, H. and De Leon, D. - A tale of two variables: Covariance and Correlation, <https://tinystats.github.io/teacups-giraffes-and-statistics/05_correlation.html#covariance>

* Wolfram Mathworld - Exponential Distribution, <https://mathworld.wolfram.com/ExponentialDistribution.html>

* Wolfram Mathworld - Normal Distribution, <https://mathworld.wolfram.com/NormalDistribution.html>
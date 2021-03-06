# R and Python Data Wrangling

Home of my Fall 2020 Honors project. Goal is to learn about key data science tools and compare and contrast the two key languages for it: R and Python. 

<h2>Key differences between R and Python</h2>

<h3>R</h3>
+ ggplot2 is a good plotting library for R. <br>
+ Importing datasets from a package and from a url.
+ Rmd files instead of Jupyter
+ MUCH BETTER wrangling functions within the tidyverse and dplyr. Chapter 4 was a pain with Python Pandas. Far too verbose. <br>
+ Fitting models and graphing is much much simpler.


<h3>Python</h3>
+ Pandas is a huge component of Python Data Wrangling. Encompasses the data frame and csv reading for example. <br>
+ No really good ggplot equivalent in Python. The libraries that are available feel like R anyway if they try to emulate ggplot2. <br> 
+ Jupyter Notebook (formally/now encompasses IPython Notebooks)
+ I use anaconda, which comes with a Python installation and a "in my opinion" better pip command, the conda command. <br>
- YIKES. Fitting models and graphing in Python is a mess. There are several options that are not easy to use, especially if you are not a stats expert...

<h2> Notes/Comments on Exercises </h2>

**Module 1 (8/17/2020)**

Using Anaconda, installation video: https://www.youtube.com/watch?v=YJC6ldI3hWk

Jupytr Notebook contains IPython Notebooks: https://www.youtube.com/watch?v=HW29067qVWk

  - Navigate to git repo in powershell
  - Type command: jupyter notebook
  - Redirect to localhosted jupyter repo.
 
 
Pandas and file reading: https://realpython.com/pandas-python-explore-dataset/
 
Export to pdf works badly in Jupyter's gui, trying on the command line. 
Command line worked perfectly using:

**jupyter nbconvert Chp1Exercises.ipynb --to pdf**

**Module 2 (8/17/2020)**

Using Anaconda, installation video: https://www.youtube.com/watch?v=YJC6ldI3hWk

Jupytr Notebook contains IPython Notebooks: https://www.youtube.com/watch?v=HW29067qVWk

  - Navigate to git repo in powershell
  - Type command: jupyter notebook
  - Redirect to localhosted jupyter repo.
 
 
Pandas and file reading: https://realpython.com/pandas-python-explore-dataset/
 
Export to pdf works badly in Jupyter's gui, trying on the command line. 
Command line worked perfectly using:

**jupyter nbconvert Chp1Exercises.ipynb --to pdf**





**Module 4 (9/04/2020)**

Filtering in python based on multiple values: https://thispointer.com/python-pandas-select-rows-in-dataframe-by-conditions-on-multiple-columns/

Mutating and creating new columns in df with a for loop and iterrows(): https://stackoverflow.com/questions/56916916/pandas-calculations-across-rows-and-columns

Cut function in Pandas: https://pandas.pydata.org/pandas-docs/stable/reference/api/pandas.cut.html

Pd cut: https://stackoverflow.com/questions/45751390/pandas-how-to-use-pd-cut

To access and add dataframe: 

body[<colName>] = <Whatever you want to add>
  
  
**Module 5 (9/11/2020)**
Fitting models with statsmodels.api in Python: statsmodels.org/stable/gettingstarted.html
 
Scatterplots with facet grid using Seaborn: https://seaborn.pydata.org/generated/seaborn.FacetGrid.html

Deleting rows based on condition: https://stackoverflow.com/questions/18172851/deleting-dataframe-row-in-pandas-based-on-column-value

Reference table for linear regression model value access: https://www.statsmodels.org/stable/generated/statsmodels.regression.linear_model.RegressionResults.html#statsmodels.regression.linear_model.RegressionResults

Get confidence intervals from Python statsmodels: https://stackoverflow.com/questions/17559408/confidence-and-prediction-intervals-with-statsmodels/17560456

**Is something wrong with your RMarkdown Knit positioning? It is probably your headers. Check that the number of # symbols you have is valid. Two is preferrable for exercise headings.**

**Module 6/7(9/20/2020)**

R normals refernce: https://stat.ethz.ch/R-manual/R-devel/library/stats/html/Normal.html

Sorting columns by another column in Python Pandas: https://stackoverflow.com/questions/34347041/pandas-sort-a-column-by-values-in-another-column
https://pandas.pydata.org/pandas-docs/stable/reference/api/pandas.DataFrame.sort_values.html

Seaborn lineplots: https://seaborn.pydata.org/generated/seaborn.lineplot.html

Seaborn graph gallery: https://seaborn.pydata.org/examples/index.html

**Module 8/9(9/27/2020)**


Guide to vectors, lists, and matricies in Python with NumPy: https://www.oreilly.com/library/view/machine-learning-with/9781491989371/ch01.html


Drop NA from dataframe Pandas: https://pandas.pydata.org/pandas-docs/stable/reference/api/pandas.DataFrame.dropna.html


Drop NA columns: https://stackoverflow.com/questions/45147100/pandas-drop-columns-with-all-nans


Select based on condition Pandas DF: https://chrisalbon.com/python/data_wrangling/pandas_selecting_rows_on_conditions/


Select all but one column: https://stackoverflow.com/questions/29763620/how-to-select-all-columns-except-one-column-in-pandas


Select from matrix numpy: https://thispointer.com/python-numpy-select-rows-columns-by-index-from-a-2d-ndarray-multi-dimension/


Ndarray to fill in values to specified matrix size: https://numpy.org/doc/stable/reference/generated/numpy.ndarray.html

**Module 10/11(10/4/2020)**
Benchmarking in a Jupyter notebook: https://stackoverflow.com/questions/32565829/simple-way-to-measure-cell-execution-time-in-ipython-notebook %%timeit and %%time are now magic commands in Python built in! 

Magic commands: https://ipython.org/ipython-doc/3/interactive/magics.html

Regex matching and compilation with re library in Python: https://docs.python.org/3/howto/regex.html

**Module 12(10/11/2020)** 
**Used libraries:** 
import pandas as pd
import numpy as np
import datetime
from dateutil.relativedelta import relativedelta
import pytz

Python solution powered by the datetime https://docs.python.org/3/library/datetime.html
Convert string to date: https://stackabuse.com/converting-strings-to-datetime-in-python/
Python arithmetic on dates with relativedelta https://www.pythonprogramming.in/add-n-number-of-year-month-day-hour-minute-second-to-current-date-time.html
Datedelta for arithmetic: https://pypi.org/project/datedelta/
RelativeDelta to calculate intervals between dates: https://www.odoo.com/forum/help-1/question/how-do-i-calculate-number-of-months-between-two-dates-9443
Alternate number of days between dates calculation: https://stackoverflow.com/questions/151199/how-to-calculate-number-of-days-between-two-given-dates
Set primary index of pandas dataframe: https://pandas.pydata.org/pandas-docs/stable/reference/api/pandas.DataFrame.set_index.html
Filtering dataframe on dates (didn't work fully): https://stackoverflow.com/questions/22898824/filtering-pandas-dataframes-on-dates
First and last row of dataframe: https://stackoverflow.com/questions/36542169/extract-first-and-last-row-of-a-dataframe-in-pandas
Timezones with pytz: http://pytz.sourceforge.net/
Misc lambda function examples: https://www.w3schools.com/python/python_lambda.asp

**Module 13(10/18/2020)**
Good comparison of data reshaping with R and Python Pandas https://pandas.pydata.org/docs/getting_started/comparison/comparison_with_r.html
Merging and combining in Pandas: https://pandas.pydata.org/pandas-docs/stable/user_guide/merging.html
Count and Series to Dataframe conversions for problem 1: https://stackoverflow.com/questions/38933071/group-by-two-columns-and-count-the-occurrences-of-each-combination-in-pandas

**Module 16(11/9/2020)**
Pandas read_html for web scraping: https://pandas.pydata.org/pandas-docs/stable/reference/api/pandas.read_html.html
Beautiful Soup + Pandas: https://stackoverflow.com/questions/50633050/scrape-tables-into-dataframe-with-beautifulsoup (See answer 2, not the accepted answer)
Mod_security workaround for 405 Forbidden errors: https://stackoverflow.com/questions/16627227/http-error-403-in-python-3-web-scraping?lq=1

**Needed libraries:**

**Pandas** for data frames

**Requests** for grabbing the remote csv

**Numpy** for np.arrays to interface with a data frame

# Useful Resources
R Graphics Cookbook for Plots, Graphics, and Graphs. http://www.cookbook-r.com/Graphs/ <br>
Used to create textbooks using R markdown. https://bookdown.org




# Presentation
See the final presentation directory to view the slides comparing R and Python.

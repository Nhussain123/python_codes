# python_codes
# Introduction to Data Science in Python
Objectives: 
1) How to write and execute Python code with DataCamp
2) How to load data from a spreadsheet into Python
3) How to turn data into plots

# Modules:
1) Groups related tools together i.e bar charts, line charts, and histograms.
2) Makes it easy to know where to look for a particular tool
Common tool examples: matplotlib, pandas, scikit-learn, scipy, nltk

To use a module you must import module first
import pandas as pd
from matplotlib import pyplot as plt

# Creating variables 
name = "Bayes"
height = 24
weight = 75.5

Variables must start with a letter. Cannot use special characters. Case sensitive.

#Floats and strings
Float represents integer or decimal
String represents test; can contain letters, numbers spaces and special characters

To find out current value of a variable you type print(variable)

#Functions
Function is an action
pd.read_csv() turns a csv file into a table in Python
plt.plot() turns data into a line plot
plt.show() displays the plot in a new window

e.g
import pandas as pd
from matplotlib import pyplot as plit

df= pd.read_csv('letter_frequency.csv')

plt.plot(df.letter_index, df.frequency, label='Ransom')
plt.show()

Function - plt.plot Positional Arguments - (df.letter_index, df.frequency, keyword argument - label='Ransom')

Function name has two parts
plt.plot - first part where module comes from (plt), second part after. is the name of the function followed by ()

positional arguments are the input to a function; tells the function how to work
Order matters - X axis comes first then the Y axis
remember to add commas, middle and end. 

key word argument - label = 'Ransom'
comes after positional arguments
This argument lets you create a legend for graph

Both postional and keyword arguments must be seperated by commas

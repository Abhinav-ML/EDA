# Exploratory Data Analysis (EDA)

Exploratory Data Analysis (EDA) is an approach to analyze the data using visual techniques. It is used to discover trends, patterns, or to check assumptions with the help of statistical summary and graphical representations. 

## Handling Missing Values
There are several useful functions for detecting, removing, and replacing null values in Pandas DataFrame :
isnull()
notnull()
dropna()
fillna()
replace()
interpolate()
# Data visualization
Data Visualization is the process of analyzing data in the form of graphs or maps, making it a lot easier to understand the trends or patterns in the data. There are various types of visualizations – 

### Univariate analysis: 
This type of data consists of only one variable. The analysis of univariate data is thus the simplest form of analysis since the information deals with only one quantity that changes. It does not deal with causes or relationships and the main purpose of the analysis is to describe the data and find patterns that exist within it.
### Bi-Variate analysis: 
This type of data involves two different variables. The analysis of this type of data deals with causes and relationships and the analysis is done to find out the relationship among the two variables.
### Multi-Variate analysis: 
When the data involves three or more variables, it is categorized under multivariate.

**Note: We will use Matplotlib and Seaborn library for the data visualization.**

**Histogram :** It can be used for both uni and bivariate analysis. 
**Boxplot :** It can also be used for univariate and bivariate analyses.
**Scatter Plot :** It can be used for bivariate analyses.
For **multivariate analysis**, we can the pairplot()method of seaborn module. We can also use it for the multiple pairwise bivariate distributions in a dataset.

## Handling Outliers
An Outlier is a data-item/object that deviates significantly from the rest of the (so-called normal)objects. They can be caused by measurement or execution errors. The analysis for outlier detection is referred to as outlier mining. There are many ways to detect the outliers, and the removal process is the data frame same as removing a data item from the panda’s dataframe.

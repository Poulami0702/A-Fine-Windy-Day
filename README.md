# A-Fine-Windy-Day
Prediction of  power (Kw/h) generated from the windmills based on features provided in the dataset. 
------

### Data Profiling : [Report](https://www.kaggleusercontent.com/kf/62738009/eyJhbGciOiJkaXIiLCJlbmMiOiJBMTI4Q0JDLUhTMjU2In0..1ztVzsZwCrakJLt79OGdoQ.ef47_elrir4d9YQPOOn0u-YuRE0E-JR98CaFhW2emIBlRmDgWZM7DCnrez601ogoWTHFfslD-YilZMca5XPbmAuPZKQiVkwMajQV4JRIct4siAd6OQLOJ19Ln93T6djAZG4nm0u2KEmAvsCzhOPyYczdYyrOGRVb_1a9cjATiro_N4MGl4MlhK48sexoDXZjBt7tggUdWXHPQoYvUbe7xdya3DvPX23Qo6_oLAYW4QD38YaD7n1oGtp3ZUkYnoJcOe1M6BxhB_1J5kMTBjjc-7uGus6rEH8CRDb6gB7ODburn1sVoVQM07qqrs-ecYarI_skrhJL33QTe1E4zQA0jmAdtmEUJUUQ1NdmGSv7JzTFfa4YA8HNG7rX-6TiI60ltlJ9f_cQTlzqnis62H7TFvwB09ypRauqS2rTuG0Gmqn-PFqKx9i22ktyWUr33vhGYt8s6KdnNFxrffM4bCAUKZWgfU-Rjqym64a0aQjoaNw2YOAIm5tRr1vz11xxnd96_FgIFjBBdU40-nesvWAopK3mblZ7IPKU4AJl84NpAUC1mnEvRq9qbt-2gzyjE27gWyRwSsYgDA5ETIAzGOIHjUyc4v0wM6XYU7fQB0Bwu6gml6qb9qRhgtITKxmLkiSiK2LO89airb7sv_D-Zk9ATwnWEbokTz4jUuvzMcA91rk.vqT-iKK5caGxpjjT6XXYmg/your_report.html#overview-warnings)

------

### Dataset : [CSV](https://github.com/Poulami0702/A-Fine-Windy-Day/tree/main/dataset(windy%20day))

------

I solved this problem by using Pycaret library for model building and Pandas Profiling for Data Analysis.

#### [PyCaret](https://pycaret.org)<br> 
Pycaret is an open source, low-code machine learning library in Python that allows you to go from preparing your data to deploying your model within seconds in your choice of notebook environment.<br>
PyCaret being a low-code library makes you more productive. With less time spent coding, you and your team can now focus on business problems.<br>
PyCaret is simple and easy to use machine learning library that will help you to perform end-to-end ML experiments with less lines of code.<br>
PyCaret is a business ready solution. It allows you to do prototyping quickly and efficiently from your choice of notebook environment.<br>

#### [Pandas Profiling](https://github.com/pandas-profiling/pandas-profiling)<br>
Pandas Profiling Generates profile reports from a pandas DataFrame. The pandas df.describe() function is great but a little basic for serious exploratory data analysis. pandas_profiling extends the pandas DataFrame with df.profile_report() for quick data analysis.<br>

For each column the following statistics - if relevant for the column type - are presented in an interactive HTML report:<br>
<p>
Type inference: detect the types of columns in a dataframe.<br>
Essentials: type, unique values, missing values<br>
Quantile statistics like minimum value, Q1, median, Q3, maximum, range, interquartile range<br>
Descriptive statistics like mean, mode, standard deviation, sum, median absolute deviation, coefficient of variation, kurtosis, skewness
Most frequent values<br>
Histogram<br>
Correlations highlighting of highly correlated variables, Spearman, Pearson and Kendall matrices<br>
Missing values matrix, count, heatmap and dendrogram of missing values<br>
Text analysis learn about categories (Uppercase, Space), scripts (Latin, Cyrillic) and blocks (ASCII) of text data.
</p>

# Movie Exchange Stack Time Series Analysis

## Introduction
Time is one of the fundamental components in data analysis. By using time, we can count the frequency of activity per day or per month or explore how customer behaviors change in a moving window.

Data can be downloaded from here: https://archive.org/download/stackexchange/movies.stackexchange.com.7z
## Project
In this project I analyzed data from movie stack exchange forums. After parsing time from textual data, we can use the pandas.datetime method to extract specific temporal features like year or month. After perform data wrangling, I resampled the dataset to various temporal resolutions, and created various plots to compare the distribution of posts over time.

Data can sometime be noisy. Hence, I utilised a moving window using the rolling method. That window can also handle some missing data with the min_periods parameter.

Ploting this data on different levels of granularity and temporality can reveal different kinds of spikes or trends.

# Exploratory Data Analysis for Covid-19 USA States Dataset

## 1. Introduction

Coronavirus disease 2019, abbreviated as COVID-19, has caused coronavirus pandemic in 2019-2020. It's spread around the world very quickly.

In this blog post, we will discover the spread of COVID-19 cases in the USA States. The data that we used in this task is the [Covid-19 USA States](https://www.kaggle.com/bioinfoacademy/covid19-usa-states-cleaned-historical-and-current) from Kaggle. This data is about cases around the US States from 22 January until 26 April 2020.

The dataset consists of 109 columns, i.e Province/State, State, Country/Region, Lat (latitude), Long (longitude), and the rest is case count from January 22nd until April 26th. And for the row, it consists of 59 rows that contain all states from the US.

From this exploratory, we hope that we can answer some questions, such as:

1. Where does the first case happen?

2. Which states have the most corona cases?

3. How is the growth of the corona case to date?

4. Is there any state that has zero cases?

---

## 2. Data Wrangling

In this exploratory data analysis post, we using one of the powerful python libraries. We will be using Pandas as a library for data manipulation and analysis. Then we read the CSV file through this library, so the dataset can be operated further.

```import pandas as pd
df = pd.read_csv('time_series_19-covid-Confirmed-us-current.csv')

```

![1](https://github.com/adipurnamk/ANALYSIS-OF-COVID-19-DATASET/blob/master/1.png "Data frame snippet ")

Blog goes [here](https://www.datainsightonline.com/post/exploratory-data-analysis-for-covid-19-usa-states-dataset)

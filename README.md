# Covid-19-knowledge-discovery

As we all know, there are differences in measures taken by countries to fight the COVID-19 epidemic. Some countries implement a full lockdown on society, whereas some try to keep everyday life almost normal. The aim of this project was to examine these differences, find out which countries have chosen alternative ways, and figure out patterns between actions and registered cases.

## Usage

1. Clone this repository using `git clone https://github.com/bonskotti/covid-19-knowledge-discovery.git`

2. Launch [The Jupyter Notebook App](https://jupyter-notebook-beginner-guide.readthedocs.io/en/latest/execute.html).

3. Run [kdd_covid19_spring2020.ipynb](../master/kdd_covid19_spring2020.ipynb).

## Data

I used three datasets:

1. COVID-19 containment and mitigation measures (https://www.kaggle.com/paultimothymooney/covid19-containment-and-mitigation-measures)

2. Time series on confirmed cases globally (https://github.com/CSSEGISandData/COVID-19/blob/master/csse_covid_19_data/csse_covid_19_time_series/time_series_covid19_confirmed_global.csv)

3. Population by country in 2020 (https://www.kaggle.com/tanuprabhu/population-by-country-2020)

## What was done

Project is divided in two parts:

1. Within four selected countries, examining frequent items and common patterns between measurements and cases.

2. Within all countries, examining trends in measurements, trying out classification and anomaly detection.

## Results

1. Frequent items mostly related to the growth levels.

![Alt text](img/items.PNG?raw=true "Title")

2. Classification of a country into a cluster based on measurements taken works fairly well. In addition, it is possible to detect if a country's COVID-19 policies differ from others'.

![Alt text](img/mahal.png?raw=true "Title")

----

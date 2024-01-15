<h3 align="center">Airbnb monthly Analysis</h3>

<p align="center">
  Analysis of Airbnb datasets from Boston and Seattle
</p>

## Table of contents

- [Introduction](#introduction)
- [Motivation](#motivation)
- [What's included](#whats-included)
- [Run the code](#run-the-code)
- [Creators](#creators)
- [Thanks](#thanks)

## Introduction

This code contains a deep analysis of how the location, the month and other features affect to availability and prices for booking an apartment through Airbnb

## Motivation

As many people, I love traveling and in the recent years many applications and pages have been created making the management of a trip easier and more accessible. 
One example is Airbnb, which has become a popular page for finding and booking accomodation around the world.
But I found the more you travel, the more you notice that when you search for an accomodation, many factors can affect to the price and availability of an apartment or hotel and they are never the same.
This reason lead me to look deeper on how this factors can affect and how much deviation can be between months or locations.

## What's included

- A Jupyter notebook that contains the code use for the analysis, called "lorea-analysis-for-udacity.ipynb"
- 4 files include the datasets necessary to run the code:
	- seattle_calendar.csv
	- seattle_reviews.csv
	- boston_calendar.csv
	- boston_calendar.csv

## Run the code

First, you need to find and environment where you can execute a Jupyter Notebook.
You can download the notebook by cloning the repository: https://github.com/lalore10/AirBnb-Seattle-London-Analysis.git
At the first lines in the notebook, the files are read, so you need to adapt these lines to the path where you have the .csv files:
- in the first piece of code, you need to replace os.walk('/kaggle/input') by the path where the cs files are located. This code gives you the complete path
- in the second piece of code, where files are read, you need to replace the current path by yours


### Creators

The source of datasets is provided by kaggle.
Their original names are "Boston Airbnb Open Data" and "Seattle Airbnb Open Data"
They can be access through the following links:
- https://www.kaggle.com/datasets/airbnb/boston/data
- https://www.kaggle.com/datasets/airbnb/seattle

## Thanks

Thanks to kaggle:
 - where I could create a jupyter notebook and interact with it saving efforts due to the fact that this utility is integrated in the webpage without need to download more things to local.
 - from where I could search and salect the datasets to work with
Thanks to Udacity, for having a program to start having a look and learning about data science and how to analyse and treat the data.

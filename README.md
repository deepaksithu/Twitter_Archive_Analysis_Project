
# :dog: Twitter Archive Analysis Project -  [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/deepaksithu/Wrangle_and_Analyze_Data_Project/master?filepath=wrangle_act.ipynb)
The Twitter Archive Analysis Project is a project for the wrangle and analyze data section of the Udacity Data Analyst Nanodegree program. In this project several data sets relating to the WeRateDogs Twitter account are gathered, cleaned, and analyzed. 

## Table of Contents
- [Overview](#overview)
- [Requirements](#requirements) 
- [Issues](#issues) 
- [Contact](#contact)

## Overview
In this project the Twitter account WeRateDogs, which posts tweets containing image and text information about a dog, including the dog's name, a rating, and often a stage such as 'doggo' or 'pupper' is analyzed primarily using `matplotlib` and `seaborn` visualizations. The data is initially gathered using the Twitter API through the `tweepy` library and is then cleaned.

## Requirements
This project makes use of the Twitter API, and therefore requires a `consumer_key`, `consumer_secret`, `access_token`, and `access_secret` for data to be gathered. However this is not necessary for running the visualizations in later portions of the project. 

This code depends on the following libraries:
1. `glob`
2. `json`
3. `os`
4. `pandas`
5. `numpy`
6. `requests`
7. `tweepy`
8. `matplotlib.pyplot`
9. `seaborn`

In addition to these, the Jupyter Notebook, `wrangle_act.ipynb` assumes that the data set `twitter-archive-enhanced.csv` has been downloaded, extracted, and saved in the project folder. The files `twitter_archive_master.csv` and `image_predictions_master.csv` are also necessary to be included in the project folder if using the Notebook with the cleaned data sets and not going through the cleaning process itself or using the Twitter API.

The Binder badge above can be used to explore an executable environment for this project. 

## Issues

- organize and clear files in project folder
- include more statistical analysis?
- add features to README
- update and edit README

## Contact
You can get in touch with me on LinkedIn [![LinkedIn Link](https://img.shields.io/badge/Connect-deepaksithu-blue.svg?logo=linkedin&longCache=true&style=social&label=Connect
)](https://www.linkedin.com/in/deepaksithu) <br>
give me that choice follow on Github      ![GitHub followers](https://img.shields.io/github/followers/deepaksithu?style=social)<br>
or email me at deepaksithu@gmail.com.

# Predicting Climate types using Neural Networks and Advanced Digital Image Processsing

![Contributors](https://img.shields.io/github/contributors/Princeu3/ClimateChange_ML?style=plastic)
![Forks](https://img.shields.io/github/forks/Princeu3/ClimateChange_ML)
![Stars](https://img.shields.io/github/stars/Princeu3/ClimateChange_ML)
![Licence](https://img.shields.io/github/license/Princeu3/ClimateChange_ML)
![Issues](https://img.shields.io/github/issues/Princeu3/ClimateChange_ML)


## Introduction:

Hi, Data Scientists. :smiley:

We are working on predicitng different climate types in North American Continent. 

This research has a focus on using supervised and unsupervised learning like **Bayesian CNN** and **Self Organizing Maps** to predict different climate types.<br>

## Background:
 ```Datasets:``` We received 10 years of [Pressure](Pressure_rawdata) and [Wind](Wind_rawdata) data for North American Continent in csv format. 

![](Visualizations/actualmap.gif)

 ```Region of Interests: ``` As the contour lines moves as time goes by, we can see they form areas in a circle that we interested in.

![day148](https://github.com/Princeu3/ClimateChange/assets/97998419/)

 ```Climate types:``` There are four different types of climate types based on the pressure mapping in ROI.

|climate type| Description|
| --- | --- |
|[COL](https://www.weatheronline.co.uk/reports/wxfacts/Cut-off-low.htm#:~:text=The%20cut%2Doff%20low%20is,the%20normal%20track%20of%20depressions.)| a weather system that has become detached or "cut off" from the main jet stream|
|CL| really similar to COL, but a little bit different in how contour lines mapped |
|[COH](https://glossary.ametsoc.org/wiki/Cutoff_high#:~:text=A%20warm%20high%20that%20has,American%20Meteorological%20Society%20(AMS).)| areas of relatively high atmospheric pressure compared to their surroundings|
|NROI| Non Region of Interet |

 ```Goal:``` Try to determine different climate type from pressure and wind maps
 
 ---

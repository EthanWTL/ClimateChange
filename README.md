# Understand Climate Types using Unsupervised Machine Learning
# Introduction:

Hi, Scientists and Geologists. :smiley:

We are working on understanding different climate types in North American Continent. 

This research has a focus on using unsupervised learning like **Kmean** and **Self Organizing Maps** to clustering different climate types.<br>

![Contributors](https://img.shields.io/github/contributors/EthanWTL/ClimateChange?style=plastic)
![Forks](https://img.shields.io/github/forks/EthanWTL/ClimateChange)
![Stars](https://img.shields.io/github/stars/EthanWTL/ClimateChange)
![Licence](https://img.shields.io/github/license/EthanWTL/ClimateChange)
![Issues](https://img.shields.io/github/issues/EthanWTL/ClimateChange)
---

# Background:
We received 10 years of [Pressure](Pressure_rawdata) and [Wind](Wind_rawdata) data for North American Continent in csv format. 

A visualization of the map is as shown below.

![](Visualizations/actualmap.gif)

As the contour lines moves as time goes by, we can see they form circles called **Region of Interests** (**ROI**). 

![day148](https://github.com/EthanWTL/ClimateChange/assets/97998419/f8de6c66-cecb-4125-a1b7-eeb665f779ec)

There are four different types of climate types based on the pressure mapping in ROI.

|climate type| Description|
| --- | --- |
|[COL](https://www.weatheronline.co.uk/reports/wxfacts/Cut-off-low.htm#:~:text=The%20cut%2Doff%20low%20is,the%20normal%20track%20of%20depressions.)| a weather system that has become detached or "cut off" from the main jet stream|
|CL| temp |
|COH| areas of relatively high atmospheric pressure compared to their surroundings|
|NROI| temp |



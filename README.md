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


# Background:
 ```Datasets:``` We received 10 years of [Pressure](Pressure_rawdata) and [Wind](Wind_rawdata) data for North American Continent in csv format. 

![](Visualizations/actualmap.gif)

 ```Region of Interests: ``` As the contour lines moves as time goes by, we can see they form areas in a circle that we interested in.

![day148](https://github.com/EthanWTL/ClimateChange/assets/97998419/f8de6c66-cecb-4125-a1b7-eeb665f779ec)

 ```Climate types:``` There are four different types of climate types based on the pressure mapping in ROI.

|climate type| Description|
| --- | --- |
|[COL](https://www.weatheronline.co.uk/reports/wxfacts/Cut-off-low.htm#:~:text=The%20cut%2Doff%20low%20is,the%20normal%20track%20of%20depressions.)| a weather system that has become detached or "cut off" from the main jet stream|
|CL| really similar to COL, but a little bit different in how contour lines mapped |
|[COH](https://glossary.ametsoc.org/wiki/Cutoff_high#:~:text=A%20warm%20high%20that%20has,American%20Meteorological%20Society%20(AMS).)| areas of relatively high atmospheric pressure compared to their surroundings|
|NROI| Non Region of Interet |

 ```Goal:``` Try to determine different climate type from pressure and wind maps
 
---

# ROI Extraction:
To increase analysis efficiency, we will only focus on **Region Of Interests**.
* Switching csv pressure map into grey scale map.
* Apply [Connected Component](https://www.sciencedirect.com/science/article/pii/S0031320317301693) to seprated out different level of cluster.
* Deploy [Open-CV](https://github.com/opencv/opencv) to detect the circle cluster.
* Consulting with experts in enviornmental field to label the ROI for us.
<img src="https://github.com/EthanWTL/ClimateChange/assets/97998419/11da3fd7-b657-4f51-85e1-a4a43e91a7e8" height="100">
<img src="https://github.com/EthanWTL/ClimateChange/assets/97998419/19c25973-de73-4fb0-9d91-43e923bc9c5a" height="100">
<img src="https://github.com/EthanWTL/ClimateChange/assets/97998419/2b1772de-3b7c-4115-bb92-81437d681fd7" height="100">
<img src="https://github.com/EthanWTL/ClimateChange/assets/97998419/52548b8b-20fb-4feb-9499-9161e93cc090" height="100">

# Data Engineering:





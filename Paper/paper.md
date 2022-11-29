---
Title: Climate Change Prediction with Machine Learning
Date: "November 2022"
Authors: Wooyoung Chung | Mahavir Chandaliya |  Bhavana Gangula | Jiahong Zhan
---

# Abstract
Debate over climate change is contentious, particularly in the US, where many people reject the idea that human activity is causing it. It is critical to understand what causes the warming to better combat it because the consequences are predicted to be severe, including a mass extinction of marine life and frequent extreme weather events. The first challenge in this study is how to build trustworthy statistical models based on the collected climate data from the past 3 years and precisely capture temperature. We evaluated the performance of several widely used machine learning algorithms on our data, including Support Vector Machine, Logistic Regression, Randon Forest and Neural Networks in order to build the model for confirming temperature change and identifying the contributing factors. The result should be assessed using numerals that considers a variety of additional factors, such as the highest and lowest possible temperatures, the highest and lowest pressures at sea level, the humidity, the visibility, the average wind speed, the maximum sustained wind speed, fog, and other variables

# Introduction
With the rise of big data, powerful supercomputers with Graphics Processing Units (GPU), and scientific interest in new methods, the beginning of the 21st century turned out to be an important time in the history of machine learning [1]. However, the last few years, with their huge increases in data volume and computer power, are seen as the golden age of artificial intelligence and machine learning [(https://www.forbes.com/sites/joemckendrick/2019/10/23/artificial-intelligence-enters-its-golden-age/?sh=75d495f0734e](https://www.forbes.com/sites/joemckendrick/2019/10/23/artificial-intelligence-enters-its-golden-age/?sh=75d495f0734e), accessed December 17, 2020).
Many thematic articles [2–4] give detailed reviews of machine learning algorithms, which are the most important type of AI method in atmospheric science. In these books, you can find information about many methods and how they are grouped. Scientists who study the atmosphere found that supervised learning was the most interesting group of techniques. This is because it is the group that has been written about the most in recent papers in the field. If you have some data that has been labeled, you can use it as a training set to build a function that maps inputs to outputs. That function can be used to test the model on a different dataset called "testing one." If the results are good, it can be used in any classification or regression application. Methods like Decision Trees, Random Forest (RF) or XGBoost (XGB), Artificial Neural Networks (ANN), Deep Learning (DL), and Support Vector Machine (SVM) are in this group. On the other hand, in unsupervised learning, algorithms don't have labeled data to train on, so they have to figure out other ways to divide a dataset or reduce the number of dimensions.
The main purpose of this project is to give an overview of machine learning methods and how they are used in climate analysis. We show how machine learning techniques can be used as a new way to solve important and complicated problems in weather forecasting and the study of climate change over different time and space scales.Our team found a climate dataset from 2019 to 2021 for San Jose and from 1991 to 1995 for Madrid. We didn't want to show every part of each problem (for example, there are at least 13 different parts of climate change [(https://vitalflux.com/machine-learning-use-cases-climate-change/](https://vitalflux.com/machine-learning-use-cases-climate-change/), accessed on 17 December 2021), but we did want to show the most important and interesting parts, which we found by reading scientific papers, and show that machine learning can be used successfully in climatology.

# Data
## Data Collection
The datasets were obtained from [tutiempo.net](https://en.tutiempo.net/climate ). We are using two datasets:
1)San Jose weather data containing the weather outcome of everyday from 2019 to 2021[san Jose](https://en.tutiempo.net/climate/ws-724945.html)
2)Madrid weather data containing the weather outcome of everyday from 1991 to 1995[Madrid](https://en.tutiempo.net/climate/download/info/).
The data used will include a variety of additional factors, such as the highest and lowest possible temperatures, the highest and lowest pressures at sea level, the humidity, the visibility, the average wind speed, the maximum sustained wind speed, fog, and other variables.


## Data Preprocessing
The data that were collected over the course of the three years do not correspond with one another. For instance, in a given year there may have been an average temperature and a humidity that corresponded to that, but there may not have been a wind speed that corresponded to that or fog at that time. In order to get the data ready for machine learning, we followed these steps to align the data. This was necessary because the algorithms that power machine learning cannot effectively deal with missing data points.
We performed the following pre-processing steps on the data:
1) Data integration: combined the weather datasets of San Jose and Madrid.
2) Data cleaning: remove missing data.
3) Data reduction: remove unnecessary features.
4) Data transformation: create new features from current ones and convert the unit of temperature.

# Methods
Methods

# Comparisons
Comparisons

# Example Analysis
Example Analysis

# Conclusions
Conclusions

# References
1) Fradkov, A.L. Early History of Machine Learning. IFAC-PapersOnLine 2020, 53, 1385–1390. [http://doi.org/10.1016/j.ifacol.2020.12.1888](http://doi.org/10.1016/j.ifacol.2020.12.1888)
2) Mahesh, B. Machine Learning Algorithms—A Review; International Journal of Science and Research: Raipur, India, 2019. [http://doi.org/10.21275/ART20203995](http://doi.org/10.21275/ART20203995).
3) Dhall, D.; Kaur, R.; Juneja, M. Machine Learning: A Review of the Algorithms and Its Applications. In Lecture Notes in Electrical Engineering, Proceedings of the ICRIC, Jammu, India, 8–9 March 2019; Singh, P.K., Kar, A.K., Singh, Y., Kolekar, M.H., Tanwar, S., Eds.;Springer International Publishing: Cham, Switzerland, 2020; pp. 47–63. [http://doi.org/10.1007/978-3-030-29407-6_5](http://doi.org/10.1007/978-3-030-29407-6_5)
4) Singh, A.; Thakur, N.; Sharma, A. A Review of Supervised Machine Learning Algorithms. In Proceedings of the 2016 3rd International Conference on Computing for Sustainable Global Development (INDIACom), New Delhi, India, 16–18 March 2016;pp. 1310–1315

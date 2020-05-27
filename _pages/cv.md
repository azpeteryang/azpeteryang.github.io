---
layout: archive
title: "Curriculum Vitae"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Education
======
* B.S. in Communication Engineering, UESTC, 2014-2018
* M.S. in Electrical and Computer Engineering, Georgia Institute of Technology, 2019-2020 (expected)

Internship experience
======
* Objection Detection Using Machine Learning Methods           (Zhun Xing Yun Xue Technology)  Jun-Aug 2017
  * Created a graph generator with multiprocessing techniques using OpenCV, generate large-scale datasets of simulated graphs.
  * Used and compared different methods to pre-process the image datasets, observed that converting the image to the frequency domain has a very good effect in improving the accuracy of the detection.
  * Designed a model for object detection using optimized ResNet by Online Hard Example Mining.
  * The optimized model increased 3% accuracy and 3 times faster training speed comparing to the built-in ResNet in PyTorch.

* Book Recommendation Website                                   (Gelan Technology)  Jun-Aug 2016
  * Designed a website which can recommend books to users based on their previous favorites.
  * Divided contents in the websites as slots and utilized Naïve Bayes algorithm to calculate the rating matrix for each website. 
  * Developed a scalable pipeline to process 203GB data using Hadoop and automated the batch processing pipeline
  * Created the frontend of the website using HTML and CSS with Bootstrap Framework.

Projects and research
======
* The Achievement of Water Level Prediction Based on Machine Learning Algorithms 
  * Used Pearson correlation coefficient to design adaptive algorithms, reduce the weight of the data that is less relevant to the current prediction and reduce model complexity.
  * Optimized and Approved the machine learning models (Multivariate Linear Model, Ridge Regression Model, SVM) based on scikit-learn to predict the water level. 
  * Arrived to the result that the optimized Multivariate Linear Model is the best model for the data and reached a very low error rate of 0.022%.
  * Did the data visualization of the water level data prediction. 
                                                                             
* Positioning Software Based on Low Energy Bluetooth
  * Built up a software with Java which can show the position of an object, using RSSI propagation model to calculate the distance between the object and the anchor.
  * Applied Kalman filter on RSSI to improve the algorithm, ignored some measuring of RSSI which are larger than a threshold to let the closest anchors measure the distance.
  * Used MATLAB to simulate the results of the new algorithm, reached high accuracy of positioning.
  
* Analysis STBC-MIMO System Under Rayleigh Channel
  * Conduct research on STBC-MIMO system and Space-time block code, used Simulink to build the system model and did preliminary simulation of the system.
  * Analyzed the bit error rate performance curve of the transmitting antenna under the independent Rayleigh channel, compare with the curve of the single transmitting-receiving antenna under the same conditions.
  * Simulated using two transmitted antennas to transmit in order to get the spatial diversity gain, used one receiving antenna to receive signals.
  * Arrived the result that the bit error rate has been significantly decreased after using space-time block codes. 

* Order Analysis
  * Performed anomaly detection and trend analysis on analyte orders with 40 million records using Fast Fourier transform and rolling bands.
  * Identified analytes with abnormal number of orders, allowing hospitals to examine name trends and potentially reduce redundant tests.
  * Implemented Bhattacharyya distance algorithm on value distribution to search for duplicate analyte with different names in Python.
  * Generated interactive visualization for analyte ordering in analyte name groups with matplotlib, Dash, and Plot.ly visualization tools.  
  
  
* Grouping Web Application
  * Designed a single page web application to normalize analyte names semi-automatically for Duke University Hospital using React.js, MobX, and Bootstrap.  
  * Communicated product design and project progress biweekly with stakeholders in person, incorporating feedback in an agile manner.  
  * Reduced 40% data preparation time for future data science projects at Duke Health by generating 100% accurate analyte groupings.   
  * Built a relational database in MySQL and handled queries through Object Relational Models with Python and SQLAlchemy
  * Created REST APIs to handle database requests and conducted unit test with Python Unittest framework.


Skills
======
* Coding
  * Matlab, Python, C++/C, JavaScript, Pytorch, TensorFlow
* Others 
  * git, Hadoop, OpenCV, MATLAB, Android




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
* M.S. in Electrical and Computer Engineering, Georgia Institute of Technology, 2019- Dec 2020  

Internship experience
======
* Hand-Written Detection Using Machine Learning Methods at Zhun Xing Yun Xue Technology             
  * •	Used and compared different methods to pre-process the image datasets, observed that converting the image to the frequency domain has a very good effect in improving the accuracy of the recognition.
  * Designed a model for hand-written using optimized ResNet with Online Hard Example Mining and Multi-GPU training with parameter server architecture.
  * The optimized model increased 3% accuracy and 3 times faster training speed comparing to the built-in ResNet in PyTorch. 
            
            
* Software Engineer at Gelan Technology                                                                  
  Project: Positioning Software Based on Low Energy Bluetooth   
  * Built up a software with Java which can show the position of an object, using RSSI propagation model to calculate the distance between the object and the anchor.
  * Applied Kalman filter on RSSI to improve the algorithm, ignored some measuring of RSSI which are larger than a threshold to let the closest anchors measure the distance.
  * Used MATLAB to simulate the results of the new algorithm, reached high accuracy of positioning.          



Projects
======     

* User Experience System Based on EEG and VR                         
  * Created a system to analysis the users' emotion reaction to certain virtual environment scene using EEG data analysis.
  * Collected the Visual evoked potential data for EEG analysis.
  * Implemented Logistic Regression to do the EEG real-time data analysis. 
  * Realized ability to store and retrieve data in self-built AWS Cloud database, presented users’ physiological data via curve graph in real time.       
  
  
* Psychological Regulations System                         
  * Completed a decision tree in analysis process, achieved automatic selection of different videos according to users' respective psychological conditions.      
  * Used Arduino to develop a method to send data collected from brainwave and skin conductor sensors.      
  * Realized ability to store and retrieve data in self-built Alibaba Cloud database, presented users' physiological data via curve graph in real time.          


* Microblogs With Translation System                                                                                       
  *	Implemented a micro-blog system with Chinese-English translation, the micro-blog system supports asynchronous post deletion (no need to loading after deleting a blog)  
  *	Used Bootstrap framework for front-end development, supported the change of theme mode, used Spring framework for back-end development. Used Apache’s A/B tool to test the system, achieved an average of 4706 requests per second.    
  *	Developed a neural machine translation system based on neural network architecture, preprocess training data through Tokenization and Normalization.   
  *	Improved translation system performance by 0.76 BLEU score through Fine-tuning, Back translation and Reranking.       


* Book Recommendation System                                                                                       
  *	Realized a book recommendation system based on Apache Flink, collaborated with other members in the team to design the entire system, used React framework to design the Front-end of the System        
  *	The Recommendation System was designed as multiple modules: Recommendation Engine module; Module to store users’ tags and real-time records based on HBase and Web module.         
  *	Implemented two recommendation algorithms: Book similarity scores calculated by cosine similarity and by collaborative filtering, displayed the two algorithms in the Front-end respectively            
  
  
  
  
* Online Image Labelling System                                                                                       
  *	Designed and prototyped an online image labelling and data management platform for the lab to improve image labelling team work efficiency by 30%.             
  *	Built the front end with HTML, CSS and JavaScript with Bootstrap Framework.                      
  *	Achieved functionalities including data management and online labelling for the iterative development by implementing server-side RESTful APIs based on Spring Framework.           
  
  
  
  
* Machine Learning Internship at Future Media Lab (Advisor: Professor Hengtao Sheng)                                                                                     
  *	Owned end-to-end machine learning pipelines to detect fraudulent activities on Remitly’s platform, reducing fraud sideline rate from 3% to 1.5% when compared to rule-based systems, while maintaining industry lead fraud loss rate (LightGBM,Random Forest, XGBoost).                  
  *	Solved the obscurity of model decision imposed on manual review by building model explanation engines using Shapley Additive explanations that explain individual predictions of black-box models. Collaborated with software engineers to deploy the explanation engine in production. Worked with operation team to create standard operation procedures and provide coaching on the explanation UI (SHAP, LIME, KNN).                          
  *	Programmatically generated labels for millions of training data using weak supervision, addressing the bottleneck of lacking ground truth labels (Snorkel).     
  * Reduced the label noise by semi-supervision, achieving 1500bps lift in precision at the same level of recall on holdout set.      
  * Mentored machine learning intern projects and hosted brown-bag sessions to share novel machine learning techniques.      
  * Generates weekly metrics and reports to communicate model performance and progress with business stakeholders.       





* Speech Recognition Using MFCC and LPC                                                                                       
  *	Used dataset which includes 6 alphabets with 3 different speakers to do automatic speech recognition based on MATLAB.     
  *	Extracted MFCC and LPC coefficients from speech signals and used the coefficients as features for a Gaussian Mixtures Model, analyzed the relationship between the number of coefficients and accuracy.                              
  *	Analyzed the test data by mahalanobis distance to the model due to high autocorrelation       


* A Research of Sensor Networks Based on Cellular Automation                                                                     
  *	Optimized cellular automation algorithm and applied it in the sensor networks to save energy for sensor network, applied SDN (Software-Defined Network) for route control.      
  *	Simulated the average energy change of the nodes with MATLAB and found the energy decreased of the nodes slower than that of previous models.      
  * Got the best research project award of the department on this topic.      


  
 

* The Achievement of Water Level Prediction Based on Machine Learning Algorithms 
  * Used Pearson correlation coefficient to design adaptive algorithms, reduce the weight of the data that is less relevant to the current prediction and reduce model complexity.
  * Optimized and Approved the machine learning models (Multivariate Linear Model, Ridge Regression Model, SVM) based on scikit-learn to predict the water level. 
  * Arrived to the result that the optimized Multivariate Linear Model is the best model for the data and reached a very low error rate of 0.022%.
  * Did the data visualization of the water level data prediction.            
      
  
     
     
* Analysis STBC-MIMO System Under Rayleigh Channel
  * Conduct research on STBC-MIMO system and Space-time block code, used Simulink to build the system model and did preliminary simulation of the system.
  * Analyzed the bit error rate performance curve of the transmitting antenna under the independent Rayleigh channel, compare with the curve of the single transmitting-receiving antenna under the same conditions.
  * Simulated using two transmitted antennas to transmit in order to get the spatial diversity gain, used one receiving antenna to receive signals.
  * Arrived the result that the bit error rate has been significantly decreased after using space-time block codes. 
  
  
* 3D Simulation of UAV Based on MPI and OpenGL.     
  * Simulated the motion of UAV and used OpenGL to visualize the scene (including the environment), used MPI (Message Passing Interface) to operate a program in 20 threads and 10 nodes based on Linux.      
  * Messages are passing between the 20 threads, 1 thread is used for describing a 3D scene of the other 19 threads and the environment, the magnitude of UAV’s color is changed based on its location and the color of the environment is also simulated.      

                 




Skills
======
* Coding
  * Matlab, Python, C++/C, JavaScript, Pytorch, TensorFlow
* Others 
  * git, Hadoop, OpenCV, MATLAB, Android




# IEEE Big Data Challenge: Soft Sensing at Scale - Seagate

## Soft sensing problem: 

*Wafer manufacturing is highly complex and takes a long time 

*To improve predictability and product yield, we have added a lot of sensors and measurements in the manufacturing line 

*The sensors and measurements are noisy, expensive and take a long time to manage 

We want to save the time for measurement and get better insights into the predictive value of these sensors for product quality by using deep learning models to predict the measurement results based on the sensing data 

 

## Organizers:  

* Sthitie Bom, Seagate Technology, sthitie.e.bom@seagate.com  

Sthitie Bom heads the global analytics, reporting and controls organizations for the 	Seagate Wafer factories. She is the driving force behind the data and controls system 	strategy in Wafer.  

* Chao Zhang, Seagate Technology, chao.1.zhang@seagate.com  

Chao Zhang is a machine learning engineer. He is working on wafer diagnostics in 		Sthitie’s team with various deep learning models. He is currently pursuing PhD in 		Molecular Engineering at the University of Chicago. 

* Jaswanth Yella, Seagate Technology, jaswanth.k.yella@seagate.com  

Jaswanth Yella is a machine learning engineer at Seagate. He is working on wafer diagnostics in Sthitie’s team focusing on deep neural networks research. He is currently pursuing PhD in Computer Science at the University of Cincinnati. 

* Yu Huang, Seagate Technology, yu.1.huang@seagate.com  

Yu Huang is a machine learning engineer at Seagate. He is working on Wafer diagnostics in Sthitie’s team developing machine-learning-based diagnostic models. He is currently pursuing a Ph.D. Degree in Electrical Engineering at Florida Atlantic University. 

The proposed Data Challenge belongs to the business problem/research problem sector. 

The dataset that will be released will contain the sensor data coming out vacuum tools. The data, upon release, will have been cleared by Seagate legal.  

 

## Cash prizes for the winners: 

* 1st prize - $2000 

* 2nd prize - $1000 

* 3rd prize - $500 

There will also be a swag for all participants. 

 

 

## Challenge Specific Details 
 

* Task and the evaluation metrics 

The task is to use the provided data sets to develop a classification model that works the best. The evaluation metric will be the ROC-AUC of your prediction on the testing set (validation set will be available to you, while testing set not) 

The dataset contains train/val/test splits, each has a 3-dimensional input with axis (sample, time-step, feature) and a 2-dimensional label with axis (sample, measurement). The testing labels will be hidden.  

Note that the train/val/test data are from different time periods of the manufacturing factory, and it’s not guaranteed that the distributions are similar among them. 

 

Participants will need to submit their source code with the prediction values for the testing data, and in backend a score will be calculated based on it, and prizes will be awarded based on the scores. 

 
 

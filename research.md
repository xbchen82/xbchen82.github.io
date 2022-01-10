---
layout: page
title: Research
permalink: /research/
---
### Overview

![Our Mission](/images/research/overview/img1.png)

- Macroscopic traffic big data analytics for imputation and prediction
  ![macroscopic](/images/research/overview/img2.png)
- Multi-sensor fusion cooperative traffic environment perception
- Personalized biomedical signal understanding for driving safety
- Internet of vehicles and mobile edge computing (MEC)
- Signal control and optimization for traffic safety, efficiency and fuel economy

### Traffic data imputation

n actual traffic environment, the data collected by traffic equipment, e.g., loop detectors, are usually not completed where many missing values may occur because of a variety of reasons, such as the failures of loop detectors or transmission network. For example, it was reported that for a dense road network in the city of Melbourne, about 8% of sensor can reach up to 56% missing data. Similarly, about 10% of daily traffic flow in Beijing is missing. Due to the connectivity of road network and the regularity of human travel activity, traffic sensor data collected at different time intervals and different road segments is essentially correlated with each other. Consequently, such a kind of intrinsic correlation between traffic sensor data makes the recovery of missing values feasible and reliable in practice. To address the above mentioned missing sensor data problem, we propose a series of imputation methods based on sparse learning and tensor learning.


**Related studies**  
Xiaobo Chen, Shurong Liang, et al., A Novel Spatiotemporal Data Low-rank Imputation Approach for Traffic Sensor Network (submitted)  
陈小波，梁书荣，柯佳，陈玲，胡煜. 基于图正则化和Schatten-p范数的交通数据缺失值恢复方法, 西南交通大学学报，2022(EI)
陈小波,陈程,陈蕾,韦中杰,蔡英凤,周俊杰  基于改进低秩矩阵补全的交通量数据缺失值插补方法, 交通运输工程学报 19(5):180-190, 2019(EI)  
Xiaobo Chen, Yingfeng Cai, Qiaolin Ye, Lei Chen, Zuoyong Li. Graph Regularized Local Self-Representation for Missing Value Imputation with Applications to On-Road Traffic Sensor Data, Neurocomputing 303: 47-59, 2018 (SCI)   
Xiaobo Chen, Yingfeng Cai, Qingchao Liu, Lei Chen, Nonconvex lp-norm Regularized Sparse Self-Representation for Traffic Sensor Data Recovery, IEEE Access 6: 24279-24290, 2018 (SCI)  
Xiaobo Chen, Xinwen Cai, Jun Liang, Qingchao Liu. Ensemble Learning Multiple LSSVR with Improved Harmony Search Algorithm for Short-term Traffic Flow Forecasting, IEEE Access 6: 9347-9357，2018 (SCI)  
Xiaobo Chen, Cheng Chen, Yingfeng Cai, Hai Wang, Qiaolin Ye. Kernel Sparse Representation with Hybrid Regularization for On-Road Traffic Sensor Data Imputation. Sensors 18(9): 2884, 2018 (SCI)  
Xiaobo Chen. An Improved Self-Representation Approach for Missing Value Imputation, 24th International Conference on Pattern Recognition, 2018 (EI)  
Xiaobo Chen, Zhongjie Wei, Zuoyong Li, Jun Liang, Yingfeng Cai. Ensemble Correlation-based Low-rank Matrix Completion with Application to Traffic Data Imputation, Knowledge-Based Systems, 132 249-262, 2017 (SCI)  

### Traffic flow forecasting

traffic flow forecasting system which predicts the traffic flow at a specific road segment in a certain period of time ahead, plays a fundamental role in various applications, including signal control, traffic guidance, route planning, etc. For example, reliable prediction of future traffic condition will provide valuable information for vehicle navigation and route planning system, thus reducing travel time and improving road utilization. According to the prediction period of time, traffic flow prediction can be categorized into long-term, mid-term, and short-term. For short-term traffic flow forecasting, the period of time is usually in the range of 5-30 minutes. In order to improve the performance of short-term traffic flow forecasting, we develop several effective algorithms based on a variety of machine learning techniques, including support vector machine, feature selection, harmony search, genetic algorithm and ensemble learning.

**Related studies**  
Xiaobo Chen, Xinwen Cai, Jun Liang, Qingchao Liu. Ensemble Learning Multiple LSSVR with Improved Harmony Search Algorithm for Short-term Traffic Flow Forecasting, IEEE Access 6: 9347-9357，2018 (SCI)  
Xiaobo Chen, Zhongjie Wei, Xiang Liu, Yingfeng Cai, Zuoyong Li, Feng Zhao. Spatiotemporal Variable and Parameter Selection Using Sparse Hybrid Genetic Algorithm for Traffic Flow Forecasting, International Journal of Distributed Sensor Networks, 13(6):1-14, 2017 (SCI)  
陈小波, 刘祥, 韦中杰, 梁军, 蔡英凤, 陈龙 基于GA-LSSVR 模型的路网短时交通流预测研究, 交通运输系统工程与信息 17(1):60-66, 2017(EI)  

### Traffic Accident prediction

We focus on a real-world application which predicts whether traffic accident will take place at a specific place based on real-time data as well as the history data. The application of machine learning to improve traffic safety has become an interesting topic recently. Due to the vast deployment of various sensors, such as camera, some import traffic parameters such as volume, speed, etc., can be obtained directly or calculated from video captured by camera. In this application, samples were collected from a road section in Hangzhou city, China from Jun. 11, to Nov. 11 in 2015. A total of 123 accident samples were recorded and accordingly 123 normal samples were selected referring to the time of accident occurrence. Each sample represented by a 24-dimensional vector can be divided into three correlated variable sets: volume, occupancy, and speed, each of which consists of 8 features. These features were obtained from two upstream and two downstream sections closest to the accident location.

**Related studies**  
Xiaobo Chen, Yan Xiao. Geometric Projection Twin Support Vector Machine for Pattern Classification Multimedia Tools and Applications, 80, pages23073–23089, 2021 (SCI)  

### Distributed Cooperative Traffic Perception

In reality, due to the physical mechanism, the on-board sensors of intelligent vehicles always suffer from inherent drawbacks, such as limited perception range or field-of-view (FOV). Moreover, in the crowd scenarios where frequent occlusion occurs, intelligent vehicles fail to detect the target that is occluded, thus, increasing the potential risk of traffic conflicts. To address the above issue, cooperative perception (or collaborative perception) based on inter-vehicle communication has attracted much attention recently. For instance, dedicated short range communication (DSRC) has been introduced as a useful technique which allows vehicles to communicate with other neighboring vehicles through the on-board units (OBUs) installed in the vehicles. When the vehicles communicate successfully, they can exchange their respective local perception results. In fact, inter-vehicle communication (more strictly speaking, the wireless interface) can be viewed as a type of virtual sensor in the sense that a host vehicle can combine its local estimate and a remote message transmitted from other cooperative vehicles to form a more accurate and complete environmental model. Due to the significant distance of inter-vehicle communication and the fusion of information from different viewpoints, cooperative perception not only increases the accuracy and perceptual range beyond line of sight, but also reduces blind spots caused by mutual occlusion, weather, and other external factors.

**Related publications**  
陈小波，陈玲，梁书荣，胡煜. 一种面向重尾非高斯定位噪声的鲁棒协同目标跟踪方法, 浙江大学学报（工学版）,  2021(EI)  
陈小波，陈玲.定位噪声统计特性未知的变分贝叶斯协同目标跟踪, 吉林大学学报（工学版）,  2021(EI)  
Xiaobo Chen, Jianyu Ji, Yanjun Wang. Robust Cooperative Multi-Vehicle Tracking with Inaccurate Self-Localization Based on On-Board Sensors and Inter-Vehicle Communication. Sensors 20(11): 3212, 2020 (SCI)  
Xiaobo Chen, Yanjun Wang, Ling Chen, Jianyu Ji. Multi-Vehicle Cooperative Target Tracking with Time-Varying Localization Uncertainty via Recursive Variational Bayesian Inference. Sensors 20(11): 6487, 2020 (SCI)  

### Vehicle Reidentification

As the number of motor vehicles continues to increase, the need to use computer technology to assist manual traffic management has become very urgent. As an important means to locate, track and monitor vehicles in cities, vehicle re-identification has received extensive attention. Vehicle re-identification means that given one image of the target vehicle in a specific area, we can find the images of the target vehicle captured by other cameras. Vehicle re-identification is a special kind of image retrieval problem, which can only use the appearance information of the vehicle and auxiliary information (such as vehicle number, shooting time and location, etc.). The retrieved image can be inconsistent with the given image due to factors such as viewpoint, shooting time and weather. Due to different camera locations, viewing angles, lighting lighting, resolution, and other factors, different images of the same vehicle may look different and different vehicles may produce similar images due to the same viewpoint and vehicle model, all of which pose a challenge to the vehicle re-identification problem.

**Related studies**  
胡煜, 陈小波（通信作者）,梁军, 陈玲,  梁书荣. 基于车辆组件特征与多注意力融合的车辆重识别方法，计算机研究与发展，2022(EI)  

### Vehicle Trajectory Prediction based on Deep Learning

Due to the rapid development of communication network such as C-V2X and 5G, the high transmission bandwidth and low latency have paved the way for internet of vehicles (IoV) where vehicles can share their local information including but not limited to ego motion state, road environmental data captured by different types of sensors, such as camera, LiDAR, to name a few. Especially, the vehicle trajectory data can be gathered by Mobile Edge Computing (MEC) server where real-time trajectory prediction can be carried out. Accurate prediction of the future trajectory of vehicle in certain traffic scene has been an indispensable task with promising applications, e.g., autonomous driving. For instance, if the future trajectory of surrounding vehicles can be accurately predicted in advance, autonomous vehicles will have sufficient time and information for risk assessment and take appropriate actions. As a result, it will be helpful to avoid potential collision and reduce dangerous incidents.

**Related studies**  
Xiaobo Chen, Huanjia Zhang, et al., Intention-aware Vehicle Trajectory Prediction based on Spatial-temporal Dynamic Attention Network for Internet of Vehicles (submitted)  

### EEG based driving fatigue detection based on Multi-view Learning

Driver fatigue is one of the most influential factors causing traffic accidents. Current studies have revealed that 15%-20% of all fatal traffic accidents are related to driver fatigue while 1,200 deaths and 76,000 injuries were contributed to fatigue-related crashes annually. Electroencephalography (EEG), as a direct manifestation of brain inherent neurophysiological activities in response to particular stimulus, has been widely to detect the driving fatigue due to its high temporal resolution as well as non-invasive acquisition method. Based on the frequency bands, the brain electrical activity rhythms can be classified into delta (0-4Hz), theta (4-8Hz), alpha (8-13Hz) and beta (13-35Hz) waves. Alpha wave frequently occurs during wakefulness, especially in the occipital cortex area of the brain. It was also revealed that the increase of EEG alpha band spindles is related to the fatigue state when subjects drive in the actual monotonous driving environment. Therefore, we attempt to utilize EEG alpha wave to detect driving fatigue.

**Related studies**  
Xiaobo Chen, Yuxiang Gao, et al., Multi-view Classification via Twin Projection Vector Machine with Application to EEG-based Driving Fatigue Detection (submitted)  

### High-order Functional Connectivity Network with Applications

Functional connectivity (FC), defined as the temporal correlation of BOLD signals in different brain regions, can exhibit how structurally segregated and functionally specialized brain regions interact with each other. FC is often modeled as a network using graph theoretic techniques. Differences between normal and disrupted FC networks, in terms of both topological structure and connection strength. Network structure refers to the representation of network vertex and edge while the correlation computation means how to define an appropriate weight for each edge. For network structure in nearly all existing methods, a vertex is always corresponding to a specific brain region, and an edge is used to characterize the FC between brain regions. this method may overlook the complex and dynamic interaction patterns among brain regions, which are essentially time-varying. We propose the novel notions of high-order correlation and high-order FC network, and further develop a simple but effective framework for eMCI classification.

**Related studies**  
Xiaobo Chen, Han Zhang, Lichi Zhang, Celina Shen, Seong-Whan Lee, Dinggang Shen. Extraction of dynamic functional connectivity from brain grey matter and white matter for MCI classification, Human Brain Mapping,38(10): 5019-5034, 2017 (SCI)  
Xiaobo Chen, Han Zhang, Dinggang Shen. Hierarchical High-Order Functional Connectivity Networks and Selective Feature Fusion for MCI Classification, Neuroinformatics 15(3):271-284, 2017 (SCI)  
Xiaobo Chen, Han Zhang, Yu Zhang, Jian Yang, Dinggang Shen. Learning Pairwise Similarity Guided Sparse Functional Connectivity Network for MCI Classification Asian Conference on Pattern Recognition 2017  
Xiaobo Chen, Han Zhang, Yue Gao, Chong-Yaw Wee, Gang Li, Dinggang Shen. High-Order Resting-State Functional Connectivity Network for MCI Classification, Human Brain Mapping,37(9):3282-96, 2016 (SCI)  
Xiaobo Chen, Han Zhang, Dinggang Shen, Ensemble Hierarchical High-Order Functional Connectivity Networks for MCI Classification. MICCAI (2) 2016: 18-25  

### Pattern Recognition and Machine Learning

Support vector machine (SVM), introduced by Vapnik and colleagues, has played an important role in the pattern recognition and machine learning community over the past decades. SVM is based on the structural risk minimization (SRM) principles which strike a balance between the traditional empirical risk and model complexity. This is implemented by maximizing margin between the samples of two classes and simultaneously minimizing the classification errors of training samples. Furthermore, in order to handle nonlinear problems, the input space is first mapped into a much higher dimensional feature space wherein a linear SVM is constructed. This is the so-called kernel trick. Due to the above merits, SVM shows good generalization performance and has been applied to various real-world problems, including text categorization, time series prediction and regression analysis.


### Contact me

[email@domain.com](mailto:email@domain.com)
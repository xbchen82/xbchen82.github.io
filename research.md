---
layout: page
title: Overview
permalink: /research/
---

![Our Mission](/images/research/overview/img1.png#pic_center){: width="400" }  

- **Macroscopic traffic big data analytics for imputation and prediction**
  ![macroscopic](/images/research/overview/img2.png)  
- **Multi-sensor fusion cooperative traffic environment perception**
  ![multi-sensor](/images/research/overview/img3.png)  
- **Personalized biomedical signal understanding for driving safety**
  ![personalized](/images/research/overview/img4.png)  
- **Internet of vehicles and mobile edge computing (MEC)**
  ![Internet](/images/research/overview/img5.png){: width="500" }
- **Signal control and optimization for traffic safety, efficiency and fuel economy**
  ![Internet](/images/research/overview/img6.png){: width="500" }


###     *<font color=Blue>Traffic data imputation</font>*

n actual traffic environment, the data collected by traffic equipment, e.g., loop detectors, are usually not completed where many missing values may occur because of a variety of reasons, such as the failures of loop detectors or transmission network. For example, it was reported that for a dense road network in the city of Melbourne, about 8% of sensor can reach up to 56% missing data. Similarly, about 10% of daily traffic flow in Beijing is missing. Due to the connectivity of road network and the regularity of human travel activity, traffic sensor data collected at different time intervals and different road segments is essentially correlated with each other. Consequently, such a kind of intrinsic correlation between traffic sensor data makes the recovery of missing values feasible and reliable in practice. To address the above mentioned missing sensor data problem, we propose a series of imputation methods based on sparse learning and tensor learning.
  ![imputation](/images/research/traffic-data-imputation/img1.png)
  ![imputation](/images/research/traffic-data-imputation/img2.png)
  ![imputation](/images/research/traffic-data-imputation/img3.png)
  ![imputation](/images/research/traffic-data-imputation/img4.png)

**Related studies**  
- <b>Xiaobo Chen</b>, Shurong Liang, et al., A Novel Spatiotemporal Data Low-rank Imputation Approach for Traffic Sensor Network, <b><i>IEEE Internet of Things Journal</i></b>, 9(20): 20122-20135, 2022 (SCI) 
- <b>Xiaobo Chen</b>, Kaiyuan Wang, et al., A Novel Nonconvex Low-rank Tensor Completion Approach for Traffic Sensor Data Recovery from Incomplete Measurements, <b><i>IEEE Transactions on Instrumentation and Measurement</i></b>, 2023
- <b>陈小波</b>，梁书荣，柯佳，陈玲，胡煜. 基于图正则化和Schatten-p范数的交通数据缺失值恢复方法, <b><i>西南交通大学学报</i></b>，2022(EI)
- <b>陈小波</b>,陈程,陈蕾,韦中杰,蔡英凤,周俊杰  基于改进低秩矩阵补全的交通量数据缺失值插补方法, <b><i>交通运输工程学报</i></b> 19(5):180-190, 2019(EI)  
- <b>Xiaobo Chen</b>, Yingfeng Cai, Qiaolin Ye, Lei Chen, Zuoyong Li. Graph Regularized Local Self-Representation for Missing Value Imputation with Applications to On-Road Traffic Sensor Data, <b><i>Neurocomputing</i></b> 303: 47-59, 2018 (SCI)   
- <b>Xiaobo Chen</b>, Yingfeng Cai, Qingchao Liu, Lei Chen, Nonconvex lp-norm Regularized Sparse Self-Representation for Traffic Sensor Data Recovery, <b><i>IEEE Access</i></b> 6: 24279-24290, 2018 (SCI)  
- <b>Xiaobo Chen</b>, Xinwen Cai, Jun Liang, Qingchao Liu. Ensemble Learning Multiple LSSVR with Improved Harmony Search Algorithm for Short-term Traffic Flow Forecasting, <b><i>IEEE Access</i></b> 6: 9347-9357, 2018 (SCI)  
- <b>Xiaobo Chen</b>, Cheng Chen, Yingfeng Cai, Hai Wang, Qiaolin Ye. Kernel Sparse Representation with Hybrid Regularization for On-Road Traffic Sensor Data Imputation, <b><i>Sensors</i></b> 18(9): 2884, 2018 (SCI)  
- <b>Xiaobo Chen</b>. An Improved Self-Representation Approach for Missing Value Imputation, 24th <b><i>International Conference on Pattern Recognition</i></b>, 2018 (EI)  
- <b>Xiaobo Chen</b>, Zhongjie Wei, Zuoyong Li, Jun Liang, Yingfeng Cai. Ensemble Correlation-based Low-rank Matrix Completion with Application to Traffic Data Imputation, <b><i>Knowledge-Based Systems</i></b>, 132 249-262, 2017 (SCI)  


###   *<font color=Blue>Traffic flow forecasting</font>*

traffic flow forecasting system which predicts the traffic flow at a specific road segment in a certain period of time ahead, plays a fundamental role in various applications, including signal control, traffic guidance, route planning, etc. For example, reliable prediction of future traffic condition will provide valuable information for vehicle navigation and route planning system, thus reducing travel time and improving road utilization. According to the prediction period of time, traffic flow prediction can be categorized into long-term, mid-term, and short-term. For short-term traffic flow forecasting, the period of time is usually in the range of 5-30 minutes. In order to improve the performance of short-term traffic flow forecasting, we develop several effective algorithms based on a variety of machine learning techniques, including support vector machine, feature selection, harmony search, genetic algorithm and ensemble learning.
  ![forecasting](/images/research/traffic-forecasting/img1.png)
  ![forecasting](/images/research/traffic-forecasting/img2.png)

**Related studies**  
- <b>Xiaobo Chen</b>, Xinwen Cai, Jun Liang, Qingchao Liu. <font color=Blue>Ensemble Learning Multiple LSSVR with Improved Harmony Search Algorithm for Short-term Traffic Flow Forecasting</font>, <b>IEEE Access</b> 6: 9347-9357，2018 (SCI)  
- <b>Xiaobo Chen</b>, Zhongjie Wei, Xiang Liu, Yingfeng Cai, Zuoyong Li, Feng Zhao. <font color=Blue>Spatiotemporal Variable and Parameter Selection Using Sparse Hybrid Genetic Algorithm for Traffic Flow Forecasting</font>, <b>International Journal of Distributed Sensor Networks</b>, 13(6):1-14, 2017 (SCI)  
- <b>陈小波</b>, 刘祥, 韦中杰, 梁军, 蔡英凤, 陈龙 <font color=Blue>基于GA-LSSVR 模型的路网短时交通流预测研究</font>, <b>交通运输系统工程与信息</b> 17(1):60-66, 2017(EI)  


###     *<font color=Blue>Traffic Accident prediction</font>*

We focus on a real-world application which predicts whether traffic accident will take place at a specific place based on real-time data as well as the history data. The application of machine learning to improve traffic safety has become an interesting topic recently. Due to the vast deployment of various sensors, such as camera, some import traffic parameters such as volume, speed, etc., can be obtained directly or calculated from video captured by camera. In this application, samples were collected from a road section in Hangzhou city, China from Jun. 11, to Nov. 11 in 2015. A total of 123 accident samples were recorded and accordingly 123 normal samples were selected referring to the time of accident occurrence. Each sample represented by a 24-dimensional vector can be divided into three correlated variable sets: volume, occupancy, and speed, each of which consists of 8 features. These features were obtained from two upstream and two downstream sections closest to the accident location.
  ![accident prediction](/images/research/Traffic-Accident-prediction/img.png)

**Related studies**  
- <b>Xiaobo Chen</b>, Yan Xiao. <font color=Blue>Geometric Projection Twin Support Vector Machine for Pattern Classification</font>, <b>Multimedia Tools and Applications</b>, 80, pages23073–23089, 2021 (SCI)  


###     *<font color=Blue>Distributed Cooperative Traffic Perception</font>*

In reality, due to the physical mechanism, the on-board sensors of intelligent vehicles always suffer from inherent drawbacks, such as limited perception range or field-of-view (FOV). Moreover, in the crowd scenarios where frequent occlusion occurs, intelligent vehicles fail to detect the target that is occluded, thus, increasing the potential risk of traffic conflicts. To address the above issue, cooperative perception (or collaborative perception) based on inter-vehicle communication has attracted much attention recently. For instance, dedicated short range communication (DSRC) has been introduced as a useful technique which allows vehicles to communicate with other neighboring vehicles through the on-board units (OBUs) installed in the vehicles. When the vehicles communicate successfully, they can exchange their respective local perception results. In fact, inter-vehicle communication (more strictly speaking, the wireless interface) can be viewed as a type of virtual sensor in the sense that a host vehicle can combine its local estimate and a remote message transmitted from other cooperative vehicles to form a more accurate and complete environmental model. Due to the significant distance of inter-vehicle communication and the fusion of information from different viewpoints, cooperative perception not only increases the accuracy and perceptual range beyond line of sight, but also reduces blind spots caused by mutual occlusion, weather, and other external factors.

  ![Distributed Cooperative Traffic Perception](/images/research/distributed-cooperative-traffic-perception/img1.png)
  ![Distributed Cooperative Traffic Perception](/images/research/distributed-cooperative-traffic-perception/img2.png)
  ![Distributed Cooperative Traffic Perception](/images/research/distributed-cooperative-traffic-perception/img3.png)
  ![Distributed Cooperative Traffic Perception](/images/research/distributed-cooperative-traffic-perception/img4.png)
  ![Distributed Cooperative Traffic Perception](/images/research/distributed-cooperative-traffic-perception/img5.png)
  ![Distributed Cooperative Traffic Perception](/images/research/distributed-cooperative-traffic-perception/img6.png)
  

**Related studies**  
- <b>陈小波</b>，陈玲，梁书荣，胡煜. <font color=Blue>一种面向重尾非高斯定位噪声的鲁棒协同目标跟踪方法</font>, <b>浙江大学学报(工学版)</b>,  2021(EI)  
- <b>陈小波</b>，陈玲.<font color=Blue>定位噪声统计特性未知的变分贝叶斯协同目标跟踪</font>, <b>吉林大学学报(工学版)</b>,  2021(EI)  
- <b>Xiaobo Chen</b>, Jianyu Ji, Yanjun Wang. <font color=Blue>Robust Cooperative Multi-Vehicle Tracking with Inaccurate Self-Localization Based on On-Board Sensors and Inter-Vehicle Communication.</font> <b>Sensors</b> 20(11): 3212, 2020 (SCI)  
- <b>Xiaobo Chen</b>, Yanjun Wang, Ling Chen, Jianyu Ji. <font color=Blue>Multi-Vehicle Cooperative Target Tracking with Time-Varying Localization Uncertainty via Recursive Variational Bayesian Inference.</font> <b>Sensors</b> 20(11): 6487, 2020 (SCI)  


###     *<font color=Blue>Vehicle Reidentification</font>*

As the number of motor vehicles continues to increase, the need to use computer technology to assist manual traffic management has become very urgent. As an important means to locate, track and monitor vehicles in cities, vehicle re-identification has received extensive attention. Vehicle re-identification means that given one image of the target vehicle in a specific area, we can find the images of the target vehicle captured by other cameras. Vehicle re-identification is a special kind of image retrieval problem, which can only use the appearance information of the vehicle and auxiliary information (such as vehicle number, shooting time and location, etc.). The retrieved image can be inconsistent with the given image due to factors such as viewpoint, shooting time and weather. Due to different camera locations, viewing angles, lighting lighting, resolution, and other factors, different images of the same vehicle may look different and different vehicles may produce similar images due to the same viewpoint and vehicle model, all of which pose a challenge to the vehicle re-identification problem.

  ![Vehicle Reidentification](/images/research/vehicle-reidentification/img1.png)
  ![Vehicle Reidentification](/images/research/vehicle-reidentification/img2.png)
  ![Vehicle Reidentification](/images/research/vehicle-reidentification/img3.png)

**Related studies**  
- 胡煜, <b>陈小波</b>（通信作者）,梁军, 陈玲,  梁书荣. <font color=Blue>基于车辆组件特征与多注意力融合的车辆重识别方法</font>，<b>计算机研究与发展</b>，2022(EI)  


###     *<font color=Blue>Vehicle Trajectory Prediction based on Deep Learning</font>*

Due to the rapid development of communication network such as C-V2X and 5G, the high transmission bandwidth and low latency have paved the way for internet of vehicles (IoV) where vehicles can share their local information including but not limited to ego motion state, road environmental data captured by different types of sensors, such as camera, LiDAR, to name a few. Especially, the vehicle trajectory data can be gathered by Mobile Edge Computing (MEC) server where real-time trajectory prediction can be carried out. Accurate prediction of the future trajectory of vehicle in certain traffic scene has been an indispensable task with promising applications, e.g., autonomous driving. For instance, if the future trajectory of surrounding vehicles can be accurately predicted in advance, autonomous vehicles will have sufficient time and information for risk assessment and take appropriate actions. As a result, it will be helpful to avoid potential collision and reduce dangerous incidents.

  ![Vehicle Trajectory Prediction based on Deep Learning](/images/research/vhicle-trajectory-prediction/img1.png)
  ![Vehicle Trajectory Prediction based on Deep Learning](/images/research/vhicle-trajectory-prediction/img2.png)
  ![Vehicle Trajectory Prediction based on Deep Learning](/images/research/vhicle-trajectory-prediction/img3.png)

**Related studies**  
- <b>Xiaobo Chen</b>, Huanjia Zhang, et al., Intention-aware Vehicle Trajectory Prediction based on Spatial-temporal Dynamic Attention Network for Internet of Vehicles, <b><i>IEEE Transactions on Intelligent Transportation Systems</i></b>,3(10):19471-19483, 2022 (SCI)
- <b>Xiaobo Chen</b>, Huanjia Zhang, et al., Vehicle Trajectory Prediction Based on Intention-Aware Non-Autoregressive Transformer with Multi-Attention Learning for Internet of Vehicles, <b><i>IEEE Transactions on Instrumentation and Measurement</i></b>,71: 2513912, 2022 (SCI)
- Yu Hu,<b>Xiaobo Chen\*</b>, Intention-aware Transformer with Adaptive Social and Temporal Learning for Vehicle Trajectory Prediction, 26th <b><i>International Conference on Pattern Recognition</i></b>, 2022
- <b>Xiaobo Chen</b>, Huanjia Zhang, et al., Stochastic Non-Autoregressive Transformer-based Multimodal Pedestrian Trajectory Prediction for Intelligent Vehicles, <b><i>IEEE xxxx</i></b>, 2022
- <b>Xiaobo Chen</b>, Huanjia Zhang, et al., VNAT: Fast and Accurate Multi-Agent Trajectory Prediction Using Variational Non-Autoregressive Transformer for Intelligent Vehicles, <b><i>IEEE Transactions on Vehicular Technology</i></b>, 2023
- <b>Xiaobo Chen</b>, Yuxiang Gao, et al., Driving Style Feature Extraction and Recognition Based on Hyperdimensional Computing and Semi-Supervised Twin Projection Vector Machine, <b><i>IEEE Transactions on Intelligent Transportation Systems</i></b>, 2023

###     *<font color=Blue>EEG based driving fatigue detection based on Multi-view Learning</font>*

Driver fatigue is one of the most influential factors causing traffic accidents. Current studies have revealed that 15%-20% of all fatal traffic accidents are related to driver fatigue while 1,200 deaths and 76,000 injuries were contributed to fatigue-related crashes annually. Electroencephalography (EEG), as a direct manifestation of brain inherent neurophysiological activities in response to particular stimulus, has been widely to detect the driving fatigue due to its high temporal resolution as well as non-invasive acquisition method. Based on the frequency bands, the brain electrical activity rhythms can be classified into delta (0-4Hz), theta (4-8Hz), alpha (8-13Hz) and beta (13-35Hz) waves. Alpha wave frequently occurs during wakefulness, especially in the occipital cortex area of the brain. It was also revealed that the increase of EEG alpha band spindles is related to the fatigue state when subjects drive in the actual monotonous driving environment. Therefore, we attempt to utilize EEG alpha wave to detect driving fatigue.

**Related studies**  
- <b>Xiaobo Chen</b>, Yuxiang Gao, et al., <font color=Blue>Multi-view Classification via Twin Projection Vector Machine with Application to EEG-based Driving Fatigue Detection</font> (submitted)  


###     *<font color=Blue>High-order Functional Connectivity Network with Applications</font>*


Functional connectivity (FC), defined as the temporal correlation of BOLD signals in different brain regions, can exhibit how structurally segregated and functionally specialized brain regions interact with each other. FC is often modeled as a network using graph theoretic techniques. Differences between normal and disrupted FC networks, in terms of both topological structure and connection strength. Network structure refers to the representation of network vertex and edge while the correlation computation means how to define an appropriate weight for each edge. For network structure in nearly all existing methods, a vertex is always corresponding to a specific brain region, and an edge is used to characterize the FC between brain regions. this method may overlook the complex and dynamic interaction patterns among brain regions, which are essentially time-varying. We propose the novel notions of high-order correlation and high-order FC network, and further develop a simple but effective framework for eMCI classification.

**Related studies**  
- <b>Xiaobo Chen</b>, Han Zhang, Lichi Zhang, Celina Shen, Seong-Whan Lee, Dinggang Shen. <font color=Blue>Extraction of dynamic functional connectivity from brain grey matter and white matter for MCI classification</font>, <b>Human Brain Mapping</b>,38(10): 5019-5034, 2017 (SCI)  
- <b>Xiaobo Chen</b>, Han Zhang, Dinggang Shen. <font color=Blue>Hierarchical High-Order Functional Connectivity Networks and Selective Feature Fusion for MCI Classification</font>, <b>Neuroinformatics</b> 15(3):271-284, 2017 (SCI)  
- <b>Xiaobo Chen</b>, Han Zhang, Yu Zhang, Dinggang Shen. <font color=Blue>Learning Pairwise Similarity Guided Sparse Functional Connectivity Network for MCI Classification</font> <b>Asian Conference on Pattern Recognition</b> 2017  
- <b>Xiaobo Chen</b>, Han Zhang, Yue Gao, Chong-Yaw Wee, Gang Li, Dinggang Shen. <font color=Blue>High-Order Resting-State Functional Connectivity Network for MCI Classification</font>, <b>Human Brain Mapping</b>,37(9):3282-96, 2016 (SCI)  
- <b>Xiaobo Chen</b>, Han Zhang, Dinggang Shen, <font color=Blue>Ensemble Hierarchical High-Order Functional Connectivity Networks for MCI Classification</font>. <b>MICCAI</b> (2) 2016: 18-25  


###    *<font color=Blue>Pattern Recognition and Machine Learning</font>*

Support vector machine (SVM), introduced by Vapnik and colleagues, has played an important role in the pattern recognition and machine learning community over the past decades. SVM is based on the structural risk minimization (SRM) principles which strike a balance between the traditional empirical risk and model complexity. This is implemented by maximizing margin between the samples of two classes and simultaneously minimizing the classification errors of training samples. Furthermore, in order to handle nonlinear problems, the input space is first mapped into a much higher dimensional feature space wherein a linear SVM is constructed. This is the so-called kernel trick. Due to the above merits, SVM shows good generalization performance and has been applied to various real-world problems, including text categorization, time series prediction and regression analysis.

**Related studies**  
- <b>Xiaobo Chen</b>, Jian Yang, Qiaolin Ye, Jun Liang. Recursive Projection Twin Support Vector Machine via Within-Class Variance Minimization, <b><i>Pattern Recognition</i></b>, 44(10-11): 2643-2655, 2011 (SCI)
- <b>Xiaobo Chen</b>, Jian Yang, David Zhang, Jun Liang. Complete Large Margin Linear Discriminant Analysis Using Mathematical Programming Approach, <b><i>Pattern Recognition</i></b>, 46(6):1579-1594, 2013 (SCI)
- <b>Xiaobo Chen</b>, Jian Yang, Jun Liang. Optimal Locality Regularized Least Squares Support Vector Machine via Alternating Optimization, <b><i>Neural Processing Letters</i></b>, 33(3): 301-315, 2011 (SCI)
- <b>Xiaobo Chen</b>, Jian Yang, Jun Liang, Qiaolin Ye. Smooth twin support vector regression, <b><i>Neural Computing and Applications</i></b>, 21(3): 505-513, 2012 (SCI)
- <b>Xiaobo Chen</b>, Jian Yang, Jun Liang. A Flexible Support Vector Machine for Regression, <b><i>Neural Computing and Applications</i></b>, 21(8): 2005-2013, 2012 (SCI) 
- <b>Xiaobo Chen</b>, Jian Yang, Qirong Mao, Fei Han. Regularized Least Squares Fisher Linear Discriminant with Applications to Image Recognition, <b><i>Neurocomputing</i></b>, 122(25):521-534, 2013 (SCI) 
- <b>Xiaobo Chen</b>, Jian Yang, Long Chen. An Improved Robust and Sparse Twin Support Vector Regression via Linear Programming, <b><i>Soft Computing</i></b>, 18(12): 2335-2348, 2014 (SCI) 
- <b>Xiaobo Chen</b>, Yan Xiao, Yinfeng Cai, Long Chen. Structural Max-Margin Discriminant Analysis for Feature Extraction, <b><i>Knowledge-Based Systems</i></b>, 70:154-166, 2014 (SCI)
- <b>Xiaobo Chen</b>, Yingfeng Cai, Long Chen, Zuoyong Li. Discriminant Feature Extraction for Image Recognition Using Complete Robust Maximum Margin Criterion, <b><i>Machine Vision and Applications</i></b>, 26(7): 857-870, 2015 (SCI)
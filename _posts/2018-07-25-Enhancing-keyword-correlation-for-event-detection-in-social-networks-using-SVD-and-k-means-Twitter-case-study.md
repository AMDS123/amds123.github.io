---
layout: post
title: "Enhancing keyword correlation for event detection in social networks using SVD and k-means: Twitter case study"
date: 2018-07-25 12:56:25
categories: arXiv_CL
tags: arXiv_CL Detection Relation
author: Ahmad Hany Hossny, Terry Moschou, Grant Osborne, Lewis Mitchell, Nick Lothian
mathjax: true
---

* content
{:toc}

##### Abstract
Extracting textual features from tweets is a challenging process due to the noisy nature of the content and the weak signal of most of the words used. In this paper, we propose using singular value decomposition (SVD) with clustering to enhance the signals of the textual features in the tweets to improve the correlation with events. The proposed technique applies SVD to the time series vector for each feature to factorize the matrix of feature/day counts, in order to ensure the independence of the feature vectors. Afterwards, the k-means clustering is applied to build a look-up table that maps members of each cluster to the cluster-centroid. The lookup table is used to map each feature in the original data to the centroid of its cluster, then we calculate the sum of the term frequency vectors of all features in each cluster to the term-frequency-vector of the cluster centroid. To test the technique we calculated the correlations of the cluster centroids with the golden standard record (GSR) vector before and after summing the vectors of the cluster members to the centroid-vector. The proposed method is applied to multiple correlation techniques including the Pearson, Spearman, distance correlation and Kendal Tao. The experiments have also considered the different word forms and lengths of the features including keywords, n-grams, skip-grams and bags-of-words. The correlation results are enhanced significantly as the highest correlation scores have increased from 0.3 to 0.6, and the average correlation scores have increased from 0.3 to 0.4.

##### Abstract (translated by Google)
由于内容的嘈杂性和所使用的大多数单词的微弱信号，从推文中提取文本特征是一个具有挑战性的过程。在本文中，我们提出使用奇异值分解（SVD）和聚类来增强推文中文本特征的信号，以改善与事件的相关性。所提出的技术将SVD应用于每个特征的时间序列向量，以对特征/日计数矩阵进行因式分解，以确保特征向量的独立性。然后，应用k-means聚类来构建查找表，该查找表将每个聚类的成员映射到聚类中心。查找表用于将原始数据中的每个特征映射到其集群的质心，然后我们计算每个集群中所有特征的术语频率向量与集群质心的术语 - 频率向量之和。为了测试该技术，我们在将簇成员的矢量与质心矢量相加之前和之后计算了簇质心与黄金标准记录（GSR）矢量的相关性。该方法适用于多种相关技术，包括Pearson，Spearman，距离相关和Kendal Tao。实验还考虑了特征的不同单词形式和长度，包括关键词，n-gram，skip-gram和词袋。随着最高相关分数从0.3增加到0.6，相关结果显着增强，平均相关分数从0.3增加到0.4。

##### URL
[http://arxiv.org/abs/1807.09561](http://arxiv.org/abs/1807.09561)

##### PDF
[http://arxiv.org/pdf/1807.09561](http://arxiv.org/pdf/1807.09561)


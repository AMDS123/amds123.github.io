---
layout: post
title: "Detecting Zones and Threat on 3D Body for Security in Airports using Deep Machine Learning"
date: 2018-02-09 17:14:09
categories: arXiv_CV
tags: arXiv_CV Segmentation Classification Deep_Learning Detection Recognition
author: Abel Ag Rb Guimaraes, Ghassem Tofighi
mathjax: true
---

* content
{:toc}

##### Abstract
In this research, it was used a segmentation and classification method to identify threat recognition in human scanner images of airport security. The Department of Homeland Security's (DHS) in USA has a higher false alarm, produced from theirs algorithms using today's scanners at the airports. To repair this problem they started a new competition at Kaggle site asking the science community to improve their detection with new algorithms. The dataset used in this research comes from DHS at this https URL According to DHS: "This dataset contains a large number of body scans acquired by a new generation of millimeter wave scanner called the High Definition-Advanced Imaging Technology (HD-AIT) system. They are comprised of volunteers wearing different clothing types (from light summer clothes to heavy winter clothes), different body mass indices, different genders, different numbers of threats, and different types of threats". Using Python as a principal language, the preprocessed of the dataset images extracted features from 200 bodies using: intensity, intensity differences and local neighbourhood to detect, to produce segmentation regions and label those regions to be used as a truth in a training and test dataset. The regions are subsequently give to a CNN deep learning classifier to predict 17 classes (that represents the body zones): zone1, zone2, ... zone17 and zones with threat in a total of 34 zones. The analysis showed the results of the classifier an accuracy of 98.2863% and a loss of 0.091319, as well as an average of 100% for recall and precision.

##### Abstract (translated by Google)
在这项研究中，它使用了分割和分类方法来识别人体扫描仪图像中的威胁识别机场安全。美国国土安全部（DHS）有一个更高的误报，由他们的算法使用今天的机场扫描仪产生。为了解决这个问题，他们在Kaggle网站开始了一场新的比赛，要求科学界通过新算法改进他们的检测。根据DHS，本研究中使用的数据集来自DHS。根据DHS：“该数据集包含大量由新一代毫米波扫描仪获取的称为高清 - 高级成像技术（HD-AIT）系统的人体扫描他们由穿着不同服装类型的志愿者组成（从轻便的夏季服装到厚重的冬季服装），不同的体重指数，不同的性别，不同的威胁数量和不同类型的威胁。使用Python作为主要语言，对数据集图像进行预处理，从200个物体中提取特征，使用：强度，强度差异和局部邻域进行检测，以生成分割区域并将这些区域标记为训练和测试数据集中的真值。这些区域随后被赋予CNN深度学习分类器，以预测17个类别（代表身体区域）：区域1，区域2，...区域17以及总共34个区域中具有威胁的区域。分析结果表明，分类器的结果精度为98.2863％，损失为0.091319，平均回收率和精度为100％。

##### URL
[https://arxiv.org/abs/1802.00565](https://arxiv.org/abs/1802.00565)

##### PDF
[https://arxiv.org/pdf/1802.00565](https://arxiv.org/pdf/1802.00565)


---
layout: post
title: "Data Augmentation of Railway Images for Track Inspection"
date: 2018-02-05 07:07:14
categories: arXiv_CV
tags: arXiv_CV Tracking Classification Detection
author: S Ritika, Dattaraj Rao
mathjax: true
---

* content
{:toc}

##### Abstract
Regular maintenance of all the assets is pivotal for proper functioning of railway. Manual maintenance can be very cumbersome and leave room for errors. Track anomalies like vegetation overgrowth, sun kinks affect the track construct and result in unequal load transfer, imbalanced lateral forces on tracks which causes further deterioration of tracks and can ultimately result in derailment of locomotive. Hence there is a need to continuously monitor rail track health. Track anomalies are rare with the skew as high as one anomaly in millions of good images. We propose a method to build training data that will make our algorithms more robust and help us detect real world track issues. The data augmentation will have a direct effect in making us detect better anomalies and hence improve time for railroads that is spent in manual inspection. This paper talks about a real world use case of detecting railway track defects from a camera mounted on a moving locomotive and tracking their locations. The camera is engineered to withstand the environment factors on a moving train and provide a consistent steady image at around 30 frames per second. An image simulation pipeline of track detection, region of interest selection, augmenting image for anomalies is implemented. Training images are simulated for sun kink and vegetation overgrowth. Inception V3 model pretrained on Imagenet dataset is finetuned for a 2 class classification. For the case of vegetation overgrowth, the model generalizes well on actual vegetation images, though it was trained and validated solely on simulated images which might have different distribution than the actual vegetation. Sun kink classifier can classify professionally simulated sun kink videos with a precision of 97.5%.

##### Abstract (translated by Google)
定期维护所有资产是铁路正常运转的关键。手动维护可能非常繁琐，并留下错误的余地。跟踪异常情况，如植被过度生长，太阳扭曲影响轨道结构，导致不平衡的负载转移，不平衡的轨道侧向力，导致轨道进一步恶化，最终可能导致机车脱轨。因此，需要不断监测铁路轨道的健康状况。跟踪异常是罕见的，在数百万的良好图像中的偏差高达一个异常。我们提出了一种方法来建立训练数据，这将使我们的算法更强大，并帮助我们检测真实世界的赛道问题。数据增加将使我们发现更好的异常情况，从而缩短人工检查中花费的铁路时间。本文讨论了一个真实的世界使用案例，检测安装在移动机车上的摄像机的轨道缺陷并跟踪其位置。相机的设计能够承受移动火车上的环境因素，并以每秒30帧的速度提供一致的稳定图像。实现了轨迹检测的图像仿真流水线，感兴趣区域选择，异常增强图像处理。培训图像模拟太阳扭曲和植被过度生长。在Imagenet数据集上训练的Inception V3模型针对2类分类进行了精细调整。对于植被过度生长的情况，该模型在实际植被图像上得到了较好的推广，但是仅仅在模拟图像上进行了训练和验证，可能与实际植被分布不同。太阳扭曲分类器可以以97.5％的精度对专业模拟太阳扭曲视频进行分类。

##### URL
[http://arxiv.org/abs/1802.01286](http://arxiv.org/abs/1802.01286)

##### PDF
[http://arxiv.org/pdf/1802.01286](http://arxiv.org/pdf/1802.01286)


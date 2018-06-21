---
layout: post
title: "Improving Online Multiple Object tracking with Deep Metric Learning"
date: 2018-06-20 07:45:50
categories: arXiv_CV
tags: arXiv_CV Re-identification Object_Detection Tracking Person_Re-identification Embedding CNN Object_Tracking Detection
author: Michael Thoreau, Navinda Kottege
mathjax: true
---

* content
{:toc}

##### Abstract
Tracking by detection is a common approach to solving the Multiple Object Tracking problem. In this paper we show how deep metric learning can be used to improve three aspects of tracking by detection. We train a convolutional neural network to learn an embedding function in a Siamese configuration on a large person re-identification dataset offline. It is then used to improve the online performance of tracking while retaining a high frame rate. We use this learned appearance metric to robustly build estimates of pedestrian's trajectories in the MOT16 dataset. In breaking with the tracking by detection model, we use our appearance metric to propose detections using the predicted state of a tracklet as a prior in the case where the detector fails. This method achieves competitive results in evaluation, especially among online, real-time approaches. We present an ablative study showing the impact of each of the three uses of our deep appearance metric.

##### Abstract (translated by Google)
通过检测进行跟踪是解决多目标跟踪问题的常用方法。在本文中，我们展示了如何使用深度度量学习来改进检测跟踪的三个方面。我们训练一个卷积神经网络，以脱机的方式在大型人员重新识别数据集上学习Siamese配置中的嵌入函数。然后用它来提高跟踪的在线性能，同时保持高帧率。我们使用这个学习外观度量来强有力地建立MOT16数据集中行人轨迹的估计。在通过检测模型打破跟踪时，我们使用我们的外观度量来在检测器失败的情况下使用Tracklet的预测状态作为先验来提出检测。这种方法在评估中取得了有竞争力的结果，特别是在线实时方法。我们提出了一种消融研究，显示了我们深度外观度量的三种用途中的每一种的影响。

##### URL
[http://arxiv.org/abs/1806.07592](http://arxiv.org/abs/1806.07592)

##### PDF
[http://arxiv.org/pdf/1806.07592](http://arxiv.org/pdf/1806.07592)


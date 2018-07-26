---
layout: post
title: "Person re-identification across different datasets with multi-task learning"
date: 2018-07-25 15:27:32
categories: arXiv_CV
tags: arXiv_CV Re-identification Person_Re-identification CNN Classification
author: Matthieu Ospici, Antoine Cecchi
mathjax: true
---

* content
{:toc}

##### Abstract
This paper presents an approach to tackle the re-identification problem. This is a challenging problem due to the large variation of pose, illumination or camera view. More and more datasets are available to train machine learning models for person re-identification. These datasets vary in conditions: cameras numbers, camera positions, location, season, in size, i.e. number of images, number of different identities. Finally in labeling: there are datasets annotated with attributes while others are not. To deal with this variety of datasets we present in this paper an approach to take information from different datasets to build a system which performs well on all of them. Our model is based on a Convolutional Neural Network (CNN) and trained using multitask learning. Several losses are used to extract the different information available in the different datasets. Our main task is learned with a classification loss. To reduce the intra-class variation we experiment with the center loss. Our paper ends with a performance evaluation in which we discuss the influence of the different losses on the global re-identification performance. We show that with our method, we are able to build a system that performs well on different datasets and simultaneously extracts attributes. We also show that our system outperforms recent re-identification works on two datasets.

##### Abstract (translated by Google)
本文介绍了一种解决重新识别问题的方法。由于姿势，照明或摄像机视图的大变化，这是一个具有挑战性的问题。越来越多的数据集可用于训练机器学习模型以进行人员重新识别。这些数据集在条件上有所不同：摄像机编号，摄像机位置，位置，季节，大小，即图像数量，不同身份的数量。最后在标签中：有数据集注释了属性，而其他数据集则没有。为了处理我们在本文中提供的各种数据集，我们提供了一种从不同数据集中获取信息的方法，以构建一个在所有数据集上都表现良好的系统。我们的模型基于卷积神经网络（CNN）并使用多任务学习进行训练。几种损失用于提取不同数据集中可用的不同信息。我们的主要任务是分类损失。为了减少类内变化，我们试验了中心损失。我们的论文以绩效评估结束，其中我们讨论了不同损失对全球再识别绩效的影响。我们展示了使用我们的方法，我们能够构建一个在不同数据集上表现良好并同时提取属性的系统。我们还表明，我们的系统优于最近对两个数据集的重新识别工作。

##### URL
[http://arxiv.org/abs/1807.09666](http://arxiv.org/abs/1807.09666)

##### PDF
[http://arxiv.org/pdf/1807.09666](http://arxiv.org/pdf/1807.09666)


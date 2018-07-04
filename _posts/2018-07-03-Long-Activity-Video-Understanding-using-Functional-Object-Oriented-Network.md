---
layout: post
title: "Long Activity Video Understanding using Functional Object-Oriented Network"
date: 2018-07-03 05:33:44
categories: arXiv_CV
tags: arXiv_CV Video_Caption Knowledge Inference Classification
author: Ahmad Babaeian Jelodar, David Paulius, Yu Sun
mathjax: true
---

* content
{:toc}

##### Abstract
Video understanding is one of the most challenging topics in computer vision. In this paper, a four-stage video understanding pipeline is presented to simultaneously recognize all atomic actions and the single on-going activity in a video. This pipeline uses objects and motions from the video and a graph-based knowledge representation network as prior reference. Two deep networks are trained to identify objects and motions in each video sequence associated with an action. Low Level image features are then used to identify objects of interest in that video sequence. Confidence scores are assigned to objects of interest based on their involvement in the action and to motion classes based on results from a deep neural network that classifies the on-going action in video into motion classes. Confidence scores are computed for each candidate functional unit associated with an action using a knowledge representation network, object confidences, and motion confidences. Each action is therefore associated with a functional unit and the sequence of actions is further evaluated to identify the single on-going activity in the video. The knowledge representation used in the pipeline is called the functional object-oriented network which is a graph-based network useful for encoding knowledge about manipulation tasks. Experiments are performed on a dataset of cooking videos to test the proposed algorithm with action inference and activity classification. Experiments show that using functional object oriented network improves video understanding significantly.

##### Abstract (translated by Google)
视频理解是计算机视觉中最具挑战性的主题之一。在本文中，提出了一个四阶段视频理解管道，以同时识别视频中的所有原子动作和单个正在进行的活动。该管道使用来自视频的对象和运动以及基于图的知识表示网络作为先前参考。训练两个深度网络以识别与动作相关联的每个视频序列中的对象和动作。然后使用低级图像特征来识别该视频序列中感兴趣的对象。基于参与动作的动作类和基于深度神经网络的结果的动作类将置信度分配分配给感兴趣的对象，该神经网络将视频中的正在进行的动作分类为动作类。使用知识表示网络，对象置信度和运动置信度为与动作相关联的每个候选功能单元计算置信度分数。因此，每个动作与功能单元相关联，并且进一步评估动作序列以识别视频中的单个正在进行的活动。管道中使用的知识表示称为功能面向对象网络，它是一种基于图形的网络，可用于编码有关操作任务的知识。在烹饪视频的数据集上执行实验，以通过动作推断和活动分类来测试所提出的算法。实验表明，使用面向功能对象的网络可以显着提高视频理解。

##### URL
[https://arxiv.org/abs/1807.00983](https://arxiv.org/abs/1807.00983)

##### PDF
[https://arxiv.org/pdf/1807.00983](https://arxiv.org/pdf/1807.00983)


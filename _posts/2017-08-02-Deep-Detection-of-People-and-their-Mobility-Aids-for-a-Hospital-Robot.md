---
layout: post
title: "Deep Detection of People and their Mobility Aids for a Hospital Robot"
date: 2017-08-02 09:54:22
categories: arXiv_CV
tags: arXiv_CV Object_Detection CNN Classification Detection
author: Andres Vasquez, Marina Kollmitz, Andreas Eitel, Wolfram Burgard
mathjax: true
---

* content
{:toc}

##### Abstract
Robots operating in populated environments encounter many different types of people, some of whom might have an advanced need for cautious interaction, because of physical impairments or their advanced age. Robots therefore need to recognize such advanced demands to provide appropriate assistance, guidance or other forms of support. In this paper, we propose a depth-based perception pipeline that estimates the position and velocity of people in the environment and categorizes them according to the mobility aids they use: pedestrian, person in wheelchair, person in a wheelchair with a person pushing them, person with crutches and person using a walker. We present a fast region proposal method that feeds a Region-based Convolutional Network (Fast R-CNN). With this, we speed up the object detection process by a factor of seven compared to a dense sliding window approach. We furthermore propose a probabilistic position, velocity and class estimator to smooth the CNN's detections and account for occlusions and misclassifications. In addition, we introduce a new hospital dataset with over 17,000 annotated RGB-D images. Extensive experiments confirm that our pipeline successfully keeps track of people and their mobility aids, even in challenging situations with multiple people from different categories and frequent occlusions. Videos of our experiments and the dataset are available at this http URL

##### Abstract (translated by Google)
在人口密集的环境中操作的机器人遇到了许多不同类型的人，其中一些人由于身体障碍或高龄可能需要谨慎的交互。因此，机器人需要认识到这些先进的要求，提供适当的援助，指导或其他形式的支持。在本文中，我们提出了一个基于深度的感知管道，用于估计环境中的人员的位置和速度，并根据他们所使用的移动辅助工具对他们进行分类：行人，坐轮椅的人，坐轮椅的人，拐杖的人和使用步行者的人。我们提出了一个快速区域提案的方法，饲料基于区域的卷积网络（快速R-CNN）。有了这个，与密集滑动窗口方法相比，我们加快了对象检测过程的七倍。我们还提出了一个概率位置，速度和类别估计器来平滑CNN的检测结果并解决了遮挡和错误分类问题。此外，我们还引入了一个新的医院数据集，超过17,000注释的RGB-D图像。大量的实验证实，即使是在多人分类和频繁闭塞的困难情况下，我们的管道也能成功跟踪人员及其行动辅具。我们的实验和数据集的视频可以在这个http URL中找到

##### URL
[https://arxiv.org/abs/1708.00674](https://arxiv.org/abs/1708.00674)

##### PDF
[https://arxiv.org/pdf/1708.00674](https://arxiv.org/pdf/1708.00674)


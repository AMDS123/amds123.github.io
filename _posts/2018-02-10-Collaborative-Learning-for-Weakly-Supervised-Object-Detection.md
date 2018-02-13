---
layout: post
title: "Collaborative Learning for Weakly Supervised Object Detection"
date: 2018-02-10 06:36:52
categories: arXiv_CV
tags: arXiv_CV Object_Detection Attention Weakly_Supervised Prediction Detection
author: Jiajie Wang, Jiangchao Yao, Ya Zhang, Rui Zhang
mathjax: true
---

* content
{:toc}

##### Abstract
Weakly supervised object detection has recently received much attention, since it only requires image-level labels instead of the bounding-box labels consumed in strongly supervised learning. Nevertheless, the save in labeling expense is usually at the cost of model accuracy. In this paper, we propose a simple but effective weakly supervised collaborative learning framework to resolve this problem, which trains a weakly supervised learner and a strongly supervised learner jointly by enforcing partial feature sharing and prediction consistency. For object detection, taking WSDDN-like architecture as weakly supervised detector sub-network and Faster-RCNN-like architecture as strongly supervised detector sub-network, we propose an end-to-end Weakly Supervised Collaborative Detection Network. As there is no strong supervision available to train the Faster-RCNN-like sub-network, a new prediction consistency loss is defined to enforce consistency of predictions between the two sub-networks as well as within the Faster-RCNN-like sub-networks. At the same time, the two detectors are designed to partially share features to further guarantee the model consistency at perceptual level. Extensive experiments on PASCAL VOC 2007 and 2012 data sets have demonstrated the effectiveness of the proposed framework.

##### Abstract (translated by Google)
弱监督对象检测最近受到了很多关注，因为它只需要图像级标签，而不是强监督学习中消耗的边界框标签。尽管如此，节省标签费用通常是以模型准确度为代价的。在本文中，我们提出了一个简单而有效的弱监督协作学习框架来解决这个问题，它通过加强部分特征共享和预测一致性来联合训练弱监督学习者和强监督学习者。针对目标检测，将类似WSDDN的体系结构作为弱监督探测子网络和Faster-RCNN-like体系结构作为强监督探测子网络，提出了端到端弱监督协作探测网络。由于没有强大的监督来训练类似Faster-RCNN的子网络，因此定义了新的预测一致性损失以强化两个子网络之间以及在类似Faster-RCNN的子网络内的预测的一致性。同时，两个探测器的设计部分共享功能，以进一步保证模型在感​​性水平上的一致性。对PASCAL VOC 2007和2012数据集进行的大量实验证明了该框架的有效性。

##### URL
[http://arxiv.org/abs/1802.03531](http://arxiv.org/abs/1802.03531)

##### PDF
[http://arxiv.org/pdf/1802.03531](http://arxiv.org/pdf/1802.03531)


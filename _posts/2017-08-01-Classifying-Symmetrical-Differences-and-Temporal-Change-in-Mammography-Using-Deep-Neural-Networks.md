---
layout: post
title: "Classifying Symmetrical Differences and Temporal Change in Mammography Using Deep Neural Networks"
date: 2017-08-01 16:11:36
categories: arXiv_CV
tags: arXiv_CV CNN
author: Thijs Kooi, Nico Karssemeijer
mathjax: true
---

* content
{:toc}

##### Abstract
We investigate the addition of symmetry and temporal context information to a deep Convolutional Neural Network (CNN) with the purpose of detecting malignant soft tissue lesions in mammography. We employ a simple linear mapping that takes the location of a mass candidate and maps it to either the contra-lateral or prior mammogram and Regions Of Interest (ROI) are extracted around each location. We subsequently explore two different architectures (1) a fusion model employing two datastreams were both ROIs are fed to the network during training and testing and (2) a stage-wise approach where a single ROI CNN is trained on the primary image and subsequently used as feature extractor for both primary and symmetrical or prior ROIs. A 'shallow' Gradient Boosted Tree (GBT) classifier is then trained on the concatenation of these features and used to classify the joint representation. Results shown a significant increase in performance using the first architecture and symmetry information, but only marginal gains in performance using temporal data and the other setting. We feel results are promising and can greatly be improved when more temporal data becomes available.

##### Abstract (translated by Google)
我们调查对称性和时间背景信息的加入深层卷积神经网络（CNN）的目的是检测恶性软组织病变的乳腺摄影。我们采用一个简单的线性映射，采取大众候选人的位置，并将其映射到对侧或之前的乳房X线照片和感兴趣区（ROI）提取每个位置周围。我们随后探索了两种不同的体系结构（1）采用两个数据流的融合模型是在训练和测试期间将两个ROI馈送到网络;以及（2）逐步地在主要图像上训练单个ROI CNN并随后使用作为主要和对称或既往ROI的特征提取器。然后在这些特征的连接上对“浅”梯度增强树（GBT）分类器进行训练，并用于对联合表示进行分类。结果表明，使用第一种体系结构和对称性信息，性能显着提高，但仅使用时间数据和其他设置的性能的边际收益。我们觉得结果是有希望的，并且可以在更多的时间数据可用时大大改善。

##### URL
[https://arxiv.org/abs/1703.07715](https://arxiv.org/abs/1703.07715)

##### PDF
[https://arxiv.org/pdf/1703.07715](https://arxiv.org/pdf/1703.07715)


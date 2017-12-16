---
layout: post
title: "Deep Self-Taught Learning for Weakly Supervised Object Localization"
date: 2017-04-30 06:23:53
categories: arXiv_CV
tags: arXiv_CV Object_Detection Weakly_Supervised Detection
author: Zequn Jie, Yunchao Wei, Xiaojie Jin, Jiashi Feng, Wei Liu
mathjax: true
---

* content
{:toc}

##### Abstract
Most existing weakly supervised localization (WSL) approaches learn detectors by finding positive bounding boxes based on features learned with image-level supervision. However, those features do not contain spatial location related information and usually provide poor-quality positive samples for training a detector. To overcome this issue, we propose a deep self-taught learning approach, which makes the detector learn the object-level features reliable for acquiring tight positive samples and afterwards re-train itself based on them. Consequently, the detector progressively improves its detection ability and localizes more informative positive samples. To implement such self-taught learning, we propose a seed sample acquisition method via image-to-object transferring and dense subgraph discovery to find reliable positive samples for initializing the detector. An online supportive sample harvesting scheme is further proposed to dynamically select the most confident tight positive samples and train the detector in a mutual boosting way. To prevent the detector from being trapped in poor optima due to overfitting, we propose a new relative improvement of predicted CNN scores for guiding the self-taught learning process. Extensive experiments on PASCAL 2007 and 2012 show that our approach outperforms the state-of-the-arts, strongly validating its effectiveness.

##### Abstract (translated by Google)
大多数现有的弱监督定位（WSL）方法通过基于利用图像级监督学习的特征找到正边界框来学习检测器。然而，这些特征不包含与空间位置有关的信息，并且通常提供劣质的正样本来训练探测器。为了克服这个问题，我们提出了一个深入的自学习的学习方法，使得探测器学习可靠的对象级特征来获取紧密的正样本，然后在此基础上重新训练自己。因此，检测器逐渐提高其检测能力，并定位更多的信息正面样本。为了实现这样的自学习学习，我们提出了一种种子样本采集方法，通过图像到对象的转移和密集的子图发现来找到可靠的正样本来初始化探测器。进一步提出了在线支持样本采集方案，以动态选择最自信的紧密样本，并以相互促进的方式训练检测器。为了防止探测器因过度拟合而陷入最差，我们提出了预测CNN分数的新的相对改进，以指导自学的学习过程。对PASCAL 2007和2012进行的大量实验表明，我们的方法优于现有技术，强有力地验证了它的有效性。

##### URL
[https://arxiv.org/abs/1704.05188](https://arxiv.org/abs/1704.05188)

##### PDF
[https://arxiv.org/pdf/1704.05188](https://arxiv.org/pdf/1704.05188)


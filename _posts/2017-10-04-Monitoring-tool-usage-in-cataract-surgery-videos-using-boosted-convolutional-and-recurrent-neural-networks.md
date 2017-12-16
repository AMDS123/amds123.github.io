---
layout: post
title: "Monitoring tool usage in cataract surgery videos using boosted convolutional and recurrent neural networks"
date: 2017-10-04 11:48:34
categories: arXiv_CV
tags: arXiv_CV CNN RNN Classification Relation
author: Hassan Al Hajj, Mathieu Lamard, Pierre-Henri Conze, Béatrice Cochener, Gwenolé Quellec
mathjax: true
---

* content
{:toc}

##### Abstract
With an estimated 19 million operations performed annually, cataract surgery is the most common surgical procedure. This paper investigates the automatic monitoring of tool usage during a cataract surgery, with potential applications in report generation, surgical training and real-time decision support. In this study, tool usage is monitored in videos recorded through the surgical microscope. Following state-of-the-art video analysis solutions, each frame of the video is analyzed by convolutional neural networks (CNNs) whose outputs are fed to recurrent neural networks (RNNs) in order to take temporal relationships between events into account. Novelty lies in the way those CNNs and RNNs are trained. Computational complexity prevents the end-to-end training of "CNN+RNN" systems. Therefore, CNNs are usually trained first, independently from the RNNs. This approach is clearly suboptimal for surgical tool analysis: many tools are very similar to one another, but they can generally be differentiated based on past events. CNNs should be trained to extract the most useful visual features in combination with the temporal context. A novel boosting strategy is proposed to achieve this goal: the CNN and RNN parts of the system are simultaneously enriched by progressively adding weak classifiers (either CNNs or RNNs) trained to improve the overall classification accuracy. Experiments were performed in a new dataset of 50 cataract surgery videos where the usage of 21 surgical tools was manually annotated. Very good classification performance are achieved in this dataset: tool usage could be labeled with an average area under the ROC curve of $A_z$ = 0.9717 in offline mode (using past, present and future information) and $A_z$ = 0.9696 in online mode (using past and present information only).

##### Abstract (translated by Google)
估计每年进行1900万次手术，白内障手术是最常见的手术过程。本文研究了白内障手术期间工具使用的自动监测，具有报告生成，手术培训和实时决策支持的潜在应用价值。在这项研究中，在通过手术显微镜记录的视频中监测工具的使用。按照最先进的视频分析解决方案，视频的每个帧都被卷积神经网络（CNN）分析，卷积神经网络的输出被馈送到递归神经网络（RNN），以考虑事件之间的时间关系。新奇在于那些CNN和RNN的训练方式。计算复杂性阻碍了“CNN + RNN”系统的端到端培训。因此，CNN通常首先受训，独立于RNN。对于手术工具分析来说，这种方法显然是不理想的：许多工具彼此非常相似，但通常可以根据过去的事件进行区分。应该对CNNs进行培训，结合时间背景提取最有用的视觉特征。为实现这一目标，提出了一种新的增强策略：通过逐步增加弱分类器（CNN或RNN）来增强系统的CNN和RNN部分，从而提高整体分类精度。实验在50个白内障手术视频的新数据集中进行，其中使用21个手术工具被手动注释。在这个数据集中可以获得非常好的分类性能：在离线模式（使用过去，现在和将来的信息）和在线模式下$ A_z $ = 0.9696时，工具使用可以用ROC曲线下的平均面积$ A_z $ = 0.9717进行标记（仅使用过去和现在的信息）。

##### URL
[https://arxiv.org/abs/1710.01559](https://arxiv.org/abs/1710.01559)

##### PDF
[https://arxiv.org/pdf/1710.01559](https://arxiv.org/pdf/1710.01559)


---
layout: post
title: "Monitoring tool usage in surgery videos using boosted convolutional and recurrent neural networks"
date: 2018-05-06 08:21:51
categories: arXiv_CV
tags: arXiv_CV CNN RNN Classification Relation
author: Hassan Al Hajj, Mathieu Lamard, Pierre-Henri Conze, B&#xe9;atrice Cochener, Gwenol&#xe9; Quellec
mathjax: true
---

* content
{:toc}

##### Abstract
This paper investigates the automatic monitoring of tool usage during a surgery, with potential applications in report generation, surgical training and real-time decision support. Two surgeries are considered: cataract surgery, the most common surgical procedure, and cholecystectomy, one of the most common digestive surgeries. Tool usage is monitored in videos recorded either through a microscope (cataract surgery) or an endoscope (cholecystectomy). Following state-of-the-art video analysis solutions, each frame of the video is analyzed by convolutional neural networks (CNNs) whose outputs are fed to recurrent neural networks (RNNs) in order to take temporal relationships between events into account. Novelty lies in the way those CNNs and RNNs are trained. Computational complexity prevents the end-to-end training of "CNN+RNN" systems. Therefore, CNNs are usually trained first, independently from the RNNs. This approach is clearly suboptimal for surgical tool analysis: many tools are very similar to one another, but they can generally be differentiated based on past events. CNNs should be trained to extract the most useful visual features in combination with the temporal context. A novel boosting strategy is proposed to achieve this goal: the CNN and RNN parts of the system are simultaneously enriched by progressively adding weak classifiers (either CNNs or RNNs) trained to improve the overall classification accuracy. Experiments were performed in a dataset of 50 cataract surgery videos and a dataset of 80 cholecystectomy videos. Very good classification performance are achieved in both datasets: tool usage could be labeled with an average area under the ROC curve of $A_z = 0.9961$ and $A_z = 0.9939$, respectively, in offline mode (using past, present and future information), and $A_z = 0.9957$ and $A_z = 0.9936$, respectively, in online mode (using past and present information only).

##### Abstract (translated by Google)
本文调查了手术过程中工具使用的自动监测，并在报告生成，手术培训和实时决策支持方面有潜在的应用。考虑两种手术：最常见的手术过程中的白内障手术和最常见的消化手术之一的胆囊切除术。通过显微镜（白内障手术）或内窥镜（胆囊切除术）记录的视频中监测工具使用情况。按照最先进的视频分析解决方案，视频的每一帧都通过卷积神经网络（CNN）进行分析，卷积神经网络的输出被馈送到递归神经网络（RNN），以考虑事件之间的时间关系。新奇在于那些CNN和RNN的训练方式。计算复杂性阻碍了“CNN + RNN”系统的端到端培训。因此，CNN通常首先受训，独立于RNN。这种方法对于手术工具分析来说显然不是最理想的：许多工具彼此非常相似，但通常可以根据过去的事件进行区分。 CNN应该接受培训，结合时间背景提取最有用的视觉特征。为实现这一目标，提出了一种新的增强策略：通过逐步增加弱分类器（CNN或RNN）来增强系统的CNN和RNN部分，以提高整体分类精度。实验在50个白内障手术视频和80个胆囊切除视频的数据集中进行。在两个数据集中均可获得非常好的分类性能：在离线模式下（使用过去，现在和将来的信息），工具使用可以分别标记为ROC曲线下的平均面积$ A_z = 0.9961 $和$ A_z = 0.9939 $， ，在线模式下分别为$ A_z = 0.9957 $和$ A_z = 0.9936 $（仅使用过去和现在的信息）。

##### URL
[http://arxiv.org/abs/1710.01559](http://arxiv.org/abs/1710.01559)

##### PDF
[http://arxiv.org/pdf/1710.01559](http://arxiv.org/pdf/1710.01559)


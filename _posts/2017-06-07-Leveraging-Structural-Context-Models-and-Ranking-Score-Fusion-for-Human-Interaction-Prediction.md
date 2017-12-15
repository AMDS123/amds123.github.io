---
layout: post
title: "Leveraging Structural Context Models and Ranking Score Fusion for Human Interaction Prediction"
date: 2017-06-07 08:35:49
categories: arXiv_CV
tags: arXiv_CV RNN Prediction
author: Qiuhong Ke, Mohammed Bennamoun, Senjian An, Farid Bossaid, Ferdous Sohel
mathjax: true
---

* content
{:toc}

##### Abstract
Predicting an interaction before it is fully executed is very important in applications such as human-robot interaction and video surveillance. In a two-human interaction scenario, there often contextual dependency structure between the global interaction context of the two humans and the local context of the different body parts of each human. In this paper, we propose to learn the structure of the interaction contexts, and combine it with the spatial and temporal information of a video sequence for a better prediction of the interaction class. The structural models, including the spatial and the temporal models, are learned with Long Short Term Memory (LSTM) networks to capture the dependency of the global and local contexts of each RGB frame and each optical flow image, respectively. LSTM networks are also capable of detecting the key information from the global and local interaction contexts. Moreover, to effectively combine the structural models with the spatial and temporal models for interaction prediction, a ranking score fusion method is also introduced to automatically compute the optimal weight of each model for score fusion. Experimental results on the BIT Interaction and the UT-Interaction datasets clearly demonstrate the benefits of the proposed method.

##### Abstract (translated by Google)
在完全执行之前预测交互在人机交互和视频监控等应用中非常重要。在双人交互的情景中，两个人的全球互动环境与每个人的不同身体部位的本地环境之间经常存在环境依赖关系结构。在本文中，我们建议学习交互语境的结构，并将其与视频序列的时空信息相结合，以更好地预测交互类。利用长时短期记忆（LSTM）网络学习包括空间和时间模型的结构模型，以分别捕获每个RGB帧和每个光流图像的全局和局部上下文的依赖性。 LSTM网络还能够从全球和本地交互情境中检测关键信息。此外，为了有效地将结构模型与交互预测的空间和时间模型相结合，还引入了排名分数融合方法来自动计算每个模型的分数融合的最优权重。 BIT Interaction和UT-Interaction数据集的实验结果清楚地证明了所提出的方法的好处。

##### URL
[https://arxiv.org/abs/1608.05267](https://arxiv.org/abs/1608.05267)

##### PDF
[https://arxiv.org/pdf/1608.05267](https://arxiv.org/pdf/1608.05267)


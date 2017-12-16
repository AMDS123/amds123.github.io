---
layout: post
title: "Action Unit Detection with Region Adaptation, Multi-labeling Learning and Optimal Temporal Fusing"
date: 2017-04-10 21:58:56
categories: arXiv_CV
tags: arXiv_CV Face CNN RNN Deep_Learning Prediction Detection Relation
author: Wei Li, Farnaz Abitahi, Zhigang Zhu
mathjax: true
---

* content
{:toc}

##### Abstract
Action Unit (AU) detection becomes essential for facial analysis. Many proposed approaches face challenging problems in dealing with the alignments of different face regions, in the effective fusion of temporal information, and in training a model for multiple AU labels. To better address these problems, we propose a deep learning framework for AU detection with region of interest (ROI) adaptation, integrated multi-label learning, and optimal LSTM-based temporal fusing. First, ROI cropping nets (ROI Nets) are designed to make sure specifically interested regions of faces are learned independently; each sub-region has a local convolutional neural network (CNN) - an ROI Net, whose convolutional filters will only be trained for the corresponding region. Second, multi-label learning is employed to integrate the outputs of those individual ROI cropping nets, which learns the inter-relationships of various AUs and acquires global features across sub-regions for AU detection. Finally, the optimal selection of multiple LSTM layers to form the best LSTM Net is carried out to best fuse temporal features, in order to make the AU prediction the most accurate. The proposed approach is evaluated on two popular AU detection datasets, BP4D and DISFA, outperforming the state of the art significantly, with an average improvement of around 13% on BP4D and 25% on DISFA, respectively.

##### Abstract (translated by Google)
行动单元（AU）检测对面部分析至关重要。许多提出的方法在处理不同面部区域的对齐，时间信息的有效融合以及训练多个AU标签的模型方面面临挑战性的问题。为了更好地解决这些问题，我们提出了一个利用感兴趣区域（ROI）自适应，综合多标签学习和最优LSTM时间融合的AU检测的深度学习框架。首先，投资回报率网络（ROI Nets）旨在确保具体感兴趣的人脸区域是独立学习的;每个子区域都有一个局部卷积神经网络（CNN） - 一个ROI网络，其卷积滤波器将只针对相应的区域进行训练。其次，多标签学习被用来整合这些单个ROI裁剪网络的输出，这些网络学习了各个AU之间的相互关系，并获得了跨子区域的AU检测的全局特征。最后，为了最好地融合时间特征，对多个LSTM层进行最优选择，形成最好的LSTM网络，以使AU预测最准确。所提出的方法在两个流行的AU检测数据集BP4D和DISFA上进行评估，显着优于现有技术，BP4D和DISFA分别平均提高约13％和25％。

##### URL
[https://arxiv.org/abs/1704.03067](https://arxiv.org/abs/1704.03067)

##### PDF
[https://arxiv.org/pdf/1704.03067](https://arxiv.org/pdf/1704.03067)


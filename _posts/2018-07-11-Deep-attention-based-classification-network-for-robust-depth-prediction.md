---
layout: post
title: "Deep attention-based classification network for robust depth prediction"
date: 2018-07-11 06:19:22
categories: arXiv_CV
tags: arXiv_CV Attention Inference Classification Prediction Recognition
author: Ruibo Li, Ke Xian, Chunhua Shen, Zhiguo Cao, Hao Lu, Lingxiao Hang
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper, we present our deep attention-based classification (DABC) network for robust single image depth prediction, in the context of the Robust Vision Challenge 2018 (ROB 2018). Unlike conventional depth prediction, our goal is to design a model that can perform well in both indoor and outdoor scenes with a single parameter set. However, robust depth prediction suffers from two challenging problems: a) How to extract more discriminative features for different scenes (compared to a single scene)? b) How to handle the large differences of depth ranges between indoor and outdoor datasets? To address these two problems, we first formulate depth prediction as a multi-class classification task and apply a softmax classifier to classify the depth label of each pixel. We then introduce a global pooling layer and a channel-wise attention mechanism to adaptively select the discriminative channels of features and to update the original features by assigning important channels with higher weights. Further, to reduce the influence of quantization errors, we employ a soft-weighted sum inference strategy for the final prediction. Experimental results on both indoor and outdoor datasets demonstrate the effectiveness of our method. It is worth mentioning that we won the 2-nd place in single image depth prediction entry of ROB 2018, in conjunction with IEEE Conference on Computer Vision and Pattern Recognition (CVPR) 2018.

##### Abstract (translated by Google)
在本文中，我们在鲁棒视觉挑战2018（ROB 2018）的背景下，提出了基于注意力的深度分类（DABC）网络，用于稳健的单图像深度预测。与传统的深度预测不同，我们的目标是设计一个能够在单个参数集的室内和室外场景中表现良好的模型。然而，强大的深度预测存在两个具有挑战性的问题：a）如何为不同的场景提取更多的判别特征（与单个场景相比）？ b）如何处理室内和室外数据集之间的深度差异？为了解决这两个问题，我们首先将深度预测表示为多类分类任务，并应用softmax分类器对每个像素的深度标签进行分类。然后，我们引入全局池层和通道注意机制，以自适应地选择特征的辨别通道，并通过分配具有更高权重的重要通道来更新原始特征。此外，为了减少量化误差的影响，我们采用软加权和推理策略进行最终预测。室内和室外数据集的实验结果证明了我们的方法的有效性。值得一提的是，我们在ROB 2018的单一图像深度预测条目中与IEEE计算机视觉和模式识别会议（CVPR）2018一起赢得了第二名。

##### URL
[http://arxiv.org/abs/1807.03959](http://arxiv.org/abs/1807.03959)

##### PDF
[http://arxiv.org/pdf/1807.03959](http://arxiv.org/pdf/1807.03959)


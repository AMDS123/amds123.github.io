---
layout: post
title: "Cross Domain Knowledge Transfer for Person Re-identification"
date: 2016-11-18 10:06:58
categories: arXiv_CV
tags: arXiv_CV Re-identification Knowledge Attention Person_Re-identification CNN RNN Classification Deep_Learning Recognition
author: Qiqi Xiao, Kelei Cao, Haonan Chen, Fangyue Peng, Chi Zhang
mathjax: true
---

* content
{:toc}

##### Abstract
Person Re-Identification (re-id) is a challenging task in computer vision, especially when there are limited training data from multiple camera views. In this paper, we pro- pose a deep learning based person re-identification method by transferring knowledge of mid-level attribute features and high-level classification features. Building on the idea that identity classification, attribute recognition and re- identification share the same mid-level semantic representations, they can be trained sequentially by fine-tuning one based on another. In our framework, we train identity classification and attribute recognition tasks from deep Convolutional Neural Network (dCNN) to learn person information. The information can be transferred to the person re-id task and improves its accuracy by a large margin. Further- more, a Long Short Term Memory(LSTM) based Recurrent Neural Network (RNN) component is extended by a spacial gate. This component is used in the re-id model to pay attention to certain spacial parts in each recurrent unit. Experimental results show that our method achieves 78.3% of rank-1 recognition accuracy on the CUHK03 benchmark.

##### Abstract (translated by Google)
个人重新识别（re-id）是计算机视觉中的一项具有挑战性的任务，特别是当多个摄像机视图的训练数据有限时。本文通过传递中级属性特征和高级分类特征的知识，提出了一种深度学习的人重新识别方法。基于身份分类，属性识别和重新识别共享相同的中级语义表示这一思想，可以通过对基于另一个的微调进行顺序训练。在我们的框架中，我们从深度卷积神经网络（dCNN）训练身份分类和属性识别任务来学习人员信息。这些信息可以传递给人员重新识别任务，并大幅提高其准确性。另外，一个基于长时间短期记忆（LSTM）的递归神经网络（RNN）分量被一个空间门扩展。在re-id模型中使用该组件来关注每个经常性单元中的某些空间部分。实验结果表明，该方法在CUHK03基准测试中达到了一级识别精度的78.3％。

##### URL
[https://arxiv.org/abs/1611.06026](https://arxiv.org/abs/1611.06026)

##### PDF
[https://arxiv.org/pdf/1611.06026](https://arxiv.org/pdf/1611.06026)


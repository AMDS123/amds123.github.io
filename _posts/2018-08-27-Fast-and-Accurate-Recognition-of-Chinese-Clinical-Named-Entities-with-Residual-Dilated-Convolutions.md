---
layout: post
title: "Fast and Accurate Recognition of Chinese Clinical Named Entities with Residual Dilated Convolutions"
date: 2018-08-27 02:42:48
categories: arXiv_CL
tags: arXiv_CL CNN RNN Deep_Learning Recognition
author: Jiahui Qiu, Qi Wang, Yangming Zhou, Tong Ruan, Ju Gao
mathjax: true
---

* content
{:toc}

##### Abstract
Clinical Named Entity Recognition (CNER) aims to identify and classify clinical terms such as diseases, symptoms, treatments, exams, and body parts in electronic health records, which is a fundamental and crucial task for clinical and translation research. In recent years, deep learning methods have achieved significant success in CNER tasks. However, these methods depend greatly on Recurrent Neural Networks (RNNs), which maintain a vector of hidden activations that are propagated through time, thus causing too much time to train models. In this paper, we propose a Residual Dilated Convolutional Neural Network with Conditional Random Field (RD-CNN-CRF) to solve the Chinese CNER. Specifically, Chinese characters and dictionary features are first projected into dense vector representations, then they are fed into the residual dilated convolutional neural network to capture contextual features. Finally, a conditional random field is employed to capture dependencies between neighboring tags. Computational results on the CCKS-2017 Task 2 benchmark dataset show that our proposed RD-CNN-CRF method competes favorably with state-of-the-art RNN-based methods both in terms of computational performance and training time.

##### Abstract (translated by Google)
临床命名实体识别（CNER）旨在识别和分类电子健康记录中的疾病，症状，治疗，检查和身体部位等临床术语，这是临床和翻译研究的基础和关键任务。近年来，深度学习方法在CNER任务中取得了重大成功。然而，这些方法在很大程度上依赖于递归神经网络（RNN），其保持通过时间传播的隐藏激活的向量，因此导致训练模型的时间太长。在本文中，我们提出了一个带有条件随机场的残余扩张卷积神经网络（RD-CNN-CRF）来解决中国的CNER问题。具体而言，首先将汉字和字典特征投影到密集矢量表示中，然后将它们馈入残余扩张卷积神经网络以捕获上下文特征。最后，采用条件随机字段来捕获相邻标签之间的依赖关系。 CCKS-2017任务2基准数据集的计算结果表明，我们提出的RD-CNN-CRF方法在计算性能和训练时间方面都与最先进的基于RNN的方法相媲美。

##### URL
[http://arxiv.org/abs/1808.08669](http://arxiv.org/abs/1808.08669)

##### PDF
[http://arxiv.org/pdf/1808.08669](http://arxiv.org/pdf/1808.08669)


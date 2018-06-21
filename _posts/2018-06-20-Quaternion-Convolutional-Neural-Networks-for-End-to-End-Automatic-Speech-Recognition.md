---
layout: post
title: "Quaternion Convolutional Neural Networks for End-to-End Automatic Speech Recognition"
date: 2018-06-20 15:16:43
categories: arXiv_SD
tags: arXiv_SD Speech_Recognition CNN RNN Classification Recognition
author: Titouan Parcollet, Ying Zhang, Mohamed Morchid, Chiheb Trabelsi, Georges Linar&#xe8;s, Renato De Mori, Yoshua Bengio
mathjax: true
---

* content
{:toc}

##### Abstract
Recently, the connectionist temporal classification (CTC) model coupled with recurrent (RNN) or convolutional neural networks (CNN), made it easier to train speech recognition systems in an end-to-end fashion. However in real-valued models, time frame components such as mel-filter-bank energies and the cepstral coefficients obtained from them, together with their first and second order derivatives, are processed as individual elements, while a natural alternative is to process such components as composed entities. We propose to group such elements in the form of quaternions and to process these quaternions using the established quaternion algebra. Quaternion numbers and quaternion neural networks have shown their efficiency to process multidimensional inputs as entities, to encode internal dependencies, and to solve many tasks with less learning parameters than real-valued models. This paper proposes to integrate multiple feature views in quaternion-valued convolutional neural network (QCNN), to be used for sequence-to-sequence mapping with the CTC model. Promising results are reported using simple QCNNs in phoneme recognition experiments with the TIMIT corpus. More precisely, QCNNs obtain a lower phoneme error rate (PER) with less learning parameters than a competing model based on real-valued CNNs.

##### Abstract (translated by Google)
最近，连接主义时态分类（CTC）模型与递归（RNN）或卷积神经网络（CNN）相结合，使得以端到端的方式训练语音识别系统变得更加容易。然而，在实值模型中，像Mel滤波器组能量和从它们获得的倒谱系数等时间帧分量以及它们的一阶和二阶导数被作为单独的元素处理，而自然的替代方案是处理这些分量作为组成实体。我们建议将这些元素以四元数形式进行分组，并使用已建立的四元数代数来处理这些四元数。四元数和四元数神经网络已经显示出它们有效地将多维输入处理为实体，对内部依赖进行编码，并且用比实值模型更少的学习参数来解决许多任务。本文提出将四元数值卷积神经网络（QCNN）中的多个特征视图进行整合，用于CTC模型的序列到序列映射。使用简单的QCNNs在TIMIT语料库的音素识别实验中报告有希望的结果。更确切地说，与基于实值CNN的竞争模型相比，QCNN获得较低的音素错误率（PER），学习参数较少。

##### URL
[http://arxiv.org/abs/1806.07789](http://arxiv.org/abs/1806.07789)

##### PDF
[http://arxiv.org/pdf/1806.07789](http://arxiv.org/pdf/1806.07789)


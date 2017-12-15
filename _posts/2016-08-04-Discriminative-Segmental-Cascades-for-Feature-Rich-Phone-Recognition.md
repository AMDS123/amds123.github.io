---
layout: post
title: "Discriminative Segmental Cascades for Feature-Rich Phone Recognition"
date: 2016-08-04 02:58:29
categories: arXiv_CL
tags: arXiv_CL Speech_Recognition Language_Model Prediction Recognition
author: Hao Tang, Weiran Wang, Kevin Gimpel, Karen Livescu
mathjax: true
---

* content
{:toc}

##### Abstract
Discriminative segmental models, such as segmental conditional random fields (SCRFs) and segmental structured support vector machines (SSVMs), have had success in speech recognition via both lattice rescoring and first-pass decoding. However, such models suffer from slow decoding, hampering the use of computationally expensive features, such as segment neural networks or other high-order features. A typical solution is to use approximate decoding, either by beam pruning in a single pass or by beam pruning to generate a lattice followed by a second pass. In this work, we study discriminative segmental models trained with a hinge loss (i.e., segmental structured SVMs). We show that beam search is not suitable for learning rescoring models in this approach, though it gives good approximate decoding performance when the model is already well-trained. Instead, we consider an approach inspired by structured prediction cascades, which use max-marginal pruning to generate lattices. We obtain a high-accuracy phonetic recognition system with several expensive feature types: a segment neural network, a second-order language model, and second-order phone boundary features.

##### Abstract (translated by Google)
分段条件随机场（SCRFs）和分段结构支持向量机（SSVMs）等判别分段模型在语音识别中通过格子重新编码和一次解码成功。然而，这样的模型遭受缓慢的解码，妨碍使用计算上昂贵的特征，例如分段神经网络或其他高阶特征。一种典型的解决方案是使用近似解码，或者通过单程中的束修剪或者通过束修剪来生成格子，然后是第二次通过。在这项工作中，我们研究了用铰链损失训练的区分节段模型（即节段结构SVMs）。我们表明，波束搜索不适合在这种方法学习rescoring模型，虽然它提供了良好的近似解码性能，当模型已经训练有素。相反，我们考虑一种由结构化预测级联启发的方法，该方法使用最大边际修剪来生成网格。我们获得了一个高精度的语音识别系统，它具有几个昂贵的特征类型：分段神经网络，二阶语言模型和二阶手机边界特征。

##### URL
[https://arxiv.org/abs/1507.06073](https://arxiv.org/abs/1507.06073)

##### PDF
[https://arxiv.org/pdf/1507.06073](https://arxiv.org/pdf/1507.06073)


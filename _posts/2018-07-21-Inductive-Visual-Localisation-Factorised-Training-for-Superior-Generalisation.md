---
layout: post
title: "Inductive Visual Localisation: Factorised Training for Superior Generalisation"
date: 2018-07-21 17:09:16
categories: arXiv_CV
tags: arXiv_CV Image_Caption Caption RNN Recognition
author: Ankush Gupta, Andrea Vedaldi, Andrew Zisserman
mathjax: true
---

* content
{:toc}

##### Abstract
End-to-end trained Recurrent Neural Networks (RNNs) have been successfully applied to numerous problems that require processing sequences, such as image captioning, machine translation, and text recognition. However, RNNs often struggle to generalise to sequences longer than the ones encountered during training. In this work, we propose to optimise neural networks explicitly for induction. The idea is to first decompose the problem in a sequence of inductive steps and then to explicitly train the RNN to reproduce such steps. Generalisation is achieved as the RNN is not allowed to learn an arbitrary internal state; instead, it is tasked with mimicking the evolution of a valid state. In particular, the state is restricted to a spatial memory map that tracks parts of the input image which have been accounted for in previous steps. The RNN is trained for single inductive steps, where it produces updates to the memory in addition to the desired output. We evaluate our method on two different visual recognition problems involving visual sequences: (1) text spotting, i.e. joint localisation and reading of text in images containing multiple lines (or a block) of text, and (2) sequential counting of objects in aerial images. We show that inductive training of recurrent models enhances their generalisation ability on challenging image datasets.

##### Abstract (translated by Google)
端到端训练的回归神经网络（RNN）已成功应用于需要处理序列的众多问题，例如图像字幕，机器翻译和文本识别。然而，RNN经常难以推广到比训练期间遇到的序列更长的序列。在这项工作中，我们建议明确优化神经网络用于归纳。该想法首先在一系列归纳步骤中分解问题，然后明确地训练RNN以再现这些步骤。由于RNN不允许学习任意内部状态，因此实现了泛化;相反，它的任务是模仿有效状态的演变。特别地，该状态限于空间存储器映射，该空间存储器映射跟踪在先前步骤中已经考虑的输入图像的部分。 RNN针对单个感应步骤进行训练，除了所需的输出之外，它还会对存储器进行更新。我们在涉及视觉序列的两个不同视觉识别问题上评估我们的方法：（1）文本定位，即在包含多行（或块）文本的图像中联合定位和读取文本，以及（2）在天线中对象的顺序计数图片。我们表明，复发模型的归纳训练增强了它们在具有挑战性的图像数据集上的泛化能力。

##### URL
[http://arxiv.org/abs/1807.08179](http://arxiv.org/abs/1807.08179)

##### PDF
[http://arxiv.org/pdf/1807.08179](http://arxiv.org/pdf/1807.08179)


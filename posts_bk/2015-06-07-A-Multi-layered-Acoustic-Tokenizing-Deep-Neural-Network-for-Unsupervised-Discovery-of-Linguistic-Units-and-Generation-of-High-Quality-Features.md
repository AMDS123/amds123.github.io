---
layout: post
title: "A Multi-layered Acoustic Tokenizing Deep Neural Network for Unsupervised Discovery of Linguistic Units and Generation of High Quality Features"
date: 2015-06-07 23:52:54
categories: arXiv_CL
tags: arXiv_CL GAN
author: Cheng-Tao Chung, Cheng-Yu Tsai, Hsiang-Hung Lu, Yuan-ming Liou, Yen-Chen Wu, Yen-Ju Lu, Hung-yi Lee, Lin-shan Lee
mathjax: true
---

* content
{:toc}

##### Abstract
This paper summarizes the work done by the authors for the Zero Resource Speech Challenge organized in the technical program of Interspeech 2015. The goal of the challenge is to discover linguistic units directly from unlabeled speech data. The Multi-layered Acoustic Tokenizer (MAT) proposed in this work automatically discovers multiple sets of acoustic tokens from the given corpus. Each acoustic token set is specified by a set of hyperparameters that describe the model configuration. These sets of acoustic tokens carry different characteristics of the given corpus and the language behind thus can be mutually reinforced. The multiple sets of token labels are then used as the targets of a Multi-target DNN (MDNN) trained on low-level acoustic features. Bottleneck features extracted from the MDNN are used as feedback for the MAT and the MDNN itself. We call this iterative system the Multi-layered Acoustic Tokenizing Deep Neural Network (MAT-DNN) which generates high quality features for track 1 of the challenge and acoustic tokens for track 2 of the challenge.

##### Abstract (translated by Google)
本文总结了作者在Interspeech 2015技术计划中组织的零资源演讲挑战所做的工作。挑战的目标是直接从无标签的语音数据中发现语言单元。本文提出的多层声学标记器（MAT）自动从给定的语料库中发现多组声学标记。每个声学标记集由一组描述模型配置的超参数指定。这些声学标记集具有给定语料库的不同特性，因此可以相互加强语言。然后将多组令牌标签用作在低级声学特征上训练的多目标DNN（MDNN）的目标。从MDNN提取的瓶颈特征被用作MAT和MDNN本身的反馈。我们把这个迭代系统称为多层声学令牌化深度神经网络（MAT-DNN），它为挑战的轨道1和挑战的轨道2产生高质量的特征。

##### URL
[https://arxiv.org/abs/1506.02327](https://arxiv.org/abs/1506.02327)

##### PDF
[https://arxiv.org/pdf/1506.02327](https://arxiv.org/pdf/1506.02327)


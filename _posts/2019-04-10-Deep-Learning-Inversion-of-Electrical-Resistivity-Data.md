---
layout: post
title: "Deep Learning Inversion of Electrical Resistivity Data"
date: 2019-04-10 16:06:29
categories: arXiv_AI
tags: arXiv_AI Face Survey CNN Inference Deep_Learning Quantitative Relation
author: Bin Liu, Qian Guo, Shucai Li, Benchao Liu, Yuxiao Ren, Yonghao Pang, Lanbo Liu, Peng Jiang
mathjax: true
---

* content
{:toc}

##### Abstract
The inverse problem of electrical resistivity surveys (ERS) is difficult because of its nonlinear and ill-posed nature. For this task, traditional linear inversion methods still face challenges such as sub-optimal approximation and initial model selection. Inspired by the remarkable non-linear mapping ability of deep learning approaches, in this paper we propose to build the mapping from apparent resistivity data (input) to resistivity model (output) directly by convolutional neural networks (CNNs). However, the vertically varying characteristic of patterns in the apparent resistivity data may cause ambiguity when using CNNs with the weight sharing and effective receptive field properties. To address the potential issue, we supply an additional tier feature map to CNNs to help it get aware of the relationship between input and output. Based on the prevalent U-Net architecture, we design our network (ERSInvNet) which can be trained end-to-end and reach real-time inference during testing. We further introduce depth weighting function and smooth constraint into loss function to improve inversion accuracy for the deep region and suppress false anomalies. Four groups of experiments are considered to demonstrate the feasibility and efficiency of the proposed methods. According to the comprehensive qualitative analysis and quantitative comparison, ERSInvNet with tier feature map, smooth constraints and depth weighting function together achieve the best performance.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1904.05265](http://arxiv.org/abs/1904.05265)

##### PDF
[http://arxiv.org/pdf/1904.05265](http://arxiv.org/pdf/1904.05265)


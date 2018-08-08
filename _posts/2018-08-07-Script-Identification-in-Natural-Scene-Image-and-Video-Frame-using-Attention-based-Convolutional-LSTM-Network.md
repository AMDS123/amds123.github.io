---
layout: post
title: "Script Identification in Natural Scene Image and Video Frame using Attention based Convolutional-LSTM Network"
date: 2018-08-07 17:37:58
categories: arXiv_CV
tags: arXiv_CV Attention CNN RNN Recognition
author: Ankan Kumar Bhunia, Aishik Konwer, Ayan Kumar Bhunia, Abir Bhowmick, Partha P. Roy, Umapada Pal
mathjax: true
---

* content
{:toc}

##### Abstract
Script identification plays a significant role in analysing documents and videos. In this paper, we focus on the problem of script identification in scene text images and video scripts. Because of low image quality, complex background and similar layout of characters shared by some scripts like Greek, Latin, etc., text recognition in those cases become challenging. In this paper, we propose a novel method that involves extraction of local and global features using CNN-LSTM framework and weighting them dynamically for script identification. First, we convert the images into patches and feed them into a CNN-LSTM framework. Attention-based patch weights are calculated applying softmax layer after LSTM. Next, we do patch-wise multiplication of these weights with corresponding CNN to yield local features. Global features are also extracted from last cell state of LSTM. We employ a fusion technique which dynamically weights the local and global features for an individual patch. Experiments have been done in four public script identification datasets: SIW-13, CVSI2015, ICDAR-17 and MLe2e. The proposed framework achieves superior results in comparison to conventional methods.

##### Abstract (translated by Google)
脚本识别在分析文档和视频中起着重要作用。在本文中，我们关注场景文本图像和视频脚本中的脚本识别问题。由于图像质量低，背景复杂，以及希腊语，拉丁语等一些脚本共享的类似字符布局，在这些情况下的文本识别变得具有挑战性。在本文中，我们提出了一种新方法，该方法涉及使用CNN-LSTM框架提取局部和全局特征，并动态加权以进行脚本识别。首先，我们将图像转换为补丁并将其提供给CNN-LSTM框架。在LSTM之后应用softmax层计算基于注意力的贴片重量。接下来，我们将这些权重与相应的CNN进行补片式乘法，以产生局部特征。全局特征也从LSTM的最后一个单元状态中提取。我们采用融合技术，动态权衡单个补丁的本地和全局特征。已经在四个公共脚本识别数据集中进行了实验：SIW-13，CVSI2015，ICDAR-17和MLe2e。与传统方法相比，所提出的框架实现了优异的结果。

##### URL
[http://arxiv.org/abs/1801.00470](http://arxiv.org/abs/1801.00470)

##### PDF
[http://arxiv.org/pdf/1801.00470](http://arxiv.org/pdf/1801.00470)


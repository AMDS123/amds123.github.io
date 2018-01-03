---
layout: post
title: "Script Identification in Natural Scene Image and Video Frame using Attention based Convolutional-LSTM Network"
date: 2018-01-01 16:42:50
categories: arXiv_CV
tags: arXiv_CV Attention CNN RNN Recognition
author: Ankan Kumar Bhunia, Aishik Konwer, Abir Bhowmick, Ayan Kumar Bhunia, Partha P. Roy, Umapada Pal
mathjax: true
---

* content
{:toc}

##### Abstract
Script identification facilitates many important applications in document/video analysis. This paper focuses on the problem of script identification in scene text images and video scripts. Because of low image quality, complex background and similar layout of characters shared by some scripts like Greek, Latin, etc., text recognition in such scenario is difficult. Most of the recent approaches usually apply a patch-based CNN network with summation of obtained features, or only a CNN-LSTM network to get the identification result. Some use a discriminative CNN to jointly optimize mid-level representations and deep features. In this paper, we propose a novel method that involves extraction of local and global features using CNN-LSTM framework and weighting them dynamically for script identification. First we convert the images into patches and feed them into a CNN-LSTM framework. Attention-based patch weights are calculated applying softmax layer after LSTM. Then we do patch-wise multiplication of these weights with corresponding CNN to yield local features. Global features are also extracted from last cell state of LSTM. We employ a fusion technique which dynamically weights the local and global features for an individual patch. Experiments have been done in two public script identification datasets, SIW-13 and CVSI2015. Our learning procedure achieves superior performance compared with previous approaches.

##### Abstract (translated by Google)
脚本识别有助于文档/视频分析中的许多重要应用。本文重点研究了场景文本图像和视频脚本中的脚本识别问题。由于图像质量较低，背景复杂，希腊，拉丁等文字共享的字符布局相似，这种情况下的文本识别是困难的。大多数近期的方法通常应用基于补丁的CNN网络和所获得的特征的总和，或者仅使用CNN-LSTM网络来获得识别结果。有的使用判别式CNN来共同优化中间层次的表示和深层特征。在本文中，我们提出了一种新的方法，它涉及到使用CNN-LSTM框架提取本地和全局特征，并对它们进行动态加权以用于脚本识别。首先，我们将图像转换为补丁，并将它们输入到CNN-LSTM框架中。在LSTM之后应用softmax层来计算基于注意力的贴片权重。然后，我们将这些权重与相应的CNN进行补丁相乘来产生局部特征。全局特征也从LSTM的最后一个单元状态中提取。我们采用一种融合技术，为单个补丁动态调整局部和全局特征。已经在两个公共脚本识别数据集SIW-13和CVSI2015中进行实验。与以前的方法相比，我们的学习过程实现了卓越的性能

##### URL
[http://arxiv.org/abs/1801.00470](http://arxiv.org/abs/1801.00470)

##### PDF
[http://arxiv.org/pdf/1801.00470](http://arxiv.org/pdf/1801.00470)


---
layout: post
title: "A Cascade of 2.5D CNN and LSTM Network for Mitotic Cell Detection in 4D Microscopy Image"
date: 2018-06-04 09:05:24
categories: arXiv_CV
tags: arXiv_CV CNN RNN Detection
author: Titinunt Kitrungrotsakul, Xian-Hau Han, Yutaro Iwamoto, Satoko Takemoto, Hideo Yokota, Sari Ipponjima, Tomomi Nemoto, Xiong Wei, Yen-Wei Chen
mathjax: true
---

* content
{:toc}

##### Abstract
In recent years, intravital skin imaging has been used in mammalian skin research for the investigation of cell behaviors. The mitotic cell (cell division) detection is a fundamental step of the investigation. Due to the complex backgrounds (normal cells), most of the existing methods bring a lot of false positives. In this paper, we proposed a 2.5 dimensional (2.5D) cascaded end-to-end network (CasDetNet_LSTM) for accurate automatic mitotic cell detection in 4D microscopic images with fewer training data. The CasDetNet_LSTM consists of two 2.5D networks. The first one is a 2.5D fast region-based convolutional neural network (2.5D Fast R-CNN), which is used for the detection of candidate cells with only volume information and the second one is a long short-term memory (LSTM) network embedded with temporal information, which is used for reduction of false positive and retrieving back those mitotic cells that missed in the first step. The experimental results shown that our CasDetNet_LSTM can achieve higher precision and recall comparing to other state-of-the-art methods.

##### Abstract (translated by Google)
近年来，活体皮肤成像已被用于哺乳动物皮肤研究以调查细胞行为。有丝分裂细胞（细胞分裂）检测是调查的基本步骤。由于复杂的背景（正常细胞），现有的大多数方法都会带来很多误报。在本文中，我们提出了一个2.5维（2.5D）级联端到端网络（CasDetNet_LSTM），用于在具有较少训练数据的4D显微图像中进行精确的自动有丝分裂细胞检测。 CasDetNet_LSTM由两个2.5D网络组成。第一种是2.5D快速区域卷积神经网络（2.5D Fast R-CNN），用于检测只有体积信息的候选细胞，第二种是长时间短期记忆（LSTM）网络嵌入了时间信息，用于减少假阳性和恢复在第一步错过的有丝分裂细胞。实验结果表明，我们的CasDetNet_LSTM与其他最先进的方法相比，可以实现更高的精度和召回率。

##### URL
[http://arxiv.org/abs/1806.01018](http://arxiv.org/abs/1806.01018)

##### PDF
[http://arxiv.org/pdf/1806.01018](http://arxiv.org/pdf/1806.01018)


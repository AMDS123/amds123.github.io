---
layout: post
title: "Word Recognition with Deep Conditional Random Fields"
date: 2016-12-04 05:39:42
categories: arXiv_CV
tags: arXiv_CV Attention Classification Deep_Learning Relation Recognition
author: Gang Chen, Yawei Li, Sargur N. Srihari
mathjax: true
---

* content
{:toc}

##### Abstract
Recognition of handwritten words continues to be an important problem in document analysis and recognition. Existing approaches extract hand-engineered features from word images--which can perform poorly with new data sets. Recently, deep learning has attracted great attention because of the ability to learn features from raw data. Moreover they have yielded state-of-the-art results in classification tasks including character recognition and scene recognition. On the other hand, word recognition is a sequential problem where we need to model the correlation between characters. In this paper, we propose using deep Conditional Random Fields (deep CRFs) for word recognition. Basically, we combine CRFs with deep learning, in which deep features are learned and sequences are labeled in a unified framework. We pre-train the deep structure with stacked restricted Boltzmann machines (RBMs) for feature learning and optimize the entire network with an online learning algorithm. The proposed model was evaluated on two datasets, and seen to perform significantly better than competitive baseline models. The source code is available at this https URL

##### Abstract (translated by Google)
手写单词的识别仍然是文件分析和识别中的一个重要问题。现有的方法从单词图像中提取手工设计的特征 - 新的数据集可能表现不佳。最近，由于从原始数据学习功能的能力，深度学习引起了很大的关注。此外，他们已经在包括字符识别和场景识别在内的分类任务中取得了最新的成果。另一方面，单词识别是一个序列问题，我们需要模拟字符之间的相关性。在本文中，我们提出使用深度条件随机场（深CRF）进行单词识别。基本上，我们把CRF和深度学习结合起来，把深刻的特征学习，把序列标注在一个统一的框架中。我们利用叠加的限制玻尔兹曼机（RBM）对特征学习的深层结构进行预训练，并利用在线学习算法对整个网络进行优化。所提出的模型在两个数据集上进行评估，并且看起来比竞争基线模型显着更好。源代码可在此https URL中获得

##### URL
[https://arxiv.org/abs/1612.01072](https://arxiv.org/abs/1612.01072)

##### PDF
[https://arxiv.org/pdf/1612.01072](https://arxiv.org/pdf/1612.01072)


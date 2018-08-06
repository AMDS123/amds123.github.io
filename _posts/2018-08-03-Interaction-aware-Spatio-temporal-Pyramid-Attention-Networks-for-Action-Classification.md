---
layout: post
title: "Interaction-aware Spatio-temporal Pyramid Attention Networks for Action Classification"
date: 2018-08-03 07:44:25
categories: arXiv_CV
tags: arXiv_CV Attention Classification Relation
author: Yang Du, Chunfeng Yuan, Bing Li, Lili Zhao, Yangxi Li, Weiming Hu
mathjax: true
---

* content
{:toc}

##### Abstract
Local features at neighboring spatial positions in feature maps have high correlation since their receptive fields are often overlapped. Self-attention usually uses the weighted sum (or other functions) with internal elements of each local feature to obtain its weight score, which ignores interactions among local features. To address this, we propose an effective interaction-aware self-attention model inspired by PCA to learn attention maps. Furthermore, since different layers in a deep network capture feature maps of different scales, we use these feature maps to construct a spatial pyramid and then utilize multi-scale information to obtain more accurate attention scores, which are used to weight the local features in all spatial positions of feature maps to calculate attention maps. Moreover, our spatial pyramid attention is unrestricted to the number of its input feature maps so it is easily extended to a spatio-temporal version. Finally, our model is embedded in general CNNs to form end-to-end attention networks for action classification. Experimental results show that our method achieves the state-of-the-art results on the UCF101, HMDB51 and untrimmed Charades.

##### Abstract (translated by Google)
特征图中相邻空间位置处的局部特征具有高相关性，因为它们的感知场经常重叠。自我关注通常使用加权和（或其他函数）与每个局部特征的内部元素来获得其权重分数，这忽略了局部特征之间的相互作用。为了解决这个问题，我们提出了一个有效的交互感知自我关注模型，它受到PCA的启发，可以学习注意力图。此外，由于深层网络中的不同层捕获不同尺度的特征图，我们使用这些特征图构建空间金字塔，然后利用多尺度信息获得更准确的注意力分数，用于对所有局部特征进行加权。特征图的空间位置以计算注意力图。此外，我们的空间金字塔注意力不受其输入要素图数量的限制，因此可以轻松扩展到时空版本。最后，我们的模型嵌入在一般的CNN中，以形成用于行动分类的端到端关注网络。实验结果表明，我们的方法在UCF101，HMDB51和未修剪的Charades上实现了最先进的结果。

##### URL
[http://arxiv.org/abs/1808.01106](http://arxiv.org/abs/1808.01106)

##### PDF
[http://arxiv.org/pdf/1808.01106](http://arxiv.org/pdf/1808.01106)


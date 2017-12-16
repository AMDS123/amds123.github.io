---
layout: post
title: "Manifold Regularized Slow Feature Analysis for Dynamic Texture Recognition"
date: 2017-06-09 16:06:25
categories: arXiv_CV
tags: arXiv_CV Classification Relation Recognition
author: Jie Miao, Xiangmin Xu, Xiaofen Xing, Dacheng Tao
mathjax: true
---

* content
{:toc}

##### Abstract
Dynamic textures exist in various forms, e.g., fire, smoke, and traffic jams, but recognizing dynamic texture is challenging due to the complex temporal variations. In this paper, we present a novel approach stemmed from slow feature analysis (SFA) for dynamic texture recognition. SFA extracts slowly varying features from fast varying signals. Fortunately, SFA is capable to leach invariant representations from dynamic textures. However, complex temporal variations require high-level semantic representations to fully achieve temporal slowness, and thus it is impractical to learn a high-level representation from dynamic textures directly by SFA. In order to learn a robust low-level feature to resolve the complexity of dynamic textures, we propose manifold regularized SFA (MR-SFA) by exploring the neighbor relationship of the initial state of each temporal transition and retaining the locality of their variations. Therefore, the learned features are not only slowly varying, but also partly predictable. MR-SFA for dynamic texture recognition is proposed in the following steps: 1) learning feature extraction functions as convolution filters by MR-SFA, 2) extracting local features by convolution and pooling, and 3) employing Fisher vectors to form a video-level representation for classification. Experimental results on dynamic texture and dynamic scene recognition datasets validate the effectiveness of the proposed approach.

##### Abstract (translated by Google)
动态纹理以各种形式存在，例如火灾，烟雾和交通堵塞，但由于复杂的时间变化，识别动态纹理是具有挑战性的。在本文中，我们提出了一种新的方法源于动态纹理识别的慢特征分析（SFA）。 SFA从快速变化的信号中提取缓慢变化的特征。幸运的是，SFA能够从动态纹理中滤除不变的表示。然而，复杂的时间变化需要高层次的语义表示来充分实现时间缓慢，因此从SFA直接学习动态纹理的高级表示是不切实际的。为了解决动态纹理复杂性的鲁棒性低级特征，我们通过探索每个时间过渡的初始状态的相邻关系并保留其变化的局部性来提出流形正则化的SFA（MR-SFA）。因此，学习的特征不仅是缓慢变化的，而且也是部分可预测的。 1）利用MR-SFA学习特征提取函数作为卷积滤波器，2）通过卷积和合并提取局部特征，3）采用Fisher向量形成视频级代表分类。动态纹理和动态场景识别数据集的实验结果验证了所提出方法的有效性。

##### URL
[https://arxiv.org/abs/1706.03015](https://arxiv.org/abs/1706.03015)

##### PDF
[https://arxiv.org/pdf/1706.03015](https://arxiv.org/pdf/1706.03015)


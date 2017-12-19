---
layout: post
title: "Modality-dependent Cross-media Retrieval"
date: 2015-06-23 01:34:01
categories: arXiv_CV
tags: arXiv_CV CNN Relation
author: Yunchao Wei, Yao Zhao, Zhenfeng Zhu, Shikui Wei, Yanhui Xiao, Jiashi Feng, Shuicheng Yan
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper, we investigate the cross-media retrieval between images and text, i.e., using image to search text (I2T) and using text to search images (T2I). Existing cross-media retrieval methods usually learn one couple of projections, by which the original features of images and text can be projected into a common latent space to measure the content similarity. However, using the same projections for the two different retrieval tasks (I2T and T2I) may lead to a tradeoff between their respective performances, rather than their best performances. Different from previous works, we propose a modality-dependent cross-media retrieval (MDCR) model, where two couples of projections are learned for different cross-media retrieval tasks instead of one couple of projections. Specifically, by jointly optimizing the correlation between images and text and the linear regression from one modal space (image or text) to the semantic space, two couples of mappings are learned to project images and text from their original feature spaces into two common latent subspaces (one for I2T and the other for T2I). Extensive experiments show the superiority of the proposed MDCR compared with other methods. In particular, based the 4,096 dimensional convolutional neural network (CNN) visual feature and 100 dimensional LDA textual feature, the mAP of the proposed method achieves 41.5\%, which is a new state-of-the-art performance on the Wikipedia dataset.

##### Abstract (translated by Google)
在本文中，我们研究了图像和文本之间的跨媒体检索，即使用图像来搜索文本（I2T）并使用文本来搜索图像（T2I）。现有的跨媒体检索方法通常会学习一对投影，通过这些投影可以将图像和文本的原始特征投影到一个共同的潜在空间中来测量内容的相似度。然而，对两种不同的检索任务（I2T和T2I）使用相同的投影可能导致它们各自的性能之间的折衷，而不是它们的最佳性能。不同于以前的作品，我们提出了一种模态依赖的跨媒体检索（MDCR）模型，其中针对不同的跨媒体检索任务学习两对投影而不是一对投影。具体来说，通过联合优化图像和文本之间的相关性以及从一个模态空间（图像或文本）到语义空间的线性回归，学习两对映射以将图像和文本从其原始特征空间投影到两个常见的潜在子空间（一个用于I2T，另一个用于T2I）。大量的实验表明，与其他方法相比，所提出的MDCR的优越性。特别是基于4096维卷积神经网络（CNN）视觉特征和100维LDA文本特征，该方法的mAP达到了41.5％，这是维基百科数据集上的一种新的性能表现。

##### URL
[https://arxiv.org/abs/1506.06628](https://arxiv.org/abs/1506.06628)

##### PDF
[https://arxiv.org/pdf/1506.06628](https://arxiv.org/pdf/1506.06628)


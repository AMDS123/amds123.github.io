---
layout: post
title: "Discriminative Block-Diagonal Representation Learning for Image Recognition"
date: 2017-07-12 05:33:57
categories: arXiv_CV
tags: arXiv_CV Regularization Attention GAN Face Represenation_Learning Optimization Prediction Relation Recognition
author: Zheng Zhang, Yong Xu, Ling Shao, Jian Yang
mathjax: true
---

* content
{:toc}

##### Abstract
Existing block-diagonal representation researches mainly focuses on casting block-diagonal regularization on training data, while only little attention is dedicated to concurrently learning both block-diagonal representations of training and test data. In this paper, we propose a discriminative block-diagonal low-rank representation (BDLRR) method for recognition. In particular, the elaborate BDLRR is formulated as a joint optimization problem of shrinking the unfavorable representation from off-block-diagonal elements and strengthening the compact block-diagonal representation under the semi-supervised framework of low-rank representation. To this end, we first impose penalty constraints on the negative representation to eliminate the correlation between different classes such that the incoherence criterion of the extra-class representation is boosted. Moreover, a constructed subspace model is developed to enhance the self-expressive power of training samples and further build the representation bridge between the training and test samples, such that the coherence of the learned intra-class representation is consistently heightened. Finally, the resulting optimization problem is solved elegantly by employing an alternative optimization strategy, and a simple recognition algorithm on the learned representation is utilized for final prediction. Extensive experimental results demonstrate that the proposed method achieves superb recognition results on four face image datasets, three character datasets, and the fifteen scene multi-categories dataset. It not only shows superior potential on image recognition but also outperforms state-of-the-art methods.

##### Abstract (translated by Google)
现有的块对角线表示研究主要集中在对训练数据进行块对角正则化，而对于训练和测试数据的块对角线表示的同时学习却很少引起注意。在本文中，我们提出了一种区分块对角线低秩表示（BDLRR）识别方法。具体而言，精心设计的BDLRR是一个联合优化问题，用于减少离块对角元素的不良表示，并加强低秩表示的半监督框架下的紧致块对角表示。为此，我们首先对消极表征施加惩罚约束，以消除不同阶级之间的相关性，从而提高阶级表征的不一致性标准。此外，构建了子空间模型，以提高训练样本的自我表达能力，进一步构建训练样本与测试样本之间的表征桥梁，使学习到的班内表征的连贯性得到持续提高。最后，通过采用另一种优化策略，优化地解决了所得到的优化问题，并且将学习表示的简单识别算法用于最终预测。广泛的实验结果表明，该方法在四幅人脸图像数据集，三幅字符数据集和十五个场景多类数据集上获得了极好的识别效果。它不仅在图像识别方面表现出优越的潜力，而且还超越了最先进的方法。

##### URL
[https://arxiv.org/abs/1707.03548](https://arxiv.org/abs/1707.03548)

##### PDF
[https://arxiv.org/pdf/1707.03548](https://arxiv.org/pdf/1707.03548)


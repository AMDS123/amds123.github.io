---
layout: post
title: "Visual Saliency Prediction Using a Mixture of Deep Neural Networks"
date: 2017-02-01 17:45:55
categories: arXiv_CV
tags: arXiv_CV Salient CNN Deep_Learning Prediction
author: Samuel Dodge, Lina Karam
mathjax: true
---

* content
{:toc}

##### Abstract
Visual saliency models have recently begun to incorporate deep learning to achieve predictive capacity much greater than previous unsupervised methods. However, most existing models predict saliency using local mechanisms limited to the receptive field of the network. We propose a model that incorporates global scene semantic information in addition to local information gathered by a convolutional neural network. Our model is formulated as a mixture of experts. Each expert network is trained to predict saliency for a set of closely related images. The final saliency map is computed as a weighted mixture of the expert networks' output, with weights determined by a separate gating network. This gating network is guided by global scene information to predict weights. The expert networks and the gating network are trained simultaneously in an end-to-end manner. We show that our mixture formulation leads to improvement in performance over an otherwise identical non-mixture model that does not incorporate global scene information.

##### Abstract (translated by Google)
视觉显着性模型最近已经开始融合深度学习，以实现比之前的无监督方法更大的预测能力。然而，大多数现有的模型使用局限于网络接受领域的局部机制来预测显着性。我们提出了一个模型，除了由卷积神经网络收集的本地信息之外，还包含全局场景语义信息。我们的模式是由专家组成的。训练每个专家网络以预测一组密切相关的图像的显着性。最终的显着图被计算为专家网络输出的加权混合，权重由独立的门控网络确定。这个门控网络是由全球场景信息引导来预测权重。专家网络和门控网络以端到端的方式同时训练。我们表明，我们的混合物配方导致改善性能超过其他相同的非混合模型，不包含全球场景信息。

##### URL
[https://arxiv.org/abs/1702.00372](https://arxiv.org/abs/1702.00372)

##### PDF
[https://arxiv.org/pdf/1702.00372](https://arxiv.org/pdf/1702.00372)


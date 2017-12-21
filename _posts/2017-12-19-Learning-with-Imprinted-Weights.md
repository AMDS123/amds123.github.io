---
layout: post
title: "Learning with Imprinted Weights"
date: 2017-12-19 19:00:08
categories: arXiv_CV
tags: arXiv_CV Embedding Classification Gradient_Descent
author: Hang Qi, Matthew Brown, David G. Lowe
mathjax: true
---

* content
{:toc}

##### Abstract
Human vision is able to immediately recognize novel visual categories after seeing just one or a few training examples. We describe how to add a similar capability to ConvNet classifiers by directly setting the final layer weights from novel training examples during low-shot learning. We call this process weight imprinting as it directly sets weights for a new category based on an appropriately scaled copy of the embedding layer activations for that training example. The imprinting process provides a valuable complement to training with stochastic gradient descent, as it provides immediate good classification performance and an initialization for any further fine-tuning in the future. We show how this imprinting process is related to proxy-based embeddings. However, it differs in that only a single imprinted weight vector is learned for each novel category, rather than relying on a nearest-neighbor distance to training instances as typically used with embedding methods. Our experiments show that using averaging of imprinted weights provides better generalization than using nearest-neighbor instance embeddings.

##### Abstract (translated by Google)
在看到一个或几个训练样例之后，人类视觉就能够立即识别新的视觉类别。我们描述了如何通过在低射击学习期间直接设置来自新颖训练示例的最终层权重来向ConvNet分类器添加类似的能力。我们将这个过程权重称为印记，因为它直接根据该训练示例的嵌入层激活的适当缩放副本为新类别设置权重。压印过程为随机梯度下降训练提供了有价值的补充，因为它提供了即时良好的分类性能，并为将来进一步的微调提供了初始化。我们展示了这个印记过程如何与基于代理的嵌入有关。然而，不同之处在于对于每个新类别只学习单个印迹权向量，而不是像嵌入方法通常使用的那样依赖于训练实例的最近邻距离。我们的实验表明，使用压印权重的平均比使用最近邻居实例嵌入提供了更好的泛化。

##### URL
[https://arxiv.org/abs/1712.07136](https://arxiv.org/abs/1712.07136)

##### PDF
[https://arxiv.org/pdf/1712.07136](https://arxiv.org/pdf/1712.07136)


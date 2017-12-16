---
layout: post
title: "Learning Wasserstein Embeddings"
date: 2017-10-20 09:09:34
categories: arXiv_CV
tags: arXiv_CV Attention Embedding Optimization
author: Nicolas Courty, Rémi Flamary, Mélanie Ducoffe
mathjax: true
---

* content
{:toc}

##### Abstract
The Wasserstein distance received a lot of attention recently in the community of machine learning, especially for its principled way of comparing distributions. It has found numerous applications in several hard problems, such as domain adaptation, dimensionality reduction or generative models. However, its use is still limited by a heavy computational cost. Our goal is to alleviate this problem by providing an approximation mechanism that allows to break its inherent complexity. It relies on the search of an embedding where the Euclidean distance mimics the Wasserstein distance. We show that such an embedding can be found with a siamese architecture associated with a decoder network that allows to move from the embedding space back to the original input space. Once this embedding has been found, computing optimization problems in the Wasserstein space (e.g. barycenters, principal directions or even archetypes) can be conducted extremely fast. Numerical experiments supporting this idea are conducted on image datasets, and show the wide potential benefits of our method.

##### Abstract (translated by Google)
Wasserstein距离最近在机器学习领域受到了极大的关注，特别是其对比分布的原理。它在几个难题中找到了许多应用，例如域适应，降维或生成模型。但是，其使用仍受到计算成本的限制。我们的目标是通过提供一种允许打破其固有复杂性的近似机制来缓解这个问题。它依赖于欧几里德距离模拟Wasserstein距离的嵌入搜索。我们展示了这样的嵌入可以在与解码器网络关联的暹罗式架构中找到，该解码器网络允许从嵌入空间移回原始输入空间。一旦找到这种嵌入，可以非常快速地进行Wasserstein空间（例如重心，主方向甚至原型）中的计算优化问题。支持这个想法的数值实验是在图像数据集上进行的，并展示了我们方法的广泛的潜在好处。

##### URL
[https://arxiv.org/abs/1710.07457](https://arxiv.org/abs/1710.07457)

##### PDF
[https://arxiv.org/pdf/1710.07457](https://arxiv.org/pdf/1710.07457)


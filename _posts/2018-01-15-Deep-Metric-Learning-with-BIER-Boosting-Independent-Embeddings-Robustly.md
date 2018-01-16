---
layout: post
title: "Deep Metric Learning with BIER: Boosting Independent Embeddings Robustly"
date: 2018-01-15 14:22:30
categories: arXiv_CV
tags: arXiv_CV Image_Retrieval Embedding Relation
author: Michael Opitz, Georg Waltner, Horst Possegger, Horst Bischof
mathjax: true
---

* content
{:toc}

##### Abstract
Learning similarity functions between image pairs with deep neural networks yields highly correlated activations of embeddings. In this work, we show how to improve the robustness of such embeddings by exploiting the independence within ensembles. To this end, we divide the last embedding layer of a deep network into an embedding ensemble and formulate training this ensemble as an online gradient boosting problem. Each learner receives a reweighted training sample from the previous learners. Further, we propose two loss functions which increase the diversity in our ensemble. These loss functions can be applied either for weight initialization or during training. Together, our contributions leverage large embedding sizes more effectively by significantly reducing correlation of the embedding and consequently increase retrieval accuracy of the embedding. Our method works with any differentiable loss function and does not introduce any additional parameters during test time. We evaluate our metric learning method on image retrieval tasks and show that it improves over state-of-the-art methods on the CUB 200-2011, Cars-196, Stanford Online Products, In-Shop Clothes Retrieval and VehicleID datasets.

##### Abstract (translated by Google)
学习与深度神经网络的图像对之间的相似性函数产生高度相关的嵌入激活。在这项工作中，我们展示了如何通过利用集合中的独立性来提高这种嵌入的鲁棒性。为此，我们将深度网络的最后一个嵌入层划分为一个嵌入集合，并将这个集合作为在线梯度提升问题进行训练。每个学习者从以前的学习者那里收到一个重新加权的训练样本。此外，我们提出两个损失函数，增加了我们的集合的多样性。这些损失函数可以用于重量初始化或训练期间。通过显着降低嵌入的相关性，从而提高嵌入的检索精度，我们的贡献一起更有效地利用大嵌入大小。我们的方法适用于任何可微分损失函数，并且在测试期间不会引入任何附加参数。我们评估我们的图像检索任务的度量学习方法，并表明它改进了CUB 200-2011，汽车196，斯坦福在线产品，店内衣服检索和VehicleID数据集的最先进的方法。

##### URL
[https://arxiv.org/abs/1801.04815](https://arxiv.org/abs/1801.04815)

##### PDF
[https://arxiv.org/pdf/1801.04815](https://arxiv.org/pdf/1801.04815)


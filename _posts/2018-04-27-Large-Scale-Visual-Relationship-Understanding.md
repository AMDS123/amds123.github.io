---
layout: post
title: "Large-Scale Visual Relationship Understanding"
date: 2018-04-27 19:41:39
categories: arXiv_CV
tags: arXiv_CV Detection Relation
author: Ji Zhang, Yannis Kalantidis, Marcus Rohrbach, Manohar Paluri, Ahmed Elgammal, Mohamed Elhoseiny
mathjax: true
---

* content
{:toc}

##### Abstract
Large scale visual understanding is challenging, as it requires a model to handle the widely-spread and imbalanced distribution of <subject, relation, object> triples. In real-world scenarios with large numbers of objects and relations, some are seen very commonly while others are barely seen. We develop a new relationship detection model that embeds objects and relations into two vector spaces where both discriminative capability and semantic affinity are preserved. We learn both a visual and a semantic module that map features from the two modalities into a shared space, where matched pairs of features have to discriminate against those unmatched, but also maintain close distances to semantically similar ones. Benefiting from that, our model can achieve superior performance even when the visual entity categories scale up to more than 80,000, with extremely skewed class distribution. We demonstrate the efficacy of our model on a large and imbalanced benchmark based of Visual Genome that comprises 53,000+ objects and 29,000+ relations, a scale at which no previous work has ever been evaluated at. We show superiority of our model over carefully designed baselines on Visual Genome, as well as competitive performance on the much smaller VRD dataset.

##### Abstract (translated by Google)
大规模视觉理解具有挑战性，因为它需要一个模型来处理<主体，关系，对象>三元组的广泛传播和不平衡分布。在具有大量物体和关系的现实场景中，有些被非常普遍地看到，而另一些则几乎看不到。我们开发了一种新的关系检测模型，将对象和关系嵌入到两个向量空间中，其中保留了区分能力和语义亲缘关系。我们学习了一个视觉和语义模块，它们将来自两种模式的特征映射到一个共享空间中，其中匹配的特征对必须与那些无法匹配的特征区分开来，但也保持距离语义相似的距离。受益于此，我们的模型即使在视觉实体类别扩展到80,000以上时，也可以实现卓越的性能，并具有非常偏斜的类别分布。我们展示了我们的模型对基于Visual Genome的大型不平衡基准的功效，该基准包含53,000多个对象和29,000多个关系，这是以前没有评估过的工作量表。我们在精心设计的基因组基线上显示了我们模型的优越性，以及在更小的VRD数据集上的竞争性能。

##### URL
[https://arxiv.org/abs/1804.10660](https://arxiv.org/abs/1804.10660)

##### PDF
[https://arxiv.org/pdf/1804.10660](https://arxiv.org/pdf/1804.10660)


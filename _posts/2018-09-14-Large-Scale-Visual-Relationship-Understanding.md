---
layout: post
title: "Large-Scale Visual Relationship Understanding"
date: 2018-09-14 21:57:59
categories: arXiv_CV
tags: arXiv_CV Detection Relation
author: Ji Zhang, Yannis Kalantidis, Marcus Rohrbach, Manohar Paluri, Ahmed Elgammal, Mohamed Elhoseiny
mathjax: true
---

* content
{:toc}

##### Abstract
Large scale visual understanding is challenging, as it requires a model to handle the widely-spread and imbalanced distribution of &lt;subject, relation, object&gt; triples. In real-world scenarios with large numbers of objects and relations, some are seen very commonly while others are barely seen. We develop a new relationship detection model that embeds objects and relations into two vector spaces where both discriminative capability and semantic affinity are preserved. We learn both a visual and a semantic module that map features from the two modalities into a shared space, where matched pairs of features have to discriminate against those unmatched, but also maintain close distances to semantically similar ones. Benefiting from that, our model can achieve superior performance even when the visual entity categories scale up to more than 80,000, with extremely skewed class distribution. We demonstrate the efficacy of our model on a large and imbalanced benchmark based of Visual Genome that comprises 53,000+ objects and 29,000+ relations, a scale at which no previous work has ever been evaluated at. We show superiority of our model over carefully designed baselines on the original Visual Genome dataset with 80,000+ categories. We also show state-of-the-art performance on the VRD dataset and the scene graph dataset which is a subset of Visual Genome with 200 categories.

##### Abstract (translated by Google)
大规模视觉理解具有挑战性，因为它需要一个模型来处理＆lt;主题，关系，对象＆gt;的广泛传播和不平衡分布。三元。在具有大量对象和关系的现实场景中，一些被看到非常普遍，而其他人几乎看不到。我们开发了一种新的关系检测模型，它将对象和关系嵌入到两个向量空间中，同时保留了判别能力和语义关联性。我们学习了一个视觉和语义模块，它将两个模态中的特征映射到共享空间，其中匹配的特征对必须区分那些不匹配的特征，但也保持与语义相似的特征的距离。受益于此，即使视觉实体类别扩展到80,000以上，我们的模型也可以实现卓越的性能，并且类别分布极其偏斜。我们展示了我们的模型在基于Visual Genome的大型且不平衡的基准测试中的功效，该基准测试包含53,000多个对象和29,000多个关系，这个规模以前没有评估过以前的工作。我们的模型优于原始Visual Genome数据集中精心设计的基线，具有80,000多个类别。我们还在VRD数据集和场景图数据集上展示了最先进的性能，该数据集是具有200个类别的Visual Genome的子集。

##### URL
[http://arxiv.org/abs/1804.10660](http://arxiv.org/abs/1804.10660)

##### PDF
[http://arxiv.org/pdf/1804.10660](http://arxiv.org/pdf/1804.10660)


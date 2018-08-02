---
layout: post
title: "Multi-modal Cycle-consistent Generalized Zero-Shot Learning"
date: 2018-08-01 01:47:55
categories: arXiv_CV
tags: arXiv_CV Regularization Adversarial GAN Classification
author: Rafael Felix, B. G. Vijay Kumar, Ian Reid, Gustavo Carneiro
mathjax: true
---

* content
{:toc}

##### Abstract
In generalized zero shot learning (GZSL), the set of classes are split into seen and unseen classes, where training relies on the semantic features of the seen and unseen classes and the visual representations of only the seen classes, while testing uses the visual representations of the seen and unseen classes. Current methods address GZSL by learning a transformation from the visual to the semantic space, exploring the assumption that the distribution of classes in the semantic and visual spaces is relatively similar. Such methods tend to transform unseen testing visual representations into one of the seen classes' semantic features instead of the semantic features of the correct unseen class, resulting in low accuracy GZSL classification. Recently, generative adversarial networks (GAN) have been explored to synthesize visual representations of the unseen classes from their semantic features - the synthesized representations of the seen and unseen classes are then used to train the GZSL classifier. This approach has been shown to boost GZSL classification accuracy, however, there is no guarantee that synthetic visual representations can generate back their semantic feature in a multi-modal cycle-consistent manner. This constraint can result in synthetic visual representations that do not represent well their semantic features. In this paper, we propose the use of such constraint based on a new regularization for the GAN training that forces the generated visual features to reconstruct their original semantic features. Once our model is trained with this multi-modal cycle-consistent semantic compatibility, we can then synthesize more representative visual representations for the seen and, more importantly, for the unseen classes. Our proposed approach shows the best GZSL classification results in the field in several publicly available datasets.

##### Abstract (translated by Google)
在广义零射击学习（GZSL）中，这组类被分成看不见的类和看不见的类，其中训练依赖于看到和看不见的类的语义特征和仅看到的类的可视化表示，而测试使用可视化表示看见和看不见的课程。当前的方法通过学习从视觉空间到语义空间的转换来解决GZSL，探索语义和视觉空间中类的分布相对相似的假设。这些方法倾向于将看不见的测试视觉表示转换为所见类的语义特征之一，而不是正确看不见的类的语义特征，导致GZSL分类的准确性低。最近，已经探索了生成对抗网络（GAN）来从其语义特征合成看不见的类的视觉表示 - 然后使用所看到和未看到的类的合成表示来训练GZSL分类器。这种方法已经被证明可以提高GZSL分类的准确性，但是，不能保证合成的视觉表示可以以多模态循环一致的方式生成它们的语义特征。此约束可能导致合成的视觉表示不能很好地表示其语义特征。在本文中，我们提出了基于GAN训练的新正则化的这种约束的使用，其迫使所生成的视觉特征重建其原始语义特征。一旦我们的模型通过这种多模态循环一致的语义兼容性进行训练，我们就可以为所看到的，更重要的是，为看不见的类合成更具代表性的视觉表示。我们提出的方法在几个公开可用的数据集中显示了该领域中最佳的GZSL分类结果。

##### URL
[https://arxiv.org/abs/1808.00136](https://arxiv.org/abs/1808.00136)

##### PDF
[https://arxiv.org/pdf/1808.00136](https://arxiv.org/pdf/1808.00136)


---
layout: post
title: "SampleAhead: Online Classifier-Sampler Communication for Learning from Synthesized Data"
date: 2018-04-01 02:12:41
categories: arXiv_CV
tags: arXiv_CV Classification Deep_Learning
author: Qi Chen, Weichao Qiu, Yi Zhang, Lingxi Xie, Alan Yuille
mathjax: true
---

* content
{:toc}

##### Abstract
State-of-the-art techniques of artificial intelligence, in particular deep learning, are mostly data-driven. However, collecting and manually labeling a large scale dataset is both difficult and expensive. A promising alternative is to introduce synthesized training data, so that the dataset size can be significantly enlarged with little human labor. But, this raises an important problem in active vision: given an {\bf infinite} data space, how to effectively sample a {\bf finite} subset to train a visual classifier? 
 This paper presents an approach for learning from synthesized data effectively. The motivation is straightforward -- increasing the probability of seeing difficult training data. We introduce a module named {\bf SampleAhead} to formulate the learning process into an online communication between a {\em classifier} and a {\em sampler}, and update them iteratively. In each round, we adjust the sampling distribution according to the classification results, and train the classifier using the data sampled from the updated distribution. Experiments are performed by introducing synthesized images rendered from ShapeNet models to assist PASCAL3D+ classification. Our approach enjoys higher classification accuracy, especially in the scenario of a limited number of training samples. This demonstrates its efficiency in exploring the infinite data space.

##### Abstract (translated by Google)
最先进的人工智能技术，特别是深度学习技术，大部分都是数据驱动的。但是，收集和手动标记大规模数据集既困难又昂贵。一个很有希望的替代方法是引入合成的训练数据，这样数据集的大小可以用很少的人力显着扩大。但是，这提出了主动视觉中的一个重要问题：给定一个{\ bf无限}数据空间，如何有效地采样{\ bf有限}子集来训练视觉分类器？
 本文提出了一种有效地从合成数据中学习的方法。动机很简单 - 增加看到困难训练数据的可能性。我们引入一个名为{\ bf SampleAhead}的模块来将学习过程制定成{\ em分类器}和{\ em sampler}之间的在线通信，并且迭代地更新它们。在每一轮中，我们根据分类结果调整抽样分布，并使用从更新分布中抽取的数据对分类器进行训练。通过引入ShapeNet模型渲染的合成图像来辅助PASCAL3D +分类来进行实验。我们的方法具有更高的分类准确度，特别是在培训样本数量有限的情况下。这证明了它在探索无限数据空间方面的效率。

##### URL
[http://arxiv.org/abs/1804.00248](http://arxiv.org/abs/1804.00248)

##### PDF
[http://arxiv.org/pdf/1804.00248](http://arxiv.org/pdf/1804.00248)


---
layout: post
title: "CRAFT: Complementary Recommendations Using Adversarial Feature Transformer"
date: 2018-05-01 01:54:32
categories: arXiv_CV
tags: arXiv_CV Adversarial Optimization Recommendation
author: Cong Phuoc Huynh, Arri Ciptadi, Ambrish Tyagi, Amit Agrawal (Amazon.com)
mathjax: true
---

* content
{:toc}

##### Abstract
Traditional approaches for complementary product recommendations rely on behavioral and non-visual data such as customer co-views or co-buys. However, certain domains such as fashion are primarily visual. We propose a framework that harnesses visual cues in an unsupervised manner to learn the distribution of co-occurring complementary items in real world images. Our model learns a non-linear transformation between the two manifolds of source and target complementary item categories (e.g., tops and bottoms in outfits). Given a large dataset of images containing instances of co-occurring object categories, we train a generative transformer network directly on the feature representation space by casting it as an adversarial optimization problem. Such a conditional generative model can produce multiple novel samples of complementary items (in the feature space) for a given query item. The final recommendations are selected from the closest real world examples to the synthesized complementary features. We apply our framework to the task of recommending complementary tops for a given bottom clothing item. The recommendations made by our system are diverse, and are favored by human experts over the baseline approaches.

##### Abstract (translated by Google)
传统的补充产品推荐方法依赖于行为和非视觉数据，如客户共同观点或共同购买。但是，某些领域如时尚主要是视觉化的。我们提出了一个框架，以无监督的方式利用视觉线索来了解真实世界图像中共现互补项目的分布情况。我们的模型学习了源和目标补充项目类别的两个流形之间的非线性变换（例如，服装中的顶部和底部）。给定包含共生对象类别实例的大型图像数据集，我们直接在特征表示空间中训练生成变换器网络，将其作为敌对优化问题进行处理。这种条件生成模型可以针对给定的查询项目产生补充项目的多个新样本（在特征空间中）。最终的建议是从最接近真实世界的例子中选择合成的互补特征。我们将我们的框架应用于推荐给定底部衣物的补充上衣的任务。我们的系统提出的建议是多种多样的，并且在基线方法上受到人类专家的青睐。

##### URL
[https://arxiv.org/abs/1804.10871](https://arxiv.org/abs/1804.10871)

##### PDF
[https://arxiv.org/pdf/1804.10871](https://arxiv.org/pdf/1804.10871)


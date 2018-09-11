---
layout: post
title: "CRAFT: Complementary Recommendations Using Adversarial Feature Transformer"
date: 2018-09-10 06:58:24
categories: arXiv_CV
tags: arXiv_CV Adversarial Optimization Recommendation
author: Cong Phuoc Huynh, Arridhana Ciptadi, Ambrish Tyagi, Amit Agrawal (Amazon.com)
mathjax: true
---

* content
{:toc}

##### Abstract
Traditional approaches for complementary product recommendations rely on behavioral and non-visual data such as customer co-views or co-buys. However, certain domains such as fashion are primarily visual. We propose a framework that harnesses visual cues in an unsupervised manner to learn the distribution of co-occurring complementary items in real world images. Our model learns a non-linear transformation between the two manifolds of source and target complementary item categories (e.g., tops and bottoms in outfits). Given a large dataset of images containing instances of co-occurring object categories, we train a generative transformer network directly on the feature representation space by casting it as an adversarial optimization problem. Such a conditional generative model can produce multiple novel samples of complementary items (in the feature space) for a given query item. The final recommendations are selected from the closest real world examples to the synthesized complementary features. We apply our framework to the task of recommending complementary tops for a given bottom clothing item. The recommendations made by our system are diverse, and are favored by human experts over the baseline approaches.

##### Abstract (translated by Google)
补充产品推荐的传统方法依赖于行为和非可视数据，例如客户合作或共同购买。然而，诸如时尚之类的某些领域主要是视觉的。我们提出了一个框架，以无人监督的方式利用视觉线索来学习现实世界图像中共同出现的互补项目的分布。我们的模型学习源和目标互补项目类别的两个流形之间的非线性变换（例如，服装的顶部和底部）。给定包含共同对象类别实例的大型图像数据集，我们通过将其作为对抗优化问题将其直接训练到特征表示空间上来生成变换网络。这样的条件生成模型可以为给定的查询项生成补充项的多个新颖样本（在特征空间中）。最终建议选自最接近的现实世界示例到合成的互补特征。我们将框架应用于为特定底部衣物推荐补充上衣的任务。我们的系统提出的建议是多种多样的，并且受到人类专家对基线方法的青睐。

##### URL
[http://arxiv.org/abs/1804.10871](http://arxiv.org/abs/1804.10871)

##### PDF
[http://arxiv.org/pdf/1804.10871](http://arxiv.org/pdf/1804.10871)


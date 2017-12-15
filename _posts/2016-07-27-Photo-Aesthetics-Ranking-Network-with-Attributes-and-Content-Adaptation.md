---
layout: post
title: "Photo Aesthetics Ranking Network with Attributes and Content Adaptation"
date: 2016-07-27 00:20:07
categories: arXiv_CV
tags: arXiv_CV Face CNN Classification
author: Shu Kong, Xiaohui Shen, Zhe Lin, Radomir Mech, Charless Fowlkes
mathjax: true
---

* content
{:toc}

##### Abstract
Real-world applications could benefit from the ability to automatically generate a fine-grained ranking of photo aesthetics. However, previous methods for image aesthetics analysis have primarily focused on the coarse, binary categorization of images into high- or low-aesthetic categories. In this work, we propose to learn a deep convolutional neural network to rank photo aesthetics in which the relative ranking of photo aesthetics are directly modeled in the loss function. Our model incorporates joint learning of meaningful photographic attributes and image content information which can help regularize the complicated photo aesthetics rating problem. To train and analyze this model, we have assembled a new aesthetics and attributes database (AADB) which contains aesthetic scores and meaningful attributes assigned to each image by multiple human raters. Anonymized rater identities are recorded across images allowing us to exploit intra-rater consistency using a novel sampling strategy when computing the ranking loss of training image pairs. We show the proposed sampling strategy is very effective and robust in face of subjective judgement of image aesthetics by individuals with different aesthetic tastes. Experiments demonstrate that our unified model can generate aesthetic rankings that are more consistent with human ratings. To further validate our model, we show that by simply thresholding the estimated aesthetic scores, we are able to achieve state-or-the-art classification performance on the existing AVA dataset benchmark.

##### Abstract (translated by Google)
真实世界的应用程序可以从自动生成照片美学的细粒度排序的能力中受益。然而，以前的图像美学分析方法主要集中在粗糙的二元图像分类到高或低审美类别。在这项工作中，我们建议学习深度卷积神经网络来对照片美学进行排序，在照片美学中，照片美学的相对排名可以直接在损失函数中建模。我们的模型结合了有意义的摄影属性和图像内容信息的联合学习，可以帮助规范复杂的照片美学评分问题。为了训练和分析这个模型，我们组装了一个新的美学和属性数据库（AADB），其中包含由多个人评估者分配给每个图像的审美分数和有意义的属性。匿名化的评价者身份被记录在图像中，使得我们能够在计算训练图像对的排名损失时利用新颖的抽样策略来利用评分者间的一致性。我们表明，提出的抽样策略是非常有效和强大的面对不同审美口味的个人的形象美学的主观判断。实验表明，我们的统一模型可以产生更符合人类评级的审美排名。为了进一步验证我们的模型，我们表明，通过简单地估计审美分数，我们能够在现有的AVA数据集基准上获得最新的分类性能。

##### URL
[https://arxiv.org/abs/1606.01621](https://arxiv.org/abs/1606.01621)

##### PDF
[https://arxiv.org/pdf/1606.01621](https://arxiv.org/pdf/1606.01621)


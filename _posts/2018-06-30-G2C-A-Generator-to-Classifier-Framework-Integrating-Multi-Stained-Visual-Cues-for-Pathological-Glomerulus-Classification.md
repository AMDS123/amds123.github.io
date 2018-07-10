---
layout: post
title: "G2C: A Generator-to-Classifier Framework Integrating Multi-Stained Visual Cues for Pathological Glomerulus Classification"
date: 2018-06-30 01:09:32
categories: arXiv_CV
tags: arXiv_CV Classification
author: Bingzhe Wu, Xiaolu Zhang, Shiwan Zhao, Lingxi Xie, Caihong Zeng, Zhihong Liu, Guangyu Sun
mathjax: true
---

* content
{:toc}

##### Abstract
Pathological glomerulus classification plays a key role in the diagnosis of nephropathy. As the difference between different subcategories is subtle, doctors often refer to slides from different staining methods to make decisions. However, creating correspondence across various stains is labor-intensive, bringing major difficulties in collecting data and training a vision-based algorithm to assist nephropathy diagnosis. This paper provides an alternative solution for integrating multi-stained visual cues for glomerulus classification. Our approach, named generator-to-classifier (G2C), is a two-stage framework. Given an input image from a specified stain, several generators are first applied to estimate its appearances in other staining methods, and a classifier follows to combine these visual cues for decision making. These two stages are optimized in a joint manner. To provide a reasonable initialization for the generators, we train an unpaired image-to-image translation network for each stain, and fine-tune them with the classifier. Since there are no publicly available datasets for glomerulus classification, we collect one by ourselves. Experiments reveal the effectiveness of our approach, including the authenticity of the generated patches so that doctors can hardly distinguish them from the real ones. We also transfer our model to a public dataset for breast cancer classification, and outperform the state-of-the-arts significantly

##### Abstract (translated by Google)
病理性肾小球分类在肾病的诊断中起关键作用。由于不同亚类之间的差异很微妙，医生通常会参考不同染色方法的幻灯片来做出决定。然而，创建各种污渍之间的对应是劳动密集型的，在收集数据和培训基于视觉的算法以帮助肾病诊断方面带来了重大困难。本文提供了一种整合多染色视觉线索的替代解决方案，用于肾小球分类。我们的方法，名为generator-to-classifier（G2C），是一个两阶段框架。给定来自指定染色的输入图像，首先应用几个生成器来估计其在其他染色方法中的外观，并且遵循分类器以组合这些视觉提示以用于决策。这两个阶段以联合方式进行优化。为了为发生器提供合理的初始化，我们为每个污点训练一个不成对的图像到图像转换网络，并用分类器对它们进行微调。由于肾小球分类没有公开的数据集，我们自己收集一个。实验揭示了我们的方法的有效性，包括生成的补丁的真实性，使医生很难将它们与真实的区分开来。我们还将我们的模型转移到用于乳腺癌分类的公共数据集，并且显着超越了现有技术水平

##### URL
[http://arxiv.org/abs/1807.03136](http://arxiv.org/abs/1807.03136)

##### PDF
[http://arxiv.org/pdf/1807.03136](http://arxiv.org/pdf/1807.03136)


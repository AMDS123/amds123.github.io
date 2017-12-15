---
layout: post
title: "Domain Generalization for Object Recognition with Multi-task Autoencoders"
date: 2015-08-31 04:15:31
categories: arXiv_CV
tags: arXiv_CV Knowledge Recognition
author: Muhammad Ghifary, W. Bastiaan Kleijn, Mengjie Zhang, David Balduzzi
mathjax: true
---

* content
{:toc}

##### Abstract
The problem of domain generalization is to take knowledge acquired from a number of related domains where training data is available, and to then successfully apply it to previously unseen domains. We propose a new feature learning algorithm, Multi-Task Autoencoder (MTAE), that provides good generalization performance for cross-domain object recognition. Our algorithm extends the standard denoising autoencoder framework by substituting artificially induced corruption with naturally occurring inter-domain variability in the appearance of objects. Instead of reconstructing images from noisy versions, MTAE learns to transform the original image into analogs in multiple related domains. It thereby learns features that are robust to variations across domains. The learnt features are then used as inputs to a classifier. We evaluated the performance of the algorithm on benchmark image recognition datasets, where the task is to learn features from multiple datasets and to then predict the image label from unseen datasets. We found that (denoising) MTAE outperforms alternative autoencoder-based models as well as the current state-of-the-art algorithms for domain generalization.

##### Abstract (translated by Google)
领域概括化的问题是从培训数据可用的许多相关领域获取知识，然后将其成功应用到以前看不见的领域。我们提出了一种新的特征学习算法，多任务自动编码器（MTAE），为跨领域对象识别提供了良好的泛化性能。我们的算法扩展了标准的去噪自动编码器框架，通过用对象外观上的自然发生的域间变化来替代人工引起的腐败。而不是从嘈杂的版本重建图像，MTAE学习将原始图像转换成多个相关领域的类比。因此，它学习了对跨域变化强大的功能。学习的特征然后被用作分类器的输入。我们评估了算法在基准图像识别数据集上的性能，其中任务是从多个数据集学习特征，然后预测来自不可见数据集的图像标签。我们发现（去噪）MTAE优于其他基于自动编码器的模型，以及当前最先进的域泛化算法。

##### URL
[https://arxiv.org/abs/1508.07680](https://arxiv.org/abs/1508.07680)

##### PDF
[https://arxiv.org/pdf/1508.07680](https://arxiv.org/pdf/1508.07680)


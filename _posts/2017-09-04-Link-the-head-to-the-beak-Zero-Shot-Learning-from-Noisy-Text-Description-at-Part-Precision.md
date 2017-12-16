---
layout: post
title: "Link the head to the 'beak': Zero Shot Learning from Noisy Text Description at Part Precision"
date: 2017-09-04 20:36:14
categories: arXiv_CV
tags: arXiv_CV Sparse Classification Prediction Recognition
author: Mohamed Elhoseiny, Yizhe Zhu, Han Zhang, Ahmed Elgammal
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper, we study learning visual classifiers from unstructured text descriptions at part precision with no training images. We propose a learning framework that is able to connect text terms to its relevant parts and suppress connections to non-visual text terms without any part-text annotations. For instance, this learning process enables terms like "beak" to be sparsely linked to the visual representation of parts like head, while reduces the effect of non-visual terms like "migrate" on classifier prediction. Images are encoded by a part-based CNN that detect bird parts and learn part-specific representation. Part-based visual classifiers are predicted from text descriptions of unseen visual classifiers to facilitate classification without training images (also known as zero-shot recognition). We performed our experiments on CUBirds 2011 dataset and improves the state-of-the-art text-based zero-shot recognition results from 34.7\% to 43.6\%. We also created large scale benchmarks on North American Bird Images augmented with text descriptions, where we also show that our approach outperforms existing methods. Our code, data, and models are publically available.

##### Abstract (translated by Google)
在本文中，我们研究学习视觉分类器的非结构化文本描述部分精度，没有训练图像。我们提出了一个学习框架，它能够将文本术语连接到相关的部分，并且在没有任何部分文本注释的情况下压制与非视觉文本术语的连接。例如，这种学习过程使像“喙”这样的术语与头部等部分的视觉表现有着稀疏的联系，同时减少了非“视觉”这个术语对分类器预测的影响。图像由基于零件的CNN编码，检测鸟类部分并学习部分特定的表示。基于部分的视觉分类器是根据看不见的视觉分类器的文本描述来预测的，以便于在没有训练图像的情况下进行分类（也称为零点识别）。我们在CUBirds 2011数据集上进行了实验，并将最先进的基于文本的零点识别结果从34.7％提高到了43.6％。我们还创建了北美鸟类图像的大型基准，增加了文本描述，我们也显示了我们的方法优于现有的方法。我们的代码，数据和模型是公开可用的。

##### URL
[https://arxiv.org/abs/1709.01148](https://arxiv.org/abs/1709.01148)

##### PDF
[https://arxiv.org/pdf/1709.01148](https://arxiv.org/pdf/1709.01148)


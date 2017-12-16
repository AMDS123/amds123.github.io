---
layout: post
title: "Contextual Visual Similarity"
date: 2016-12-08 05:53:16
categories: arXiv_CV
tags: arXiv_CV Image_Caption
author: Xiaofang Wang, Kris M. Kitani, Martial Hebert
mathjax: true
---

* content
{:toc}

##### Abstract
Measuring visual similarity is critical for image understanding. But what makes two images similar? Most existing work on visual similarity assumes that images are similar because they contain the same object instance or category. However, the reason why images are similar is much more complex. For example, from the perspective of category, a black dog image is similar to a white dog image. However, in terms of color, a black dog image is more similar to a black horse image than the white dog image. This example serves to illustrate that visual similarity is ambiguous but can be made precise when given an explicit contextual perspective. Based on this observation, we propose the concept of contextual visual similarity. To be concrete, we examine the concept of contextual visual similarity in the application domain of image search. Instead of providing only a single image for image similarity search (\eg, Google image search), we require three images. Given a query image, a second positive image and a third negative image, dissimilar to the first two images, we define a contextualized similarity search criteria. In particular, we learn feature weights over all the feature dimensions of each image such that the distance between the query image and the positive image is small and their distances to the negative image are large after reweighting their features. The learned feature weights encode the contextualized visual similarity specified by the user and can be used for attribute specific image search. We also show the usefulness of our contextualized similarity weighting scheme for different tasks, such as answering visual analogy questions and unsupervised attribute discovery.

##### Abstract (translated by Google)
测量视觉相似性对于理解图像至关重要。但是，什么使两个图像相似？大多数现有的视觉相似性工作都假设图像是相似的，因为它们包含相同的对象实例或类别。但是，图像相似的原因要复杂得多。例如，从类别的角度来看，黑狗图像类似于白狗图像。然而，就颜色而言，黑狗图像比白狗图像更类似于黑马图像。这个例子是为了说明视觉上的相似性是不明确的，但是当给出一个明确的上下文观点时，可以做到精确。基于这个观察，我们提出了上下文视觉相似的概念。具体来说，我们在图像搜索的应用领域研究了上下文视觉相似性的概念。我们不需要为图像相似性搜索（例如，Google图像搜索）提供单个图像，而是需要三幅图像。给定一个查询图像，第二个正面图像和第三个负面图像，不同于前两个图像，我们定义了一个情境化的相似性搜索条件。具体来说，我们学习每个图像的所有特征维度上的特征权重，使得查询图像和正图像之间的距离小，并且在重新加权它们的特征之后到负图像的距离是大的。学习到的特征权重对由用户指定的背景化的视觉相似性进行编码，并且可以用于属性特定的图像搜索。我们还展示了我们的情境化相似性加权方案对于不同任务的有用性，例如回答视觉类比问题和无监督属性发现。

##### URL
[https://arxiv.org/abs/1612.02534](https://arxiv.org/abs/1612.02534)

##### PDF
[https://arxiv.org/pdf/1612.02534](https://arxiv.org/pdf/1612.02534)


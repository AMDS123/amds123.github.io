---
layout: post
title: "Photo Filter Recommendation by Category-Aware Aesthetic Learning"
date: 2017-03-27 05:07:06
categories: arXiv_CV
tags: arXiv_CV Knowledge CNN Classification Recommendation
author: Wei-Tse Sun, Ting-Hsuan Chao, Yin-Hsi Kuo, Winston H. Hsu
mathjax: true
---

* content
{:toc}

##### Abstract
Nowadays, social media has become a popular platform for the public to share photos. To make photos more visually appealing, users usually apply filters on their photos without domain knowledge. However, due to the growing number of filter types, it becomes a major issue for users to choose the best filter type. For this purpose, filter recommendation for photo aesthetics takes an important role in image quality ranking problems. In these years, several works have declared that Convolutional Neural Networks (CNNs) outperform traditional methods in image aesthetic categorization, which classifies images into high or low quality. Most of them do not consider the effect on filtered images; hence, we propose a novel image aesthetic learning for filter recommendation. Instead of binarizing image quality, we adjust the state-of-the-art CNN architectures and design a pairwise loss function to learn the embedded aesthetic responses in hidden layers for filtered images. Based on our pilot study, we observe image categories (e.g., portrait, landscape, food) will affect user preference on filter selection. We further integrate category classification into our proposed aesthetic-oriented models. To the best of our knowledge, there is no public dataset for aesthetic judgment with filtered images. We create a new dataset called Filter Aesthetic Comparison Dataset (FACD). It contains 28,160 filtered images based on the AVA dataset and 42,240 reliable image pairs with aesthetic annotations using Amazon Mechanical Turk. It is the first dataset containing filtered images and user preference labels. We conduct experiments on the collected FACD for filter recommendation, and the results show that our proposed category-aware aesthetic learning outperforms aesthetic classification methods (e.g., 12% relative improvement).

##### Abstract (translated by Google)
如今，社交媒体已经成为公众分享照片的热门平台。为了使照片更具视觉吸引力，用户通常在他们的照片上应用过滤器，而没有领域知识。但是，由于滤波器类型越来越多，用户选择最佳滤波器类型成为主要问题。为此，过滤器对照片美学的建议在图像质量排序问题中起重要作用。近年来，有几篇文章宣称卷积神经网络（CNNs）在图像美学分类方面优于传统方法，将图像分为高质量或低质量。他们大多不考虑对滤波图像的影响;因此，我们提出了一种新颖的图像美学学习过滤器推荐。我们不是将图像质量进行二值化处理，而是调整最先进的CNN架构，并设计成对损失函数来学习隐藏层中的嵌入式审美响应，以便过滤图像。基于我们的试点研究，我们观察图像类别（例如，肖像，风景，食物）将影响用户在过滤器选择上的偏好。我们进一步将类别分类整合到我们提出的审美型模型中。据我们所知，没有用于过滤图像审美判断的公共数据集。我们创建一个名为过滤美学比较数据集（FACD）的新数据集。它包含基于AVA数据集的28,160张过滤图像和使用Amazon Mechanical Turk的42,240张可靠的图像对以及美学注释。这是第一个包含过滤图像和用户偏好标签的数据集。我们对所收集的FACD进行过滤器推荐实验，结果表明，我们提出的类别感知审美学习优于审美分类方法（例如相对改进12％）。

##### URL
[https://arxiv.org/abs/1608.05339](https://arxiv.org/abs/1608.05339)

##### PDF
[https://arxiv.org/pdf/1608.05339](https://arxiv.org/pdf/1608.05339)


---
layout: post
title: "Learning to Segment Object Candidates"
date: 2015-09-01 16:03:01
categories: arXiv_CV
tags: arXiv_CV Object_Detection Segmentation CNN Detection
author: Pedro O. Pinheiro, Ronan Collobert, Piotr Dollar
mathjax: true
---

* content
{:toc}

##### Abstract
Recent object detection systems rely on two critical steps: (1) a set of object proposals is predicted as efficiently as possible, and (2) this set of candidate proposals is then passed to an object classifier. Such approaches have been shown they can be fast, while achieving the state of the art in detection performance. In this paper, we propose a new way to generate object proposals, introducing an approach based on a discriminative convolutional network. Our model is trained jointly with two objectives: given an image patch, the first part of the system outputs a class-agnostic segmentation mask, while the second part of the system outputs the likelihood of the patch being centered on a full object. At test time, the model is efficiently applied on the whole test image and generates a set of segmentation masks, each of them being assigned with a corresponding object likelihood score. We show that our model yields significant improvements over state-of-the-art object proposal algorithms. In particular, compared to previous approaches, our model obtains substantially higher object recall using fewer proposals. We also show that our model is able to generalize to unseen categories it has not seen during training. Unlike all previous approaches for generating object masks, we do not rely on edges, superpixels, or any other form of low-level segmentation.

##### Abstract (translated by Google)
最近的对象检测系统依赖于两个关键步骤：（1）尽可能有效地预测一组对象提议，以及（2）将这组候选提议传递给对象分类器。已经表明，这些方法可以快速，同时实现检测性能的现有技术。在本文中，我们提出了一种生成对象提议的新方法，引入了基于判别卷积网络的方法。我们的模型是与两个目标联合进行训练的：给定一个图像补丁，系统的第一部分输出一个类不可知的分割蒙版，而系统的第二部分输出补丁集中在一个完整的对象上的可能性。在测试时间，模型被有效地应用在整个测试图像上，并生成一组分割掩模，每个分割掩模被分配相应的对象似然分数。我们表明，我们的模型比现有技术的对象提议算法产生显着的改进。具体来说，与以前的方法相比，我们的模型使用较少的提议获得高得多的对象回忆。我们还表明，我们的模型能够推广到在培训期间看不见的类别。与以前的所有生成物体遮罩的方法不同，我们不依赖于边缘，超像素或任何其他形式的低级分割。

##### URL
[https://arxiv.org/abs/1506.06204](https://arxiv.org/abs/1506.06204)

##### PDF
[https://arxiv.org/pdf/1506.06204](https://arxiv.org/pdf/1506.06204)


---
layout: post
title: "Semantic Image Inpainting with Deep Generative Models"
date: 2017-07-13 16:29:21
categories: arXiv_CV
tags: arXiv_CV Inference
author: Raymond A. Yeh, Chen Chen, Teck Yian Lim, Alexander G. Schwing, Mark Hasegawa-Johnson, Minh N. Do
mathjax: true
---

* content
{:toc}

##### Abstract
Semantic image inpainting is a challenging task where large missing regions have to be filled based on the available visual data. Existing methods which extract information from only a single image generally produce unsatisfactory results due to the lack of high level context. In this paper, we propose a novel method for semantic image inpainting, which generates the missing content by conditioning on the available data. Given a trained generative model, we search for the closest encoding of the corrupted image in the latent image manifold using our context and prior losses. This encoding is then passed through the generative model to infer the missing content. In our method, inference is possible irrespective of how the missing content is structured, while the state-of-the-art learning based method requires specific information about the holes in the training phase. Experiments on three datasets show that our method successfully predicts information in large missing regions and achieves pixel-level photorealism, significantly outperforming the state-of-the-art methods.

##### Abstract (translated by Google)
语义图像修复是一个具有挑战性的任务，根据可用的视觉数据，需要填充大量的缺失区域。仅从单个图像提取信息的现有方法通常由于缺乏高层次的上下文而产生不令人满意的结果。在本文中，我们提出了一种新的语义图像修复方法，通过对可用数据进行处理来生成缺失的内容。给定一个训练有素的生成模型，我们使用我们的上下文和先前的损失搜索在潜像集合中被破坏的图像的最接近的编码。然后这个编码通过生成模型来推断缺失的内容。在我们的方法中，推理是可能的，而不管缺少的内容是如何构造的，而最先进的基于学习的方法在训练阶段需要关于洞的特定信息。在三个数据集上的实验表明，我们的方法成功地预测了大面积缺失区域的信息，达到了像素级照片真实感，明显优于最先进的方法。

##### URL
[https://arxiv.org/abs/1607.07539](https://arxiv.org/abs/1607.07539)

##### PDF
[https://arxiv.org/pdf/1607.07539](https://arxiv.org/pdf/1607.07539)


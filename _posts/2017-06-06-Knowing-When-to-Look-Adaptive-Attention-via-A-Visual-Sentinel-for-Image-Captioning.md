---
layout: post
title: "Knowing When to Look: Adaptive Attention via A Visual Sentinel for Image Captioning"
date: 2017-06-06 06:59:15
categories: arXiv_CV
tags: arXiv_CV Image_Caption Attention Caption Language_Model
author: Jiasen Lu, Caiming Xiong, Devi Parikh, Richard Socher
mathjax: true
---

* content
{:toc}

##### Abstract
Attention-based neural encoder-decoder frameworks have been widely adopted for image captioning. Most methods force visual attention to be active for every generated word. However, the decoder likely requires little to no visual information from the image to predict non-visual words such as "the" and "of". Other words that may seem visual can often be predicted reliably just from the language model e.g., "sign" after "behind a red stop" or "phone" following "talking on a cell". In this paper, we propose a novel adaptive attention model with a visual sentinel. At each time step, our model decides whether to attend to the image (and if so, to which regions) or to the visual sentinel. The model decides whether to attend to the image and where, in order to extract meaningful information for sequential word generation. We test our method on the COCO image captioning 2015 challenge dataset and Flickr30K. Our approach sets the new state-of-the-art by a significant margin.

##### Abstract (translated by Google)
基于注意的神经编码器 - 解码器框架已被广泛用于图像字幕。大多数方法强制视觉注意对每个生成的单词都有效。然而，解码器可能几乎不需要来自图像的视觉信息来预测诸如“该”和“之”的非视觉词。通常可以从语言模型可靠地预测看似可视的其他单词，例如，在“在一个单元格上讲话”之后的“红色停止之后”或“电话”之后的“签名”。在本文中，我们提出了一种具有视觉哨兵的新型自适应注意模型。在每个时间步，我们的模型决定是否参加图像（如果是，对哪些区域）或视觉哨兵。模型决定是否关注图像以及在何处，以便为顺序字生成提取有意义的信息。我们在COCO图像字幕2015挑战数据集和Flickr30K上测试我们的方法。我们的方法以最大的优势创造了新的先进技术。

##### URL
[https://arxiv.org/abs/1612.01887](https://arxiv.org/abs/1612.01887)

##### PDF
[https://arxiv.org/pdf/1612.01887](https://arxiv.org/pdf/1612.01887)


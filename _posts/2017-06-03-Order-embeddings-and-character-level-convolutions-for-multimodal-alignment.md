---
layout: post
title: "Order embeddings and character-level convolutions for multimodal alignment"
date: 2017-06-03 20:24:32
categories: arXiv_CV
tags: arXiv_CV Caption Embedding CNN RNN Recognition
author: Jônatas Wehrmann, Anderson Mattjie, Rodrigo C. Barros
mathjax: true
---

* content
{:toc}

##### Abstract
With the novel and fast advances in the area of deep neural networks, several challenging image-based tasks have been recently approached by researchers in pattern recognition and computer vision. In this paper, we address one of these tasks, which is to match image content with natural language descriptions, sometimes referred as multimodal content retrieval. Such a task is particularly challenging considering that we must find a semantic correspondence between captions and the respective image, a challenge for both computer vision and natural language processing areas. For such, we propose a novel multimodal approach based solely on convolutional neural networks for aligning images with their captions by directly convolving raw characters. Our proposed character-based textual embeddings allow the replacement of both word-embeddings and recurrent neural networks for text understanding, saving processing time and requiring fewer learnable parameters. Our method is based on the idea of projecting both visual and textual information into a common embedding space. For training such embeddings we optimize a contrastive loss function that is computed to minimize order-violations between images and their respective descriptions. We achieve state-of-the-art performance in the largest and most well-known image-text alignment dataset, namely Microsoft COCO, with a method that is conceptually much simpler and that possesses considerably fewer parameters than current approaches.

##### Abstract (translated by Google)
随着深度神经网络领域的新颖和快速发展，模式识别和计算机视觉领域的研究人员最近接近了几个具有挑战性的基于图像的任务。在本文中，我们解决这些任务之一，即将图像内容与自然语言描述（有时称为多模式内容检索）进行匹配。考虑到我们必须找到字幕和各自图像之间的语义对应，这对于计算机视觉和自然语言处理领域都是一个挑战，这样的任务是特别具有挑战性的。为此，我们提出了一种基于卷积神经网络的新型多模态方法，通过直接卷积原始字符来将图像与其字幕对齐。我们提出的基于字符的文本嵌入允许替换文本嵌入和递归神经网络以用于文本理解，节省了处理时间并且需要较少的可学习参数。我们的方法基于将视觉和文本信息投影到共同嵌入空间的想法。为了训练这样的嵌入，我们优化了对比损失函数，该函数被计算用于使图像和它们各自的描述之间的顺序违规最小化。我们在最大和最知名的图像文本对齐数据集（即Microsoft COCO）中实现了最先进的性能，其方法在概念上要简单得多，而且比目前的方法具有更少的参数。

##### URL
[https://arxiv.org/abs/1706.00999](https://arxiv.org/abs/1706.00999)

##### PDF
[https://arxiv.org/pdf/1706.00999](https://arxiv.org/pdf/1706.00999)


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
随着深度神经网络领域的新颖和快速发展，研究人员最近在模式识别和计算机视觉方面采用了几项具有挑战性的基于图像的任务。在本文中，我们将解决其中一项任务，即将图像内容与自然语言描述相匹配，有时也称为多模式内容检索。考虑到我们必须在字幕和各自的图像之间找到语义对应，这对于计算机视觉和自然语言处理领域都是一种挑战，这样的任务尤其具有挑战性。为此，我们提出了一种基于卷积神经网络的新型多模式方法，通过直接卷积原始字符来对齐图像及其字幕。我们提出的基于字符的文本嵌入允许替换字嵌入和循环神经网络以便于文本理解，从而节省处理时间并且需要更少的可学习参数。我们的方法基于将视觉和文本信息投影到共同嵌入空间的想法。为了训练这样的嵌入，我们优化了对比度损失函数，该函数被计算以最小化图像与其各自描述之间的顺序违规。我们在最大和最知名的图像文本对齐数据集（即Microsoft COCO）中实现了最先进的性能，其方法在概念上更简单，并且具有比当前方法少得多的参数。

##### URL
[https://arxiv.org/abs/1706.00999](https://arxiv.org/abs/1706.00999)

##### PDF
[https://arxiv.org/pdf/1706.00999](https://arxiv.org/pdf/1706.00999)


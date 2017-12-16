---
layout: post
title: "Improved Texture Networks: Maximizing Quality and Diversity in Feed-forward Stylization and Texture Synthesis"
date: 2017-11-06 14:47:29
categories: arXiv_CV
tags: arXiv_CV CNN Optimization
author: Dmitry Ulyanov, Andrea Vedaldi, Victor Lempitsky
mathjax: true
---

* content
{:toc}

##### Abstract
The recent work of Gatys et al., who characterized the style of an image by the statistics of convolutional neural network filters, ignited a renewed interest in the texture generation and image stylization problems. While their image generation technique uses a slow optimization process, recently several authors have proposed to learn generator neural networks that can produce similar outputs in one quick forward pass. While generator networks are promising, they are still inferior in visual quality and diversity compared to generation-by-optimization. In this work, we advance them in two significant ways. First, we introduce an instance normalization module to replace batch normalization with significant improvements to the quality of image stylization. Second, we improve diversity by introducing a new learning formulation that encourages generators to sample unbiasedly from the Julesz texture ensemble, which is the equivalence class of all images characterized by certain filter responses. Together, these two improvements take feed forward texture synthesis and image stylization much closer to the quality of generation-via-optimization, while retaining the speed advantage.

##### Abstract (translated by Google)
Gatys等人最近的工作是利用卷积神经网络滤波器的统计特征描述图像的风格，引发了对纹理生成和图像程式化问题的重新兴趣。虽然他们的图像生成技术使用一个缓慢的优化过程，最近几个作者已经提出了学习发电机神经网络，可以在一个快速通过产生相似的输出。虽然发电机网络是有前途的，但与通过最优化生成相比，它们的视觉质量和多样性仍然较差。在这项工作中，我们提出了两个重要的方面。首先，我们引入了一个实例规范化模块来取代批量规范化，并且对图像样式的质量有了显着的改进。其次，我们通过引入一个新的学习公式来提高多样性，鼓励发生器从Julesz纹理集合中无偏地采样，Julesz纹理集合是以某些滤波器响应为特征的所有图像的等价类。总之，这两项改进将前馈纹理合成和图像仿真更接近通过优化生成的质量，同时保留了速度优势。

##### URL
[https://arxiv.org/abs/1701.02096](https://arxiv.org/abs/1701.02096)

##### PDF
[https://arxiv.org/pdf/1701.02096](https://arxiv.org/pdf/1701.02096)


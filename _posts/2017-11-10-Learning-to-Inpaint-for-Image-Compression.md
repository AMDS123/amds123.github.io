---
layout: post
title: "Learning to Inpaint for Image Compression"
date: 2017-11-10 06:58:40
categories: arXiv_CV
tags: arXiv_CV
author: Mohammad Haris Baig, Vladlen Koltun, Lorenzo Torresani
mathjax: true
---

* content
{:toc}

##### Abstract
We study the design of deep architectures for lossy image compression. We present two architectural recipes in the context of multi-stage progressive encoders and empirically demonstrate their importance on compression performance. Specifically, we show that: (a) predicting the original image data from residuals in a multi-stage progressive architecture facilitates learning and leads to improved performance at approximating the original content and (b) learning to inpaint (from neighboring image pixels) before performing compression reduces the amount of information that must be stored to achieve a high-quality approximation. Incorporating these design choices in a baseline progressive encoder yields an average reduction of over $60\%$ in file size with similar quality compared to the original residual encoder.

##### Abstract (translated by Google)
我们研究深度架构的有损图像压缩的设计。我们在多级渐进编码器的背景下提出了两个架构配方，并凭经验证明了它们在压缩性能方面的重要性。具体来说，我们表明：（a）从多阶段渐进式体系结构中的残差预测原始图像数据便于学习并导致在近似原始内容方面改善的性能和（b）在执行之前学习（从相邻图像像素）压缩减少了必须存储以实现高质量近似的信息量。将这些设计选项合并到一个基准渐进式编码器中，与原始残差编码器相比，其文件尺寸平均减少了60多美元。

##### URL
[https://arxiv.org/abs/1709.08855](https://arxiv.org/abs/1709.08855)

##### PDF
[https://arxiv.org/pdf/1709.08855](https://arxiv.org/pdf/1709.08855)


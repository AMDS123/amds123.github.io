---
layout: post
title: "Joint Autoregressive and Hierarchical Priors for Learned Image Compression"
date: 2018-09-08 01:51:28
categories: arXiv_CV
tags: arXiv_CV Knowledge Optimization Deep_Learning
author: David Minnen, Johannes Ball&#xe9;, George Toderici
mathjax: true
---

* content
{:toc}

##### Abstract
Recent models for learned image compression are based on autoencoders, learning approximately invertible mappings from pixels to a quantized latent representation. These are combined with an entropy model, a prior on the latent representation that can be used with standard arithmetic coding algorithms to yield a compressed bitstream. Recently, hierarchical entropy models have been introduced as a way to exploit more structure in the latents than simple fully factorized priors, improving compression performance while maintaining end-to-end optimization. Inspired by the success of autoregressive priors in probabilistic generative models, we examine autoregressive, hierarchical, as well as combined priors as alternatives, weighing their costs and benefits in the context of image compression. While it is well known that autoregressive models come with a significant computational penalty, we find that in terms of compression performance, autoregressive and hierarchical priors are complementary and, together, exploit the probabilistic structure in the latents better than all previous learned models. The combined model yields state-of-the-art rate--distortion performance, providing a 15.8% average reduction in file size over the previous state-of-the-art method based on deep learning, which corresponds to a 59.8% size reduction over JPEG, more than 35% reduction compared to WebP and JPEG2000, and bitstreams 8.4% smaller than BPG, the current state-of-the-art image codec. To the best of our knowledge, our model is the first learning-based method to outperform BPG on both PSNR and MS-SSIM distortion metrics.

##### Abstract (translated by Google)
用于学习图像压缩的最新模型基于自动编码器，学习从像素到量化潜在表示的近似可逆映射。这些与熵模型组合，潜在表示的先验可以与标准算术编码算法一起使用以产生压缩比特流。最近，已经引入分级熵模型作为在潜在中利用更多结构而不是简单的完全因子化先验的方式，在保持端到端优化的同时提高压缩性能。受概率生成模型中自回归先验的成功启发，我们研究了自回归，层次化以及组合先验作为替代方案，在图像压缩的背景下权衡其成本和收益。虽然众所周知，自回归模型具有显着的计算代价，但我们发现，就压缩性能而言，自回归和分层先验是互补的，并且一起利用潜在中的概率结构比所有先前学习的模型更好。组合模型产生了最先进的速率 - 失真性能，与基于深度学习的先前最先进方法相比，文件大小平均减少了15.8％，相当于59.8％的尺寸减小超过JPEG，与WebP和JPEG2000相比减少了35％以上，比目标比目前最先进的图像编解码器BPG小8.4％。据我们所知，我们的模型是第一个在PSNR和MS-SSIM失真度量上优于BPG的基于学习的方法。

##### URL
[http://arxiv.org/abs/1809.02736](http://arxiv.org/abs/1809.02736)

##### PDF
[http://arxiv.org/pdf/1809.02736](http://arxiv.org/pdf/1809.02736)


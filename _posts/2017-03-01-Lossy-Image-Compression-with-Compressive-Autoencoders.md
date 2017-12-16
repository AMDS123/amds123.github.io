---
layout: post
title: "Lossy Image Compression with Compressive Autoencoders"
date: 2017-03-01 17:13:47
categories: arXiv_CV
tags: arXiv_CV RNN
author: Lucas Theis, Wenzhe Shi, Andrew Cunningham, Ferenc Huszár
mathjax: true
---

* content
{:toc}

##### Abstract
We propose a new approach to the problem of optimizing autoencoders for lossy image compression. New media formats, changing hardware technology, as well as diverse requirements and content types create a need for compression algorithms which are more flexible than existing codecs. Autoencoders have the potential to address this need, but are difficult to optimize directly due to the inherent non-differentiabilty of the compression loss. We here show that minimal changes to the loss are sufficient to train deep autoencoders competitive with JPEG 2000 and outperforming recently proposed approaches based on RNNs. Our network is furthermore computationally efficient thanks to a sub-pixel architecture, which makes it suitable for high-resolution images. This is in contrast to previous work on autoencoders for compression using coarser approximations, shallower architectures, computationally expensive methods, or focusing on small images.

##### Abstract (translated by Google)
我们提出了一个新的方法来优化有损图像压缩自动编码器的问题。新的媒体格式，不断变化的硬件技术，以及不同的需求和内容类型，都需要比现有的编解码器更加灵活的压缩算法。自动编码器有可能满足这种需求，但是由于压缩损失的固有的不可分性，难以直接进行优化。我们在这里表明，损失的最小变化足以训练与JPEG 2000相竞争的深度自动编码器，并超越最近提出的基于RNN的方法。我们的网络由于采用了亚像素架构，因此具有更高的计算效率，因此适用于高分辨率图像。这与之前关于使用更粗糙的近似，更浅的体系结构，更昂贵的计算方法或专注于小图像的自动编码器的工作相反。

##### URL
[https://arxiv.org/abs/1703.00395](https://arxiv.org/abs/1703.00395)

##### PDF
[https://arxiv.org/pdf/1703.00395](https://arxiv.org/pdf/1703.00395)


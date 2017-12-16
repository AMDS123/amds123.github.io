---
layout: post
title: "Learning a Mixture of Deep Networks for Single Image Super-Resolution"
date: 2017-01-03 20:41:46
categories: arXiv_CV
tags: arXiv_CV Super_Resolution Inference Relation
author: Ding Liu, Zhaowen Wang, Nasser Nasrabadi, Thomas Huang
mathjax: true
---

* content
{:toc}

##### Abstract
Single image super-resolution (SR) is an ill-posed problem which aims to recover high-resolution (HR) images from their low-resolution (LR) observations. The crux of this problem lies in learning the complex mapping between low-resolution patches and the corresponding high-resolution patches. Prior arts have used either a mixture of simple regression models or a single non-linear neural network for this propose. This paper proposes the method of learning a mixture of SR inference modules in a unified framework to tackle this problem. Specifically, a number of SR inference modules specialized in different image local patterns are first independently applied on the LR image to obtain various HR estimates, and the resultant HR estimates are adaptively aggregated to form the final HR image. By selecting neural networks as the SR inference module, the whole procedure can be incorporated into a unified network and be optimized jointly. Extensive experiments are conducted to investigate the relation between restoration performance and different network architectures. Compared with other current image SR approaches, our proposed method achieves state-of-the-arts restoration results on a wide range of images consistently while allowing more flexible design choices. The source codes are available in this http URL

##### Abstract (translated by Google)
单幅图像超分辨率（SR）是一个不适合的问题，旨在从其低分辨率（LR）观测中恢复高分辨率（HR）图像。这个问题的症结在于学习低分辨率补丁和相应的高分辨率补丁之间的复杂映射。对于这个建议，现有技术已经使用了简单回​​归模型的混合或单个非线性神经网络。本文提出了在一个统一的框架下学习混合SR推理模块的方法来解决这个问题。具体而言，首先在LR图像上独立地应用专用于不同图像局部图案的多个SR推断模块，以获得各种HR估计值，并且将由此产生的HR估计值自适应地聚合以形成最终的HR图像。通过选择神经网络作为SR推理模块，将整个过程整合到一个统一的网络中进行联合优化。为了研究恢复性能与不同网络架构之间的关系，进行了大量的实验。与其他当前的图像SR方法相比，我们提出的方法可以在广泛的图像上始终如一地获得最新的恢复结果，同时允许更灵活的设计选择。源代码在这个http URL中可用

##### URL
[https://arxiv.org/abs/1701.00823](https://arxiv.org/abs/1701.00823)

##### PDF
[https://arxiv.org/pdf/1701.00823](https://arxiv.org/pdf/1701.00823)


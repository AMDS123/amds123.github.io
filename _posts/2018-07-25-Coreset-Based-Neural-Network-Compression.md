---
layout: post
title: "Coreset-Based Neural Network Compression"
date: 2018-07-25 18:26:49
categories: arXiv_CV
tags: arXiv_CV CNN Inference
author: Abhimanyu Dubey, Moitreya Chatterjee, Narendra Ahuja
mathjax: true
---

* content
{:toc}

##### Abstract
We propose a novel Convolutional Neural Network (CNN) compression algorithm based on coreset representations of filters. We exploit the redundancies extant in the space of CNN weights and neuronal activations (across samples) in order to obtain compression. Our method requires no retraining, is easy to implement, and obtains state-of-the-art compression performance across a wide variety of CNN architectures. Coupled with quantization and Huffman coding, we create networks that provide AlexNet-like accuracy, with a memory footprint that is $832\times$ smaller than the original AlexNet, while also introducing significant reductions in inference time as well. Additionally these compressed networks when fine-tuned, successfully generalize to other domains as well.

##### Abstract (translated by Google)
我们提出了一种基于滤波器的核心集表示的新型卷积神经网络（CNN）压缩算法。我们利用CNN权重和神经元激活（跨样本）空间中存在的冗余来获得压缩。我们的方法不需要重新训练，易于实现，并且可以在各种CNN架构中获得最先进的压缩性能。结合量化和霍夫曼编码，我们创建了提供类似AlexNet精度的网络，其内存占用空间比原始AlexNet小832美元，而且还大大减少了推理时间。此外，经过微调的这些压缩网络也成功地推广到其他领域。

##### URL
[http://arxiv.org/abs/1807.09810](http://arxiv.org/abs/1807.09810)

##### PDF
[http://arxiv.org/pdf/1807.09810](http://arxiv.org/pdf/1807.09810)


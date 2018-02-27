---
layout: post
title: "PBGAN: Partial Binarization of Deconvolution Based Generators"
date: 2018-02-26 03:50:09
categories: arXiv_CV
tags: arXiv_CV Adversarial GAN CNN Inference
author: Jinglan Liu, Jiaxin Zhang, Yukun Ding, Xiaowei Xu, Meng Jiang, Yiyu Shi
mathjax: true
---

* content
{:toc}

##### Abstract
The generator is quite different from the discriminator in a generative adversarial network (GAN). Compression techniques for the latter have been studied widely, while those for the former stay untouched so far. This work explores the binarization of the deconvolution based generator in a GAN for memory saving and speedup. We show that some layers of the generator may need to be kept in floating point representation to preserve performance, though conventional convolutional neural networks can be completely binarized. As such, only partial binarization may be possible for the generator. To quickly decide whether a layer can be binarized, supported by theoretical analysis and verified by experiments, a simple metric based on the dimension of deconvolution operations is established. Moreover, our results indicate that both generator and discriminator should be binarized at the same time for balanced competition and better performance. Compared with the floating-point version, experimental results based on CelebA suggest that our partial binarization on the generator of the deep convolutional generative adversarial network can yield up to 25.81$\times$ saving in memory consumption, and 1.96$\times$ and 1.32$\times$ speedup in inference and training respectively with little performance loss measured by sliced Wasserstein distance.

##### Abstract (translated by Google)
生成器与生成对抗网络（GAN）中的鉴别器完全不同。后者的压缩技术已被广泛研究，而前者的压缩技术目前尚未被采用。这项工作探讨了GAN中基于去卷积的发生器的二进制化，用于存储器节省和加速。我们表明，发生器的某些层可能需要保持浮点表示以保持性能，尽管传统的卷积神经网络可以完全二进制化。这样，发生器可能只有部分二值化。为了快速决定一个图层是否可以被二值化，在理论分析的支持下并通过实验验证，建立了一个基于反卷积操作维度的简单度量。此外，我们的结果表明，发生器和鉴别器应同时进行二进制化处理，以实现均衡的竞争和更好的性能。与浮点版本相比，基于CelebA的实验结果表明，我们对深度卷积生成对抗网络的生成器的部分二值化可以节省内存消耗高达25.81美元/次，以及1.96美元/次和$ 1.32美元$ \ times $加速推理和训练分别与几何性能损失测量切片Wasserstein距离。

##### URL
[http://arxiv.org/abs/1802.09153](http://arxiv.org/abs/1802.09153)

##### PDF
[http://arxiv.org/pdf/1802.09153](http://arxiv.org/pdf/1802.09153)


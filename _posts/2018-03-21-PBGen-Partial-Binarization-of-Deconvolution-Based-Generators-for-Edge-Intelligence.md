---
layout: post
title: "PBGen: Partial Binarization of Deconvolution-Based Generators for Edge Intelligence"
date: 2018-03-21 01:34:52
categories: arXiv_CV
tags: arXiv_CV GAN CNN Inference
author: Jinglan Liu, Jiaxin Zhang, Yukun Ding, Xiaowei Xu, Meng Jiang, Yiyu Shi
mathjax: true
---

* content
{:toc}

##### Abstract
This work explores the binarization of the deconvolution-based generator in a GAN for memory saving and speedup of image construction. Our study suggests that different from convolutional neural networks (including the discriminator) where all layers can be binarized, only some of the layers in the generator can be binarized without significant performance loss. Supported by theoretical analysis and verified by experiments, a direct metric based on the dimension of deconvolution operations is established, which can be used to quickly decide which layers in the generator can be binarized. Our results also indicate that both the generator and the discriminator should be binarized simultaneously for balanced competition and better performance. Experimental results based on CelebA suggest that directly applying state-of-the-art binarization techniques to all the layers of the generator will lead to 2.83$\times$ performance loss measured by sliced Wasserstein distance compared with the original generator, while applying them to selected layers only can yield up to 25.81$\times$ saving in memory consumption, and 1.96$\times$ and 1.32$\times$ speedup in inference and training respectively with little performance loss.

##### Abstract (translated by Google)
这项工作探讨了在GAN中基于去卷积的发生器的二进制化，用于存储器保存和图像构建的加速。我们的研究表明，不同于卷积神经网络（包括鉴别器），其中所有层可以被二值化，只有发生器中的一些层可以被二值化而没有显着的性能损失。在理论分析和实验验证的基础上，建立了基于去卷积运算维数的直接度量方法，该方法可用于快速判断发生器中的哪些层可以进行二值化。我们的结果还表明，发生器和鉴别器应同时进行二进制化处理，以实现均衡的竞争和更好的性能。基于CelebA的实验结果表明，直接将最先进的二值化技术应用于发生器的所有层将导致与原始发生器相比，通过切片Wasserstein距离测量的性能损失2.83美元倍，同时将其应用于在推断和训练中，所选择的图层只能分别节省内存消耗25.81美元，节省内存消耗1.96美元，加速1.32美元，加速性能增加1.32美元，性能损失很小。

##### URL
[http://arxiv.org/abs/1802.09153](http://arxiv.org/abs/1802.09153)

##### PDF
[http://arxiv.org/pdf/1802.09153](http://arxiv.org/pdf/1802.09153)


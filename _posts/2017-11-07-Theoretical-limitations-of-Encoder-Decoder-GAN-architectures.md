---
layout: post
title: "Theoretical limitations of Encoder-Decoder GAN architectures"
date: 2017-11-07 18:30:24
categories: arXiv_CV
tags: arXiv_CV GAN Inference
author: Sanjeev Arora, Andrej Risteski, Yi Zhang
mathjax: true
---

* content
{:toc}

##### Abstract
Encoder-decoder GANs architectures (e.g., BiGAN and ALI) seek to add an inference mechanism to the GANs setup, consisting of a small encoder deep net that maps data-points to their succinct encodings. The intuition is that being forced to train an encoder alongside the usual generator forces the system to learn meaningful mappings from the code to the data-point and vice-versa, which should improve the learning of the target distribution and ameliorate mode-collapse. It should also yield meaningful codes that are useful as features for downstream tasks. The current paper shows rigorously that even on real-life distributions of images, the encode-decoder GAN training objectives (a) cannot prevent mode collapse; i.e. the objective can be near-optimal even when the generated distribution has low and finite support (b) cannot prevent learning meaningless codes for data -- essentially white noise. Thus if encoder-decoder GANs do indeed work then it must be due to reasons as yet not understood, since the training objective can be low even for meaningless solutions.

##### Abstract (translated by Google)
编码器 - 解码器GAN体系结构（例如BiGAN和ALI）试图向GAN设置添加推理机制，由一个将数据点映射到其简洁编码的小型编码器深网组成。直觉是被迫跟着通常的发生器一起训练一个编码器迫使系统学习从代码到数据点的有意义的映射，反之亦然，这应该改进目标分布的学习和改善模式崩溃。它也应该产生有意义的代码，作为下游任务的功能是有用的。当前的论文严格地表明，即使在图像的实际分布上，编解码器的GAN训练目标（a）也不能防止模式崩溃;即即使所生成的分布具有低的有限支持（b）也不能防止学习数据的无意义代码 - 实质上是白噪声，则目标可以是接近最佳的。因此，如果编码器 - 译码器GAN确实工作，那么它必须是由于还没有被理解的原因，因为即使对于无意义的解决方案，训练目标也可能是低的。

##### URL
[https://arxiv.org/abs/1711.02651](https://arxiv.org/abs/1711.02651)

##### PDF
[https://arxiv.org/pdf/1711.02651](https://arxiv.org/pdf/1711.02651)


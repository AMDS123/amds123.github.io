---
layout: post
title: "tempoGAN: A Temporally Coherent, Volumetric GAN for Super-resolution Fluid Flow"
date: 2018-01-29 19:11:13
categories: arXiv_CV
tags: arXiv_CV Adversarial Super_Resolution GAN Inference
author: You Xie, Erik Franz, Mengyu Chu, Nils Thuerey
mathjax: true
---

* content
{:toc}

##### Abstract
We propose a temporally coherent generative model addressing the super-resolution problem for fluid flows. Our work represents a first approach to synthesize four-dimensional physics fields with neural networks. Based on a conditional generative adversarial network that is designed for the inference of three-dimensional volumetric data, our model generates consistent and detailed results by using a novel temporal discriminator, in addition to the commonly used spatial one. Our experiments show that the generator is able to infer more realistic high-resolution details by using additional physical quantities, such as low-resolution velocities or vorticities. Besides improvements in the training process and in the generated outputs, these inputs offer means for artistic control as well. We additionally employ a physics-aware data augmentation step, which is crucial to avoid overfitting and to reduce memory requirements. In this way, our network learns to generate advected quantities with highly detailed, realistic, and temporally coherent features. Our method works instantaneously, using only a single time-step of low-resolution fluid data. We demonstrate the abilities of our method using a variety of complex inputs and applications in two and three dimensions.

##### Abstract (translated by Google)
我们提出了一个时间一致的生成模型来解决流体流动的超分辨率问题。我们的工作是用神经网络来合成四维物理场的第一种方法。基于三维立体数据推理设计的条件生成对抗网络，我们的模型除了常用的空间数据之外，还使用新颖的时间鉴别器生成一致且详细的结果。我们的实验表明，发生器能够通过使用额外的物理量（例如低分辨率的速度或涡度）来推断更真实的高分辨率细节。除了培训过程和产出的改进之外，这些投入还提供了艺术控制的手段。我们还使用物理意识数据增强步骤，这对于避免过度拟合和减少内存需求至关重要。通过这种方式，我们的网络学习生成具有高度详细的，现实的和时间上一致的特征的平均数量。我们的方法瞬时工作，只使用一个低分辨率流体数据的时间步骤。我们展示了我们的方法在二维和三维中使用各种复杂的输入和应用程序的能力。

##### URL
[https://arxiv.org/abs/1801.09710](https://arxiv.org/abs/1801.09710)

##### PDF
[https://arxiv.org/pdf/1801.09710](https://arxiv.org/pdf/1801.09710)


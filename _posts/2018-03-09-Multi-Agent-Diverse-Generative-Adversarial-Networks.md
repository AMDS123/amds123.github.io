---
layout: post
title: "Multi-Agent Diverse Generative Adversarial Networks"
date: 2018-03-09 23:29:16
categories: arXiv_AI
tags: arXiv_AI Adversarial GAN Face
author: Arnab Ghosh, Viveka Kulharia, Vinay Namboodiri, Philip H. S. Torr, Puneet K. Dokania
mathjax: true
---

* content
{:toc}

##### Abstract
We propose an intuitive generalization to the Generative Adversarial Networks (GANs) and its conditional variants to address the well known mode collapse problem. Firstly, we propose a multi-agent GAN architecture incorporating multiple generators and one discriminator. Secondly, to enforce different generators to capture diverse high probability modes, we modify discriminator's objective function where along with finding the real and fake samples, the discriminator has to identify the generator that generated the fake sample. Intuitively, to succeed in this task, the discriminator must learn to push different generators towards different identifiable modes. Our framework (MAD-GAN) is generalizable in the sense that it can be easily combined with other existing variants of GANs to produce diverse samples. We perform extensive experiments on synthetic and real datasets and compare MAD-GAN with different variants of GAN. We show high quality diverse sample generations for the challenging tasks such as image-to-image translation (known to learn delta distribution) and face generation. In addition, we show that MAD-GAN is able to disentangle different modalities even when trained using highly challenging multi-view dataset (mixture of forests, icebergs, bedrooms etc). In the end, we also show its efficacy for the unsupervised feature representation task. In the appendix we introduce a similarity based competing objective which encourages the different generators to generate varied samples judged by a user defined similarity metric. We show extensive evaluations on a 1-D setting of mixture of gaussians for non parametric density estimation. The theoretical proofs back the efficacy of the framework and explains why various generators are pushed towards distinct clusters of modes.

##### Abstract (translated by Google)
我们提出了对生成对抗网络（GAN）及其条件变体的直观泛化，以解决众所周知的模式崩溃问题。首先，我们提出了一个包含多个生成器和一个鉴别器的多代理GAN体系结构。其次，为了强制不同的生成器捕获不同的高概率模式，我们修改鉴别器的目标函数，在找到真实样本和假样本的同时，鉴别器必须识别生成假样本的生成器。直觉上，要成功完成这项任务，鉴别者必须学会将不同的生成者推向不同的可识别模式。我们的框架（MAD-GAN）是可泛化的，因为它可以很容易地与其他现有的GAN变体组合起来生成不同的样本。我们对合成和真实数据集进行了大量实验，并将MAD-GAN与不同的GAN变体进行比较。我们针对图像到图像的翻译（已知学习三角洲分布）和面部生成等具有挑战性的任务展示高质量的多样化样本。此外，我们表明MAD-GAN即使在使用高度具有挑战性的多视图数据集（森林，冰山，卧室等的混合物）进行训练时也能够解开不同的模式。最后，我们还展示了其对无监督特征表示任务的功效。在附录中，我们介绍了基于相似性的竞争目标，它鼓励不同的生成器生成由用户定义的相似性度量标准判断的不同样本。我们对非参数密度估计的高斯混合的一维设置展示了广泛的评估。理论证明支持该框架的功效，并解释了为什么各种发电机被推向不同的模式集群。

##### URL
[http://arxiv.org/abs/1704.02906](http://arxiv.org/abs/1704.02906)

##### PDF
[http://arxiv.org/pdf/1704.02906](http://arxiv.org/pdf/1704.02906)


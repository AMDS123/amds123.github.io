---
layout: post
title: "Whitening and Coloring transform for GANs"
date: 2018-06-01 16:17:30
categories: arXiv_CV
tags: arXiv_CV Adversarial GAN
author: Aliaksandr Siarohin, Enver Sangineto, Nicu Sebe
mathjax: true
---

* content
{:toc}

##### Abstract
Batch Normalization (BN) is a common technique used both in discriminative and generative networks in order to speed-up training. On the other hand, the learnable parameters of BN are commonly used in conditional Generative Adversarial Networks for representing class-specific information using conditional Batch Normalization (cBN). In this paper we propose to generalize both BN and cBN using a Whitening and Coloring based batch normalization. We apply our method to conditional and unconditional image generation tasks and we show that replacing the BN feature standardization and scaling with our feature whitening and coloring improves the final qualitative results and the training speed. We test our approach on different datasets and we show a consistent improvement orthogonal to different GAN frameworks. Our CIFAR-10 supervised results are higher than all previous works on this dataset.

##### Abstract (translated by Google)
批量标准化（BN）是一种常用技术，用于区分性和生成性网络，以加速培训。另一方面，BN的可学习参数通常用于条件生成对抗网络，用于使用条件批量规范化（cBN）表示特定于类别的信息。在本文中，我们建议使用基于白化和着色的批量归一化概括BN和cBN。我们将我们的方法应用于有条件和无条件的图像生成任务，并且我们展示用特征美白和着色替换BN特征标准化和缩放可以提高最终的定性结果和训练速度。我们在不同的数据集上测试了我们的方法，并且我们展示了与不同GAN框架正交的一致改进。我们的CIFAR-10监督结果高于此数据集的所有以前的作品。

##### URL
[https://arxiv.org/abs/1806.00420](https://arxiv.org/abs/1806.00420)

##### PDF
[https://arxiv.org/pdf/1806.00420](https://arxiv.org/pdf/1806.00420)


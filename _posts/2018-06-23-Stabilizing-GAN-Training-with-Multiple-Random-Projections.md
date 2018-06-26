---
layout: post
title: "Stabilizing GAN Training with Multiple Random Projections"
date: 2018-06-23 00:53:46
categories: arXiv_CV
tags: arXiv_CV Adversarial GAN
author: Behnam Neyshabur, Srinadh Bhojanapalli, Ayan Chakrabarti
mathjax: true
---

* content
{:toc}

##### Abstract
Training generative adversarial networks is unstable in high-dimensions as the true data distribution tends to be concentrated in a small fraction of the ambient space. The discriminator is then quickly able to classify nearly all generated samples as fake, leaving the generator without meaningful gradients and causing it to deteriorate after a point in training. In this work, we propose training a single generator simultaneously against an array of discriminators, each of which looks at a different random low-dimensional projection of the data. Individual discriminators, now provided with restricted views of the input, are unable to reject generated samples perfectly and continue to provide meaningful gradients to the generator throughout training. Meanwhile, the generator learns to produce samples consistent with the full data distribution to satisfy all discriminators simultaneously. We demonstrate the practical utility of this approach experimentally, and show that it is able to produce image samples with higher quality than traditional training with a single discriminator.

##### Abstract (translated by Google)
由于真实的数据分布往往集中在周围空间的一小部分，因此训练生成对抗网络在高维方面不稳定。然后鉴别器很快能够将几乎所有生成的样本归类为假，使得发生器没有有意义的梯度并且在训练点之后使其发生劣化。在这项工作中，我们建议同时对一个鉴别器阵列进行单个发生器的训练，每个鉴别器都会查看数据的不同随机低维投影。个别鉴别器（现在提供输入受限视图）无法完美地拒绝生成的样本，并在整个训练过程中继续为发生器提供有意义的梯度。同时，发生器学习产生符合全部数据分布的样本，以同时满足所有鉴别器。我们通过实验证明了这种方法的实际效用，并且表明它能够产生比具有单一鉴别器的传统训练更高质量的图像样本。

##### URL
[http://arxiv.org/abs/1705.07831](http://arxiv.org/abs/1705.07831)

##### PDF
[http://arxiv.org/pdf/1705.07831](http://arxiv.org/pdf/1705.07831)


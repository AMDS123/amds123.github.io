---
layout: post
title: "User-Guided Deep Anime Line Art Colorization with Conditional Adversarial Networks"
date: 2018-08-09 17:17:47
categories: arXiv_CV
tags: arXiv_CV Adversarial GAN
author: Yuanzheng Ci, Xinzhu Ma, Zhihui Wang, Haojie Li, Zhongxuan Luo
mathjax: true
---

* content
{:toc}

##### Abstract
Scribble colors based line art colorization is a challenging computer vision problem since neither greyscale values nor semantic information is presented in line arts, and the lack of authentic illustration-line art training pairs also increases difficulty of model generalization. Recently, several Generative Adversarial Nets (GANs) based methods have achieved great success. They can generate colorized illustrations conditioned on given line art and color hints. However, these methods fail to capture the authentic illustration distributions and are hence perceptually unsatisfying in the sense that they are often lack of accurate shading. To address these challenges, we propose a novel deep conditional adversarial architecture for scribble based anime line art colorization. Specifically, we integrate the conditional framework with WGAN-GP criteria as well as the perceptual loss to enable us to robustly train a deep network that makes the synthesized images more natural and real. We also introduce a local features network that is independent of synthetic data. With GANs conditioned on features from such network, we notably increase the generalization capability over "in the wild" line arts. Furthermore, we collect two datasets that provide high-quality colorful illustrations and authentic line arts for training and benchmarking. With the proposed model trained on our illustration dataset, we demonstrate that images synthesized by the presented approach are considerably more realistic and precise than alternative approaches.

##### Abstract (translated by Google)
基于涂鸦颜色的线条艺术着色是一个具有挑战性的计算机视觉问题，因为在线条艺术中既没有灰度值也没有语义信息，并且缺乏真实的插图线艺术训练对也增加了模型概括的难度。最近，几种基于生成对抗网（GAN）的方法取得了巨大成功。他们可以根据给定的艺术线条和颜色提示生成彩色插图。然而，这些方法无法捕获真实的插图分布，因此在感觉上它们通常缺乏准确的阴影，因此在感知上不令人满意。为了应对这些挑战，我们提出了一种新的深度条件对抗体系结构，用于基于涂鸦的动漫线条艺术着色。具体来说，我们将条件框架与WGAN-GP标准以及感知损失相结合，使我们能够强大地训练深度网络，使合成图像更自然，更真实。我们还引入了一个独立于合成数据的本地特征网络。由于GAN以这种网络的特征为条件，我们显着提高了“野外”线条艺术的泛化能力。此外，我们收集了两个数据集，提供高质量的彩色插图和真实的线条艺术，用于培训和基准测试。通过在我们的插图数据集上训练所提出的模型，我们证明通过所提出的方法合成的图像比替代方法更加真实和精确。

##### URL
[http://arxiv.org/abs/1808.03240](http://arxiv.org/abs/1808.03240)

##### PDF
[http://arxiv.org/pdf/1808.03240](http://arxiv.org/pdf/1808.03240)


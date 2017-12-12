---
layout: post
title: "From source to target and back: symmetric bi-directional adaptive GAN"
date: 2017-11-29 10:14:52
categories: arXiv_CV
tags: arXiv_CV Adversarial GAN Quantitative
author: Paolo Russo, Fabio Maria Carlucci, Tatiana Tommasi, Barbara Caputo
mathjax: true
---

* content
{:toc}

##### Abstract
The effectiveness of generative adversarial approaches in producing images according to a specific style or visual domain has recently opened new directions to solve the unsupervised domain adaptation problem. It has been shown that source labeled images can be modified to mimic target samples making it possible to train directly a classifier in the target domain, despite the original lack of annotated data. Inverse mappings from the target to the source domain have also been evaluated but only passing through adapted feature spaces, thus without new image generation. In this paper we propose to better exploit the potential of generative adversarial networks for adaptation by introducing a novel symmetric mapping among domains. We jointly optimize bi-directional image transformations combining them with target self-labeling. Moreover we define a new class consistency loss that aligns the generators in the two directions imposing to conserve the class identity of an image passing through both domain mappings. A detailed qualitative and quantitative analysis of the reconstructed images confirm the power of our approach. By integrating the two domain specific classifiers obtained with our bi-directional network we exceed previous state-of-the-art unsupervised adaptation results on four different benchmark datasets.

##### Abstract (translated by Google)
根据特定的风格或视觉领域产生图像的生成对抗方法的有效性最近开辟了解决无监督领域适应问题的新方向。已经表明，源标记图像可以被修改以模仿目标样本，使得可以直接训练目标域中的分类器，尽管原始缺少注释数据。从目标到源域的逆映射也被评估过，但是只能通过自适应的特征空间，因此没有新的图像生成。在本文中，我们建议通过引入域之间的新型对称映射来更好地利用生成对抗网络的适应潜力。我们联合优化双向图像转换，将它们与目标自我标记相结合。此外，我们定义了一个新的类一致性损失，在两个方向上对齐生成器，以保存通过两个域映射的图像的类标识。重建图像的详细的定性和定量分析证实了我们的方法的力量。通过整合与我们的双向网络获得的两个领域特定的分类器，我们超过了先前在四个不同的基准数据集上的最先进的无监督的适应结果。

##### URL
[https://arxiv.org/abs/1705.08824](https://arxiv.org/abs/1705.08824)

##### PDF
[https://arxiv.org/pdf/1705.08824](https://arxiv.org/pdf/1705.08824)


---
layout: post
title: "RankIQA: Learning from Rankings for No-reference Image Quality Assessment"
date: 2017-07-26 10:02:40
categories: arXiv_CV
tags: arXiv_CV Knowledge QA
author: Xialei Liu, Joost van de Weijer, Andrew D. Bagdanov
mathjax: true
---

* content
{:toc}

##### Abstract
We propose a no-reference image quality assessment (NR-IQA) approach that learns from rankings (RankIQA). To address the problem of limited IQA dataset size, we train a Siamese Network to rank images in terms of image quality by using synthetically generated distortions for which relative image quality is known. These ranked image sets can be automatically generated without laborious human labeling. We then use fine-tuning to transfer the knowledge represented in the trained Siamese Network to a traditional CNN that estimates absolute image quality from single images. We demonstrate how our approach can be made significantly more efficient than traditional Siamese Networks by forward propagating a batch of images through a single network and backpropagating gradients derived from all pairs of images in the batch. Experiments on the TID2013 benchmark show that we improve the state-of-the-art by over 5%. Furthermore, on the LIVE benchmark we show that our approach is superior to existing NR-IQA techniques and that we even outperform the state-of-the-art in full-reference IQA (FR-IQA) methods without having to resort to high-quality reference images to infer IQA.

##### Abstract (translated by Google)
我们提出一个从参考排名（RankIQA）学习的无参考图像质量评估（NR-IQA）方法。为了解决有限的IQA数据集大小的问题，我们训练连体网络以通过使用已知的相对图像质量的合成生成的失真对图像质量进行排名。这些排名的图像集可以自动生成，而不费力的人类标签。然后，我们使用微调将训练的Siamese网络中表示的知识转移到一个传统的CNN中，该CNN从单个图像中估计绝对图像质量。我们演示了如何通过一个网络向前传播一批图像，并从批次中的所有图像对反向传播梯度，使我们的方法比传统的连体网络更有效率。 TID2013基准的实验表明，我们改进了超过5％的最新技术水平。此外，在LIVE基准测试中，我们展示了我们的方法优于现有的NR-IQA技术，甚至超越了全参考IQA（FR-IQA）方法的先进水平，质量参考图像来推断IQA。

##### URL
[https://arxiv.org/abs/1707.08347](https://arxiv.org/abs/1707.08347)

##### PDF
[https://arxiv.org/pdf/1707.08347](https://arxiv.org/pdf/1707.08347)


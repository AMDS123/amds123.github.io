---
layout: post
title: "CGIntrinsics: Better Intrinsic Image Decomposition through Physically-Based Rendering"
date: 2018-08-26 17:58:46
categories: arXiv_CV
tags: arXiv_CV Sparse
author: Zhengqi Li, Noah Snavely
mathjax: true
---

* content
{:toc}

##### Abstract
Intrinsic image decomposition is a challenging, long-standing computer vision problem for which ground truth data is very difficult to acquire. We explore the use of synthetic data for training CNN-based intrinsic image decomposition models, then applying these learned models to real-world images. To that end, we present \ICG, a new, large-scale dataset of physically-based rendered images of scenes with full ground truth decompositions. The rendering process we use is carefully designed to yield high-quality, realistic images, which we find to be crucial for this problem domain. We also propose a new end-to-end training method that learns better decompositions by leveraging \ICG, and optionally IIW and SAW, two recent datasets of sparse annotations on real-world images. Surprisingly, we find that a decomposition network trained solely on our synthetic data outperforms the state-of-the-art on both IIW and SAW, and performance improves even further when IIW and SAW data is added during training. Our work demonstrates the suprising effectiveness of carefully-rendered synthetic data for the intrinsic images task.

##### Abstract (translated by Google)
内在图像分解是一个具有挑战性的长期计算机视觉问题，很难获得地面实况数据。我们探索使用合成数据来训练基于CNN的内在图像分解模型，然后将这些学习的模型应用于真实世界的图像。为此，我们提出了\ ICG，这是一个新的大型数据集，基于物理渲染的场景渲染图像，具有完整的地面真实分解。我们使用的渲染过程经过精心设计，可以生成高质量，逼真的图像，我们发现这对于这个问题领域至关重要。我们还提出了一种新的端到端训练方法，该方法通过利用\ ICG以及可选的IIW和SAW（现实世界图像上的两个稀疏注释数据集）来学习更好的分解。令人惊讶的是，我们发现仅依靠我们的合成数据训练的分解网络优于IIW和SAW的最新技术，并且在训练期间添加IIW和SAW数据时性能进一步提高。我们的工作展示了精心渲染的合成数据对于内在图像任务的惊人效果。

##### URL
[http://arxiv.org/abs/1808.08601](http://arxiv.org/abs/1808.08601)

##### PDF
[http://arxiv.org/pdf/1808.08601](http://arxiv.org/pdf/1808.08601)


---
layout: post
title: "Convolutional Dictionary Learning via Local Processing"
date: 2017-05-09 09:07:59
categories: arXiv_CV
tags: arXiv_CV Sparse CNN Relation
author: Vardan Papyan, Yaniv Romano, Jeremias Sulam, Michael Elad
mathjax: true
---

* content
{:toc}

##### Abstract
Convolutional Sparse Coding (CSC) is an increasingly popular model in the signal and image processing communities, tackling some of the limitations of traditional patch-based sparse representations. Although several works have addressed the dictionary learning problem under this model, these relied on an ADMM formulation in the Fourier domain, losing the sense of locality and the relation to the traditional patch-based sparse pursuit. A recent work suggested a novel theoretical analysis of this global model, providing guarantees that rely on a localized sparsity measure. Herein, we extend this local-global relation by showing how one can efficiently solve the convolutional sparse pursuit problem and train the filters involved, while operating locally on image patches. Our approach provides an intuitive algorithm that can leverage standard techniques from the sparse representations field. The proposed method is fast to train, simple to implement, and flexible enough that it can be easily deployed in a variety of applications. We demonstrate the proposed training scheme for image inpainting and image separation, while achieving state-of-the-art results.

##### Abstract (translated by Google)
卷积稀疏编码（CSC）是信号和图像处理领域日益流行的模型，解决了传统的基于补丁的稀疏表示的一些局限性。虽然在这个模型下，有些作品已经解决了字典学习问题，但是这些都依赖于傅立叶域的ADMM公式，失去了局部感和与传统的基于块的稀疏追求的关系。最近的一项工作提出了对这种全球模式的新颖的理论分析，提供了依靠局部稀疏度量的保证。在此，我们通过展示如何有效地解决卷积稀疏追踪问题和训练所涉及的滤波器，同时在图像块上本地操作，来扩展这种局部 - 全局关系。我们的方法提供了一个直观的算法，可以利用稀疏表示领域的标准技术。所提出的方法训练速度快，实施简单，并且足够灵活，以致可以容易地部署在各种应用中。我们展示了提出的图像修复和图像分离培训方案，同时实现了最先进的结果。

##### URL
[https://arxiv.org/abs/1705.03239](https://arxiv.org/abs/1705.03239)

##### PDF
[https://arxiv.org/pdf/1705.03239](https://arxiv.org/pdf/1705.03239)


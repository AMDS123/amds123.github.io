---
layout: post
title: "What Properties are Desirable from an Electron Microscopy Segmentation Algorithm"
date: 2015-09-28 14:05:32
categories: arXiv_CV
tags: arXiv_CV Sparse Segmentation
author: Toufiq Parag
mathjax: true
---

* content
{:toc}

##### Abstract
The prospect of neural reconstruction from Electron Microscopy (EM) images has been elucidated by the automatic segmentation algorithms. Although segmentation algorithms eliminate the necessity of tracing the neurons by hand, significant manual effort is still essential for correcting the mistakes they make. A considerable amount of human labor is also required for annotating groundtruth volumes for training the classifiers of a segmentation framework. It is critically important to diminish the dependence on human interaction in the overall reconstruction system. This study proposes a novel classifier training algorithm for EM segmentation aimed to reduce the amount of manual effort demanded by the groundtruth annotation and error refinement tasks. Instead of using an exhaustive pixel level groundtruth, an active learning algorithm is proposed for sparse labeling of pixel and boundaries of superpixels. Because over-segmentation errors are in general more tolerable and easier to correct than the under-segmentation errors, our algorithm is designed to prioritize minimization of false-merges over false-split mistakes. Our experiments on both 2D and 3D data suggest that the proposed method yields segmentation outputs that are more amenable to neural reconstruction than those of existing methods.

##### Abstract (translated by Google)
自动分割算法已经阐明了电子显微镜（EM）图像神经重构的前景。虽然分割算法消除了手动追踪神经元的必要性，但重要的手动操作仍然是纠正错误的关键。为了训练分割框架的分类器，还需要大量的人力来注释地面实体。减少整个重建系统对人类交往的依赖是至关重要的。本研究提出了一种新的EM分割分类器训练算法，旨在减少地面真实标注和误差精化任务所需的人工操作量。提出了一种主动学习算法，用于超像素的像素和边界的稀疏标记，而不是使用穷尽像素级的groundtruth。由于过分割误差通常比欠缺分割误差更容易且更容易纠正，所以我们的算法被设计成优先考虑将错误合并最小化为错误分割错误。我们对2D和3D数据的实验表明，所提出的方法产生比现有方法更适合于神经重建的分割输出。

##### URL
[https://arxiv.org/abs/1503.05430](https://arxiv.org/abs/1503.05430)

##### PDF
[https://arxiv.org/pdf/1503.05430](https://arxiv.org/pdf/1503.05430)


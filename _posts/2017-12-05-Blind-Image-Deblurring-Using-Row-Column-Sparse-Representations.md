---
layout: post
title: "Blind Image Deblurring Using Row-Column Sparse Representations"
date: 2017-12-05 21:39:29
categories: arXiv_CV
tags: arXiv_CV Sparse Optimization Quantitative
author: Mohammad Tofighi, Yuelong Li, Vishal Monga
mathjax: true
---

* content
{:toc}

##### Abstract
Blind image deblurring is a particularly challenging inverse problem where the blur kernel is unknown and must be estimated en route to recover the deblurred image. The problem is of strong practical relevance since many imaging devices such as cellphone cameras, must rely on deblurring algorithms to yield satisfactory image quality. Despite significant research effort, handling large motions remains an open problem. In this paper, we develop a new method called Blind Image Deblurring using Row-Column Sparsity (BD-RCS) to address this issue. Specifically, we model the outer product of kernel and image coefficients in certain transformation domains as a rank-one matrix, and recover it by solving a rank minimization problem. Our central contribution then includes solving {\em two new} optimization problems involving row and column sparsity to automatically determine blur kernel and image support sequentially. The kernel and image can then be recovered through a singular value decomposition (SVD). Experimental results on linear motion deblurring demonstrate that BD-RCS can yield better results than state of the art, particularly when the blur is caused by large motion. This is confirmed both visually and through quantitative measures.

##### Abstract (translated by Google)
盲图像去模糊是一个特别具有挑战性的逆问题，其中模糊核是未知的，必须在途中估计以恢复去模糊的图像。这个问题具有很强的实际意义，因为许多成像设备（如手机相机）必须依靠去模糊算法来产生令人满意的图像质量。尽管进行了大量的研究工作，处理大动作仍然是一个开放的问题在本文中，我们使用行列稀疏（BD-RCS）开发了一种名为“Blind Image Deblurring”的新方法来解决这个问题。具体来说，我们将核函数和图像系数的外积作为一个一级矩阵在某些变换域中建模，并通过求解一个秩最小化问题来恢复它。我们的核心贡献包括解决涉及行和列稀疏性的两个新的优化问题，以便顺序地自动确定模糊核和图像支持。然后可以通过奇异值分解（SVD）来恢复内核和图像。直线运动去模糊的实验结果表明，BD-RCS可以产生比现有技术更好的结果，特别是当模糊是由大的运动引起时。这通过视觉和定量措施得到证实。

##### URL
[http://arxiv.org/abs/1712.01937](http://arxiv.org/abs/1712.01937)

##### PDF
[http://arxiv.org/pdf/1712.01937](http://arxiv.org/pdf/1712.01937)


---
layout: post
title: "The Little Engine that Could: Regularization by Denoising"
date: 2017-09-03 10:36:54
categories: arXiv_CV
tags: arXiv_CV Regularization Super_Resolution Optimization
author: Yaniv Romano, Michael Elad, Peyman Milanfar
mathjax: true
---

* content
{:toc}

##### Abstract
Removal of noise from an image is an extensively studied problem in image processing. Indeed, the recent advent of sophisticated and highly effective denoising algorithms lead some to believe that existing methods are touching the ceiling in terms of noise removal performance. Can we leverage this impressive achievement to treat other tasks in image processing? Recent work has answered this question positively, in the form of the Plug-and-Play Prior ($P^3$) method, showing that any inverse problem can be handled by sequentially applying image denoising steps. This relies heavily on the ADMM optimization technique in order to obtain this chained denoising interpretation. Is this the only way in which tasks in image processing can exploit the image denoising engine? In this paper we provide an alternative, more powerful and more flexible framework for achieving the same goal. As opposed to the $P^3$ method, we offer Regularization by Denoising (RED): using the denoising engine in defining the regularization of the inverse problem. We propose an explicit image-adaptive Laplacian-based regularization functional, making the overall objective functional clearer and better defined. With a complete flexibility to choose the iterative optimization procedure for minimizing the above functional, RED is capable of incorporating any image denoising algorithm, treat general inverse problems very effectively, and is guaranteed to converge to the globally optimal result. We test this approach and demonstrate state-of-the-art results in the image deblurring and super-resolution problems.

##### Abstract (translated by Google)
从图像中去除噪声是图像处理中广泛研究的问题。实际上，最近出现的复杂高效的去噪算法使得人们相信现有的方法在噪声去除性能方面正在触及最高限度。我们可以利用这个令人印象深刻的成就来处理其他图像处理任务吗最近的研究已经以即插即用（Pre-Play Prior）（$ P ^ 3 $）方法的形式积极回答了这个问题，表明任何逆问题都可以通过顺序应用图像去噪步骤来处理。这很大程度上依赖于ADMM优化技术来获得这种链式去噪解释。这是图像处理中的任务可以利用图像去噪引擎的唯一方式吗？在本文中，我们提供了一个替代，更强大，更灵活的框架来实现相同的目标。与$ P ^ 3 $方法相反，我们通过去噪（RED）来提供正则化：使用去噪引擎来定义逆问题的正则化。我们提出了一个显式的图像自适应拉普拉斯正则化函数，使整体目标函数更清晰和更好地定义。 RED具有完全灵活的选择迭代优化程序以最小化上述功能，能够结合任何图像去噪算法，能够非常有效地处理一般的逆问题，并保证收敛到全局最优结果。我们测试了这种方法，并在图像去模糊和超分辨率问题上展示了最新的结果。

##### URL
[https://arxiv.org/abs/1611.02862](https://arxiv.org/abs/1611.02862)

##### PDF
[https://arxiv.org/pdf/1611.02862](https://arxiv.org/pdf/1611.02862)


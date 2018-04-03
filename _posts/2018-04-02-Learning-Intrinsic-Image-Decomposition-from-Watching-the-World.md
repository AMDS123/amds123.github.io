---
layout: post
title: "Learning Intrinsic Image Decomposition from Watching the World"
date: 2018-04-02 15:06:11
categories: arXiv_CV
tags: arXiv_CV
author: Zhengqi Li, Noah Snavely
mathjax: true
---

* content
{:toc}

##### Abstract
Single-view intrinsic image decomposition is a highly ill-posed problem, and so a promising approach is to learn from large amounts of data. However, it is difficult to collect ground truth training data at scale for intrinsic images. In this paper, we explore a different approach to learning intrinsic images: observing image sequences over time depicting the same scene under changing illumination, and learning single-view decompositions that are consistent with these changes. This approach allows us to learn without ground truth decompositions, and to instead exploit information available from multiple images when training. Our trained model can then be applied at test time to single views. We describe a new learning framework based on this idea, including new loss functions that can be efficiently evaluated over entire sequences. While prior learning-based methods achieve good performance on specific benchmarks, we show that our approach generalizes well to several diverse datasets, including MIT intrinsic images, Intrinsic Images in the Wild and Shading Annotations in the Wild.

##### Abstract (translated by Google)
单视图固有图像分解是一个非常不适合的问题，因此一种有前途的方法是从大量数据中学习。然而，难以为内在图像收集大规模的地面真实训练数据。在本文中，我们探索了一种不同的学习内在图像的方法：观察随时间变化的图像序列，描述变化照明下的相同场景，以及学习与这些变化一致的单视图分解。这种方法允许我们在没有地面真实分解的情况下进行学习，而是在训练时利用多幅图像中可用的信息。然后，我们训练有素的模型可以在测试时应用于单个视图。我们基于这个想法描述了一个新的学习框架，包括可以在整个序列上进行有效评估的新损失函数。虽然之前的基于学习的方法在特定的基准测试中取得了良好的表现，但我们表明，我们的方法很好地适用于几种不同的数据集，包括麻省理工学院内在图像，野外内在图像和野外着色注解。

##### URL
[http://arxiv.org/abs/1804.00582](http://arxiv.org/abs/1804.00582)

##### PDF
[http://arxiv.org/pdf/1804.00582](http://arxiv.org/pdf/1804.00582)


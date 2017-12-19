---
layout: post
title: "Object localization in ImageNet by looking out of the window"
date: 2015-08-04 14:55:33
categories: arXiv_CV
tags: arXiv_CV Classification Relation
author: Alexander Vezhnevets, Vittorio Ferrari
mathjax: true
---

* content
{:toc}

##### Abstract
We propose a method for annotating the location of objects in ImageNet. Traditionally, this is cast as an image window classification problem, where each window is considered independently and scored based on its appearance alone. Instead, we propose a method which scores each candidate window in the context of all other windows in the image, taking into account their similarity in appearance space as well as their spatial relations in the image plane. We devise a fast and exact procedure to optimize our scoring function over all candidate windows in an image, and we learn its parameters using structured output regression. We demonstrate on 92000 images from ImageNet that this significantly improves localization over recent techniques that score windows in isolation.

##### Abstract (translated by Google)
我们提出了一种在ImageNet中注释对象位置的方法。传统上，这被认为是一个图像窗口分类问题，每个窗口都被独立地考虑并根据其外观进行评分。相反，我们提出了一种方法，在图像中的所有其他窗口的上下文中对每个候选窗口进行评分，考虑到它们在外观空间上的相似性以及它们在图像平面中的空间关系。我们设计了一个快速和精确的程序来优化图像中所有候选窗口的评分函数，并且我们使用结构化输出回归来学习它的参数。我们在ImageNet的92000个图像上展示了这个技术，可以显着改善最近分离窗口的技术的本地化。

##### URL
[https://arxiv.org/abs/1501.01181](https://arxiv.org/abs/1501.01181)

##### PDF
[https://arxiv.org/pdf/1501.01181](https://arxiv.org/pdf/1501.01181)


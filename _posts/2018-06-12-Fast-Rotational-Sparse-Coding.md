---
layout: post
title: "Fast Rotational Sparse Coding"
date: 2018-06-12 07:49:42
categories: arXiv_CV
tags: arXiv_CV Sparse Classification
author: Michael T. McCann, Michael Unser, Adrien Depeursinge
mathjax: true
---

* content
{:toc}

##### Abstract
We propose an algorithm for rotational sparse coding along with an efficient implementation using steerability. Sparse coding (also called \emph{dictionary learning}) is an important technique in image processing, useful in inverse problems, compression, and analysis; however, the usual formulation fails to capture an important aspect of the structure of images: images are formed from building blocks, e.g., edges, lines, or points, that appear at different locations, orientations, and scales. The sparse coding problem can be reformulated to explicitly account for these transforms, at the cost of increased computational cost. In this work, we propose an algorithm for a rotational version of sparse coding that is based on K-SVD with additional rotation operations. We then propose a method to accelerate these rotations by learning the dictionary in a steerable basis. We compare the proposed approach to standard sparse with experiments on patch coding and texture classification; in the latter case we report state-of-the-art results on the Outex_TC_00010 dataset.

##### Abstract (translated by Google)
我们提出了一个旋转稀疏编码算法，以及一个使用可控性的有效实现。稀疏编码（也称为\ emph {字典学习}）是图像处理中的一项重要技术，可用于逆向问题，压缩和分析;然而，通常的表述未能捕捉图像结构的重要方面：图像由构建块形成，例如出现在不同位置，方向和尺度的边缘，线条或点。稀疏编码问题可以重新制定以明确说明这些变换，但代价是计算成本增加。在这项工作中，我们提出了一种基于K-SVD和其他旋转操作的稀疏编码旋转版本的算法。然后，我们提出一种通过在可操纵基础上学习字典来加速这些旋转的方法。我们将所提出的标准稀疏方法与补丁编码和纹理分类的实验进行了比较;在后一种情况下，我们会报告Outex_TC_00010数据集的最新结果。

##### URL
[http://arxiv.org/abs/1806.04374](http://arxiv.org/abs/1806.04374)

##### PDF
[http://arxiv.org/pdf/1806.04374](http://arxiv.org/pdf/1806.04374)


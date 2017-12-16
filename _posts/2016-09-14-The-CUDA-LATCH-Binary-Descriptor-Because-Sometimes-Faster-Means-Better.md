---
layout: post
title: "The CUDA LATCH Binary Descriptor: Because Sometimes Faster Means Better"
date: 2016-09-14 00:51:19
categories: arXiv_CV
tags: arXiv_CV
author: Christopher Parker, Matthew Daiter, Kareem Omar, Gil Levi, Tal Hassner
mathjax: true
---

* content
{:toc}

##### Abstract
Accuracy, descriptor size, and the time required for extraction and matching are all important factors when selecting local image descriptors. To optimize over all these requirements, this paper presents a CUDA port for the recent Learned Arrangement of Three Patches (LATCH) binary descriptors to the GPU platform. The design of LATCH makes it well suited for GPU processing. Owing to its small size and binary nature, the GPU can further be used to efficiently match LATCH features. Taken together, this leads to breakneck descriptor extraction and matching speeds. We evaluate the trade off between these speeds and the quality of results in a feature matching intensive application. To this end, we use our proposed CUDA LATCH (CLATCH) to recover structure from motion (SfM), comparing 3D reconstructions and speed using different representations. Our results show that CLATCH provides high quality 3D reconstructions at fractions of the time required by other representations, with little, if any, loss of reconstruction quality.

##### Abstract (translated by Google)
精确度，描述符大小和提取和匹配所需的时间都是选择局部图像描述符时的重要因素。为了优化所有这些要求，本文提出了针对GPU平台上最近的三个补丁（LATCH）二进制描述符的学习安排的CUDA端口。 LATCH的设计使其非常适合GPU处理。由于其尺寸小和二进制特性，GPU可以进一步用于有效地匹配LATCH功能。综上所述，这导致了描述符提取和匹配速度的严重。我们评估这些速度与功能匹配密集型应用程序的结果质量之间的平衡。为此，我们使用我们提出的CUDA LATCH（CLATCH）从运动恢复结构（SfM），比较三维重建和速度使用不同的表示。我们的研究结果表明，CLATCH提供高质量的三维重建在一小部分时间所需的其他表示，几乎没有，如果有的话，重建质量的损失。

##### URL
[https://arxiv.org/abs/1609.03986](https://arxiv.org/abs/1609.03986)

##### PDF
[https://arxiv.org/pdf/1609.03986](https://arxiv.org/pdf/1609.03986)


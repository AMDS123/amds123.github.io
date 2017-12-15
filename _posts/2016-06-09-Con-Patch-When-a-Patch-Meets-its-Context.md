---
layout: post
title: "Con-Patch: When a Patch Meets its Context"
date: 2016-06-09 14:14:58
categories: arXiv_CV
tags: arXiv_CV Super_Resolution
author: Yaniv Romano, Michael Elad
mathjax: true
---

* content
{:toc}

##### Abstract
Measuring the similarity between patches in images is a fundamental building block in various tasks. Naturally, the patch-size has a major impact on the matching quality, and on the consequent application performance. Under the assumption that our patch database is sufficiently sampled, using large patches (e.g. 21-by-21) should be preferred over small ones (e.g. 7-by-7). However, this "dense-sampling" assumption is rarely true; in most cases large patches cannot find relevant nearby examples. This phenomenon is a consequence of the curse of dimensionality, stating that the database-size should grow exponentially with the patch-size to ensure proper matches. This explains the favored choice of small patch-size in most applications. Is there a way to keep the simplicity and work with small patches while getting some of the benefits that large patches provide? In this work we offer such an approach. We propose to concatenate the regular content of a conventional (small) patch with a compact representation of its (large) surroundings - its context. Therefore, with a minor increase of the dimensions (e.g. with additional 10 values to the patch representation), we implicitly/softly describe the information of a large patch. The additional descriptors are computed based on a self-similarity behavior of the patch surrounding. We show that this approach achieves better matches, compared to the use of conventional-size patches, without the need to increase the database-size. Also, the effectiveness of the proposed method is tested on three distinct problems: (i) External natural image denoising, (ii) Depth image super-resolution, and (iii) Motion-compensated frame-rate up-conversion.

##### Abstract (translated by Google)
测量图像中的补丁之间的相似性是各种任务中的基本构建块。当然，补丁大小对匹配质量以及随之而来的应用程序性能有重大影响。在假设我们的补丁数据库被充分采样的情况下，使用较大的补丁（例如21×21）应优先于小补丁（例如7×7）。然而，这种“密集取样”的假设很少是真实的。在大多数情况下，大的补丁无法找到相关的附近例子。这种现象是维度诅咒的结果，说明数据库大小应该随着补丁大小呈指数级增长，以确保正确匹配。这解释了在大多数应用中小尺寸贴片的青睐选择。有没有一种方法来保持简单和小补丁的工作，同时获得一些大补丁提供的好处？在这项工作中，我们提供了这样的方法。我们建议将传统（小）补丁的规则内容与其大（大）环境的紧凑表示 - 其上下文连接起来。因此，在尺寸略微增加的情况下（例如，对补丁表示附加10个值），我们隐式/软性地描述大补丁的信息。附加描述符是基于补丁周围的自相似行为计算的。我们表明，与使用传统大小的补丁相比，这种方法实现了更好的匹配，而不需要增加数据库大小。此外，该方法的有效性进行了三个不同的问题进行测试：（一）外部自然图像去噪，（二）深度图像超分辨率，和（三）运动补偿帧率上转换。

##### URL
[https://arxiv.org/abs/1603.06812](https://arxiv.org/abs/1603.06812)

##### PDF
[https://arxiv.org/pdf/1603.06812](https://arxiv.org/pdf/1603.06812)


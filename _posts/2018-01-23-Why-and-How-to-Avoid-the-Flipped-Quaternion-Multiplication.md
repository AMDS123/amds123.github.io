---
layout: post
title: "Why and How to Avoid the Flipped Quaternion Multiplication"
date: 2018-01-23 10:50:58
categories: arXiv_RO
tags: arXiv_RO
author: Hannes Sommer, Igor Gilitschenski, Michael Bloesch, Stephan M. Weiss, Roland Siegwart, Juan Nieto
mathjax: true
---

* content
{:toc}

##### Abstract
Over the last decades quaternions have become a crucial and very successful tool for attitude representation in robotics and aerospace. However, there is a major problem that is continuously causing trouble in practice when it comes to exchanging formulas or implementations: there are two quaternion multiplications in common use, Hamilton's original multiplication and its flipped version, which is often associated with NASA's Jet Propulsion Laboratory. We believe that this particular issue is completely avoidable and only exists today due to a lack of understanding. This paper explains the underlying problem for the popular passive world to body usage of rotation quaternions, and derives an alternative solution compatible with Hamilton's multiplication. Furthermore, it argues for entirely discontinuing the flipped multiplication. Additionally, it provides recipes for efficiently detecting relevant conventions and migrating formulas or algorithms between them.

##### Abstract (translated by Google)
在过去的几十年中，四元数已经成为机器人和航空航天中态度表示的一个非常重要和非常成功的工具。然而，在交换公式或实现方面，存在一个不断在实践中引起麻烦的重大问题：通常使用两个四元数乘法，汉密尔顿的原始乘法和翻转版本，通常与NASA的喷气推进实验室有关。我们认为这个问题是完全可以避免的，只是由于缺乏了解才存在。本文解释了流行被动世界对于旋转四元数的身体使用的潜在问题，并推导了一个与Hamilton乘法相容的替代解。此外，它认为完全停止翻转乘法。此外，它还提供了用于有效检测相关约定和迁移它们之间的公式或算法的配方。

##### URL
[http://arxiv.org/abs/1801.07478](http://arxiv.org/abs/1801.07478)

##### PDF
[http://arxiv.org/pdf/1801.07478](http://arxiv.org/pdf/1801.07478)


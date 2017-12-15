---
layout: post
title: "Adaptive Objectness for Object Tracking"
date: 2015-01-05 16:24:37
categories: arXiv_CV
tags: arXiv_CV Knowledge Tracking Object_Tracking
author: Pengpeng Liang, Chunyuan Liao, Xue Mei, Haibin Ling
mathjax: true
---

* content
{:toc}

##### Abstract
Object tracking is a long standing problem in vision. While great efforts have been spent to improve tracking performance, a simple yet reliable prior knowledge is left unexploited: the target object in tracking must be an object other than non-object. The recently proposed and popularized objectness measure provides a natural way to model such prior in visual tracking. Thus motivated, in this paper we propose to adapt objectness for visual object tracking. Instead of directly applying an existing objectness measure that is generic and handles various objects and environments, we adapt it to be compatible to the specific tracking sequence and object. More specifically, we use the newly proposed BING objectness as the base, and then train an object-adaptive objectness for each tracking task. The training is implemented by using an adaptive support vector machine that integrates information from the specific tracking target into the BING measure. We emphasize that the benefit of the proposed adaptive objectness, named ADOBING, is generic. To show this, we combine ADOBING with seven top performed trackers in recent evaluations. We run the ADOBING-enhanced trackers with their base trackers on two popular benchmarks, the CVPR2013 benchmark (50 sequences) and the Princeton Tracking Benchmark (100 sequences). On both benchmarks, our methods not only consistently improve the base trackers, but also achieve the best known performances. Noting that the way we integrate objectness in visual tracking is generic and straightforward, we expect even more improvement by using tracker-specific objectness.

##### Abstract (translated by Google)
对象跟踪是视觉中一个长期存在的问题。尽管已经花费了大量的精力来提高跟踪性能，但一个简单但可靠的先验知识仍然没有被利用：跟踪中的目标对象必须是非对象以外的对象。最近提出的和普及的对象度量提供了一种自然的方式来模拟这种先验的视觉跟踪。因此，在本文中，我们提出为视觉对象跟踪调整对象。我们不是直接应用现有的通用对象度量来处理各种对象和环境，而是将其调整为与具体的跟踪序列和对象兼容。更具体地说，我们使用新提出的BING对象作为基础，然后为每个跟踪任务训练一个对象自适应对象。通过使用自适应支持向量机来实现训练，该自适应支持向量机将来自特定跟踪目标的信息集成到BING量度中。我们强调所提出的自适应对象的好处，即ADOBING，是通用的。为了展示这一点，我们将ADOBING与最近评估的七个顶级执行跟踪器结合在一起。我们在两个流行的基准，即CVPR2013基准（50个序列）和普林斯顿跟踪基准（100个序列）上运行ADOBING增强型跟踪器和基本跟踪器。在这两个基准上，我们的方法不仅不断地改进基础跟踪器，而且还获得最出名的性能。注意到我们在视觉跟踪中整合对象的方式是通用和直接的，我们期望通过使用跟踪器特定的对象来获得更多的改进。

##### URL
[https://arxiv.org/abs/1501.00909](https://arxiv.org/abs/1501.00909)

##### PDF
[https://arxiv.org/pdf/1501.00909](https://arxiv.org/pdf/1501.00909)


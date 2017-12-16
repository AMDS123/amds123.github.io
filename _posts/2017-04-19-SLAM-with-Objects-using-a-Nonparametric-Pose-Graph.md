---
layout: post
title: "SLAM with Objects using a Nonparametric Pose Graph"
date: 2017-04-19 23:54:57
categories: arXiv_CV
tags: arXiv_CV Object_Detection Detection SLAM
author: Beipeng Mu, Shih-Yuan Liu, Liam Paull, John Leonard, Jonathan How
mathjax: true
---

* content
{:toc}

##### Abstract
Mapping and self-localization in unknown environments are fundamental capabilities in many robotic applications. These tasks typically involve the identification of objects as unique features or landmarks, which requires the objects both to be detected and then assigned a unique identifier that can be maintained when viewed from different perspectives and in different images. The \textit{data association} and \textit{simultaneous localization and mapping} (SLAM) problems are, individually, well-studied in the literature. But these two problems are inherently tightly coupled, and that has not been well-addressed. Without accurate SLAM, possible data associations are combinatorial and become intractable easily. Without accurate data association, the error of SLAM algorithms diverge easily. This paper proposes a novel nonparametric pose graph that models data association and SLAM in a single framework. An algorithm is further introduced to alternate between inferring data association and performing SLAM. Experimental results show that our approach has the new capability of associating object detections and localizing objects at the same time, leading to significantly better performance on both the data association and SLAM problems than achieved by considering only one and ignoring imperfections in the other.

##### Abstract (translated by Google)
在未知环境中的映射和自我定位是许多机器人应用程序的基本功能。这些任务通常涉及将对象识别为独特的特征或地标，这要求对象都被检测到，然后分配唯一的标识符，当从不同的角度和不同的图像观察时，可以保持该标识符。在文献中单独研究了\ textit {data association}和\ textit {simultaneous localization and mapping}（SLAM）问题。但这两个问题本质上是紧密结合的，这个问题还没有得到很好的解决。没有准确的SLAM，可能的数据关联是组合的，并且容易变得难以处理。没有准确的数据关联，SLAM算法的误差就容易发生偏差。本文提出了一种新的非参数姿态图，在单个框架中模拟数据关联和SLAM。进一步介绍一种算法来推断数据关联和执行SLAM之间的交替。实验结果表明，我们的方法同时具有将对象检测与对象相关联的新功能，从而使数据关联和SLAM问题的性能明显优于仅考虑一个而忽略不完善的性能。

##### URL
[https://arxiv.org/abs/1704.05959](https://arxiv.org/abs/1704.05959)

##### PDF
[https://arxiv.org/pdf/1704.05959](https://arxiv.org/pdf/1704.05959)


---
layout: post
title: "CoMaL Tracking: Tracking Points at the Object Boundaries"
date: 2017-06-07 18:38:05
categories: arXiv_CV
tags: arXiv_CV Tracking Detection
author: Santhosh K. Ramakrishnan, Swarna Kamlam Ravindran, Anurag Mittal
mathjax: true
---

* content
{:toc}

##### Abstract
Traditional point tracking algorithms such as the KLT use local 2D information aggregation for feature detection and tracking, due to which their performance degrades at the object boundaries that separate multiple objects. Recently, CoMaL Features have been proposed that handle such a case. However, they proposed a simple tracking framework where the points are re-detected in each frame and matched. This is inefficient and may also lose many points that are not re-detected in the next frame. We propose a novel tracking algorithm to accurately and efficiently track CoMaL points. For this, the level line segment associated with the CoMaL points is matched to MSER segments in the next frame using shape-based matching and the matches are further filtered using texture-based matching. Experiments show improvements over a simple re-detect-and-match framework as well as KLT in terms of speed/accuracy on different real-world applications, especially at the object boundaries.

##### Abstract (translated by Google)
传统的点跟踪算法（如KLT）使用局部2D信息聚合进行特征检测和跟踪，因此在分离多个对象的对象边界上其性能下降。最近，CoMaL特性已经被提出来处理这种情况。但是，他们提出了一个简单的跟踪框架，在每个框架中重新检测点并进行匹配。这是低效率的，并且可能会丢失许多在下一帧中不被重新检测的点。我们提出了一种新颖的跟踪算法来准确高效地跟踪CoMaL点。为此，使用基于形状的匹配将与CoMaL点相关联的水平线段与下一帧中的MSER段匹配，并使用基于纹理的匹配对匹配进行进一步过滤。实验表明，在不同的真实世界的应用中，特别是在对象边界上，对于简单的重新检测和匹配框架以及KLT在速度/准确性方面的改进。

##### URL
[https://arxiv.org/abs/1706.02331](https://arxiv.org/abs/1706.02331)

##### PDF
[https://arxiv.org/pdf/1706.02331](https://arxiv.org/pdf/1706.02331)


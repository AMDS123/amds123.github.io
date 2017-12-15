---
layout: post
title: "Sequential Optimization for Efficient High-Quality Object Proposal Generation"
date: 2017-05-22 17:23:07
categories: arXiv_CV
tags: arXiv_CV Object_Detection Optimization Detection
author: Ziming Zhang, Yun Liu, Xi Chen, Yanjun Zhu, Ming-Ming Cheng, Venkatesh Saligrama, Philip H.S. Torr
mathjax: true
---

* content
{:toc}

##### Abstract
We are motivated by the need for a generic object proposal generation algorithm which achieves good balance between object detection recall, proposal localization quality and computational efficiency. We propose a novel object proposal algorithm, BING++, which inherits the virtue of good computational efficiency of BING but significantly improves its proposal localization quality. At high level we formulate the problem of object proposal generation from a novel probabilistic perspective, based on which our BING++ manages to improve the localization quality by employing edges and segments to estimate object boundaries and update the proposals sequentially. We propose learning the parameters efficiently by searching for approximate solutions in a quantized parameter space for complexity reduction. We demonstrate the generalization of BING++ with the same fixed parameters across different object classes and datasets. Empirically our BING++ can run at half speed of BING on CPU, but significantly improve the localization quality by 18.5% and 16.7% on both VOC2007 and Microhsoft COCO datasets, respectively. Compared with other state-of-the-art approaches, BING++ can achieve comparable performance, but run significantly faster.

##### Abstract (translated by Google)
我们的动机是需要一个通用的对象提议生成算法，实现对象检测召回，提议定位质量和计算效率之间的良好平衡。我们提出了一种新的对象提议算法BING ++，该算法继承了BING计算效率高的优点，但是提高了提议的定位质量。在高层次上，我们从一个新颖的概率角度出发提出了对象建议的生成问题，在此基础上，我们的BING ++通过使用边和段来估计对象边界，并依次更新提议，从而提高了定位的质量。我们提出通过在量化参数空间中搜索近似解来降低复杂度来有效地学习参数。我们用不同的对象类和数据集的固定参数来展示BING ++的泛化。实际上，我们的BING ++可以在CPU上以BING的一半速度运行，但是在VOC2007和Microhsoft COCO数据集上的定位质量分别显着提高了18.5％和16.7％。与其他最先进的方法相比，BING ++可以达到相当的性能，但运行速度要快得多。

##### URL
[https://arxiv.org/abs/1511.04511](https://arxiv.org/abs/1511.04511)

##### PDF
[https://arxiv.org/pdf/1511.04511](https://arxiv.org/pdf/1511.04511)


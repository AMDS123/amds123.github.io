---
layout: post
title: "OpenCL-accelerated object classification in video streams using Spatial Pooler of Hierarchical Temporal Memory"
date: 2016-08-05 18:25:21
categories: arXiv_CV
tags: arXiv_CV Classification Recognition
author: Maciej Wielgosz, Marcin Pietroń
mathjax: true
---

* content
{:toc}

##### Abstract
We present a method to classify objects in video streams using a brain-inspired Hierarchical Temporal Memory (HTM) algorithm. Object classification is a challenging task where humans still significantly outperform machine learning algorithms due to their unique capabilities. We have implemented a system which achieves very promising performance in terms of recognition accuracy. Unfortunately, conducting more advanced experiments is very computationally demanding; some of the trials run on a standard CPU may take as long as several days for 960x540 video streams frames. Therefore we have decided to accelerate selected parts of the system using OpenCL. In particular, we seek to determine to what extent porting selected and computationally demanding parts of a core may speed up calculations. The classification accuracy of the system was examined through a series of experiments and the performance was given in terms of F1 score as a function of the number of columns, synapses, $min\_overlap$ and $winners\_set\_size$. The system achieves the highest F1 score of 0.95 and 0.91 for $min\_overlap=4$ and 256 synapses, respectively. We have also conduced a series of experiments with different hardware setups and measured CPU/GPU acceleration. The best kernel speed-up of 632x and 207x was reached for 256 synapses and 1024 columns. However, overall acceleration including transfer time was significantly lower and amounted to 6.5x and 3.2x for the same setup.

##### Abstract (translated by Google)
我们提出了一种使用大脑启发的分层时间记忆（HTM）算法对视频流中的对象进行分类的方法。对象分类是一项具有挑战性的任务，由于其独特的功能，人类的机器学习算法仍然具有显着的优势。我们已经实现了一个系统，在识别精度方面取得了非常有希望的性能。不幸的是，进行更高级的实验对计算量要求很高。对于960x540视频流帧，一些在标准CPU上运行的试验可能需要几天的时间。因此，我们决定使用OpenCL加速系统的选定部分。特别是，我们试图确定在何种程度上移植核心的选定部分和计算需求部分可以加速计算。通过一系列实验检查系统的分类准确性，并以F1分数作为列数，突触$ min \ _overlap $和$ winners \ _set \ _size $的函数给出性能。系统分别以$ min \ _overlap = 4 $和256个突触获得最高的F1分数为0.95和0.91。我们还进行了一系列不同硬件设置的实验，并测量了CPU / GPU加速。 256突触和1024列达到了632x和207x的最佳内核加速。然而，包括传输时间的整体加速度显着较低，并且在相同的设置下为6.5倍和3.2倍。

##### URL
[https://arxiv.org/abs/1608.01966](https://arxiv.org/abs/1608.01966)

##### PDF
[https://arxiv.org/pdf/1608.01966](https://arxiv.org/pdf/1608.01966)


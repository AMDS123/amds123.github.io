---
layout: post
title: "SECS: Efficient Deep Stream Processing via Class Skew Dichotomy"
date: 2018-09-07 18:03:47
categories: arXiv_AI
tags: arXiv_AI CNN Optimization Classification
author: Boyuan Feng, Kun Wan, Shu Yang, Yufei Ding
mathjax: true
---

* content
{:toc}

##### Abstract
Despite that accelerating convolutional neural network (CNN) receives an increasing research focus, the save on resource consumption always comes with a decrease in accuracy. To both increase accuracy and decrease resource consumption, we explore an environment information, called class skew, which is easily available and exists widely in daily life. Since the class skew may switch as time goes, we bring up probability layer to utilize class skew without any overhead during the runtime. Further, we observe class skew dichotomy that some class skew may appear frequently in the future, called hot class skew, and others will never appear again or appear seldom, called cold class skew. Inspired by techniques from source code optimization, two modes, i.e., interpretation and compilation, are proposed. The interpretation mode pursues efficient adaption during runtime for cold class skew and the compilation mode aggressively optimize on hot ones for more efficient deployment in the future. Aggressive optimization is processed by class-specific pruning and provides extra benefit. Finally, we design a systematic framework, SECS, to dynamically detect class skew, processing interpretation and compilation, as well as select the most accurate architectures under the runtime resource budget. Extensive evaluations show that SECS can realize end-to-end classification speedups by a factor of 3x to 11x relative to state-of-the-art convolutional neural networks, at a higher accuracy.

##### Abstract (translated by Google)
尽管加速卷积神经网络（CNN）受到越来越多的研究关注，但资源消耗的节省总是伴随着准确性的降低。为了提高准确性并减少资源消耗，我们探索了一种称为类偏斜的环境信息，这种信息很容易获得并且在日常生活中广泛存在。由于类偏斜可能随着时间的推移而切换，因此我们提出概率层以利用类偏斜而不会在运行时产生任何开销。此外，我们观察到类偏斜二分法，将来可能会出现一些类偏斜，称为热类偏斜，而其他类型将永远不再出现或很少出现，称为冷类偏斜。受源代码优化技术的启发，提出了两种模式，即解释和编译。解释模式在运行时期间追求冷等级偏差的有效适应，并且编译模式在热点上进行积极优化以便在将来更有效地部署。积极优化由特定于类的修剪处理，并提供额外的好处。最后，我们设计了一个系统框架SECS，以动态检测类偏斜，处理解释和编译，以及在运行时资源预算下选择最准确的体系结构。广泛的评估表明，相对于现有技术的卷积神经网络，SECS可以以更高的准确度实现端到端分类加速3倍至11倍。

##### URL
[https://arxiv.org/abs/1809.06691](https://arxiv.org/abs/1809.06691)

##### PDF
[https://arxiv.org/pdf/1809.06691](https://arxiv.org/pdf/1809.06691)


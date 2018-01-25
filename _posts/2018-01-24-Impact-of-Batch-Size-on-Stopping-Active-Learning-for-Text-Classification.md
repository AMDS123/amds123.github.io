---
layout: post
title: "Impact of Batch Size on Stopping Active Learning for Text Classification"
date: 2018-01-24 07:47:05
categories: arXiv_CL
tags: arXiv_CL Text_Classification Classification
author: Garrett Beatty, Ethan Kochis, Michael Bloodgood
mathjax: true
---

* content
{:toc}

##### Abstract
When using active learning, smaller batch sizes are typically more efficient from a learning efficiency perspective. However, in practice due to speed and human annotator considerations, the use of larger batch sizes is necessary. While past work has shown that larger batch sizes decrease learning efficiency from a learning curve perspective, it remains an open question how batch size impacts methods for stopping active learning. We find that large batch sizes degrade the performance of a leading stopping method over and above the degradation that results from reduced learning efficiency. We analyze this degradation and find that it can be mitigated by changing the window size parameter of how many past iterations of learning are taken into account when making the stopping decision. We find that when using larger batch sizes, stopping methods are more effective when smaller window sizes are used.

##### Abstract (translated by Google)
使用主动学习时，从学习效率的角度来看，较小的批量通常更有效率。但是，实际上由于速度和人类注释器的考虑，使用较大的批量是必要的。虽然过去的工作表明，从学习曲线的角度来看，较大的批量大小会降低学习效率，但批量大小如何影响停止主动学习的方法仍然是个悬而未决的问题。我们发现，大批量大小降低了领先停止方法的性能，超过了由于学习效率降低而导致的降级。我们分析这种退化，并发现它可以通过改变窗口大小参数来减少多少次过去的迭代学习被考虑在做出停止决定时。我们发现，当使用较大的批量大小时，使用较小的窗口大小时，停止方法更有效。

##### URL
[http://arxiv.org/abs/1801.07887](http://arxiv.org/abs/1801.07887)

##### PDF
[http://arxiv.org/pdf/1801.07887](http://arxiv.org/pdf/1801.07887)


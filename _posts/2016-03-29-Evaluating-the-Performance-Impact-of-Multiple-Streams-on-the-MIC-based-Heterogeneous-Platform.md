---
layout: post
title: "Evaluating the Performance Impact of Multiple Streams on the MIC-based Heterogeneous Platform"
date: 2016-03-29 03:01:06
categories: arXiv_CV
tags: arXiv_CV
author: Zhaokui Li, Jianbin Fang, Tao Tang, Xuhao Chen, Cheng Chen, Canqun Yang
mathjax: true
---

* content
{:toc}

##### Abstract
Using \textit{multiple streams} can improve the overall system performance by mitigating the data transfer overhead on heterogeneous systems. Prior work focuses a lot on GPUs but little is known about the performance impact on (Intel Xeon) Phi. In this work, we apply multiple streams into six real-world applications on Phi. We then systematically evaluate the performance benefits of using multiple streams. The evaluation work is performed at two levels: the microbenchmarking level and the real-world application level. Our experimental results at the microbenchmark level show that data transfers and kernel execution can be overlapped on Phi, while data transfers in both directions are performed in a serial manner. At the real-world application level, we show that both overlappable and non-overlappable applications can benefit from using multiple streams (with an performance improvement of up to 24\%). We also quantify how task granularity and resource granularity impact the overall performance. Finally, we present a set of heuristics to reduce the search space when determining a proper task granularity and resource granularity. To conclude, our evaluation work provides lots of insights for runtime and architecture designers when using multiple streams on Phi.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1603.08619](https://arxiv.org/abs/1603.08619)

##### PDF
[https://arxiv.org/pdf/1603.08619](https://arxiv.org/pdf/1603.08619)


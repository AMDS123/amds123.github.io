---
layout: post
title: "ENCORE: Ensemble Learning using Convolution Neural Machine Translation for Automatic Program Repair"
date: 2019-06-20 15:25:16
categories: arXiv_CL
tags: arXiv_CL CNN NMT RNN
author: Thibaud Lutellier, Lawrence Pang, Viet Hung Pham, Moshi Wei, Lin Tan
mathjax: true
---

* content
{:toc}

##### Abstract
Automated generate-and-validate (G&V) program repair techniques typically rely on hard-coded rules, only fix bugs following specific patterns, and are hard to adapt to different programming languages. We propose ENCORE, a new G&V technique, which uses ensemble learning on convolutional neural machine translation (NMT) models to automatically fix bugs in multiple programming languages. We take advantage of the randomness in hyper-parameter tuning to build multiple models that fix different bugs and combine them using ensemble learning. This new convolutional NMT approach outperforms the standard long short-term memory (LSTM) approach used in previous work, as it better captures both local and long-distance connections between tokens. Our evaluation on two popular benchmarks, Defects4J and QuixBugs, shows that ENCORE fixed 42 bugs, including 16 that have not been fixed by existing techniques. In addition, ENCORE is the first G&V repair technique to be applied to four popular programming languages (Java, C++, Python, and JavaScript), fixing a total of 67 bugs across five benchmarks.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1906.08691](https://arxiv.org/abs/1906.08691)

##### PDF
[https://arxiv.org/pdf/1906.08691](https://arxiv.org/pdf/1906.08691)


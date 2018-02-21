---
layout: post
title: "Learning Hidden Markov Models from Pairwise Co-occurrences with Applications to Topic Modeling"
date: 2018-02-19 22:33:56
categories: arXiv_CL
tags: arXiv_CL
author: Kejun Huang, Xiao Fu, Nicholas D. Sidiropoulos
mathjax: true
---

* content
{:toc}

##### Abstract
We present a new algorithm for identifying the transition and emission probabilities of a hidden Markov model (HMM) from the emitted data. Expectation-maximization becomes computationally prohibitive for long observation records, which are often required for identification. The new algorithm is particularly suitable for cases where the available sample size is large enough to accurately estimate second-order output probabilities, but not higher-order ones. We show that if one is only able to obtain a reliable estimate of the pairwise co-occurrence probabilities of the emissions, it is still possible to uniquely identify the HMM if the emission probability is \emph{sufficiently scattered}. We apply our method to hidden topic Markov modeling, and demonstrate that we can learn topics with higher quality if documents are modeled as observations of HMMs sharing the same emission (topic) probability, compared to the simple but widely used bag-of-words model.

##### Abstract (translated by Google)
我们提出了一种新的算法，用于从发射的数据中识别隐马尔可夫模型（HMM）的过渡和发射概率。对于长期观察记录来说，期望最大化对于识别通常是必需的，因此在计算上变得不可行。新算法特别适用于可用样本量足够大以准确估计二阶输出概率的情况，但不适用于高阶输出概率。我们表明，如果只能获得发射的成对共现概率的可靠估计，则如果发射概率是\ emph {足够分散}，则仍然可以唯一地识别HMM。我们将我们的方法应用于隐藏话题马尔可夫模型，并且证明如果文档被建模为共享相同发射（话题）概率的HMM的观察结果，那么与简单但广泛使用的书包模型相比，我们可以更高质量地学习话题。

##### URL
[http://arxiv.org/abs/1802.06894](http://arxiv.org/abs/1802.06894)

##### PDF
[http://arxiv.org/pdf/1802.06894](http://arxiv.org/pdf/1802.06894)


---
layout: post
title: "The Critical Radius in Sampling-based Motion Planning"
date: 2018-02-04 15:46:18
categories: arXiv_RO
tags: arXiv_RO
author: Kiril Solovey, Michal Kleinbort
mathjax: true
---

* content
{:toc}

##### Abstract
We develop a new analysis of sampling-based motion planning with uniform random sampling, which significantly improves upon the celebrated result of Karaman and Frazzoli (2011) and subsequent work. Particularly, we prove the existence of a critical connection radius proportional to $\Theta(n^{-1/d})$ for $n$ samples and $d$ dimensions: Below this value the planner is guaranteed to fail (similarly shown by the aforementioned work, ibid.). More importantly, for larger radius values the planner is asymptotically (near-)optimal (AO). Furthermore, our analysis yields an explicit lower bound of $1-O(n^{-1})$ on the probability of success. A practical implication of our work is that AO is achieved when each sample is connected to only $\Theta(1)$ neighbors. This is in stark contrast to previous work which requires $\Theta(\log n)$ connections, that are induced by a radius of order $\left(\frac{\log n}{n}\right)^{1/d}$. Our analysis is not restricted to PRM and applies to a variety of "PRM-based" planners, including RGG, FMT$^*$ and BTT. Continuum percolation plays an important role in our proofs. Lastly, we develop similar theory for the aforementioned planners when constructed with deterministic samples, which are then sparsified in a randomized fashion. We believe that this new model, and its analysis, is interesting in its own right.

##### Abstract (translated by Google)
我们采用统一随机抽样的方法，开展了基于抽样运动规划的新分析，这对Karaman和Frazzoli（2011年）以及后续工作的成果显着提高。特别是，我们证明了对于$ n $ samples和$ d $维度存在一个与$ \ Theta（n ^ { -  1 / d}）$成比例的关键连接半径：在这个值的下面，规划器保证失败由上述工作，同上）。更重要的是，对于较大的半径值，规划器渐近（近似）最优（AO）。此外，我们的分析在成功概率上产生了$ 1-O（n ^ { -  1}）$的显式下限。我们工作的一个实际意义是，当每个样本仅连接到$ \ Theta（1）$ neighbours时，AO就可以实现。这与以前需要$ \ Theta（\ log n）$个连接的工作形成了鲜明的对比，这个连接是由$ \ left（\ frac {\ log n} {n} \ right）^ {1 / d} $。我们的分析不限于PRM，而是适用于各种“基于PRM的”规划者，包括RGG，FMT $ ^ * $和BTT。连续渗流在我们的证明中起着重要的作用。最后，我们在用确定性样本构建上述规划人员时，发展了类似的理论，然后以随机方式进行稀疏化。我们相信这个新模式及其分析本身就很有意思。

##### URL
[http://arxiv.org/abs/1709.06290](http://arxiv.org/abs/1709.06290)

##### PDF
[http://arxiv.org/pdf/1709.06290](http://arxiv.org/pdf/1709.06290)


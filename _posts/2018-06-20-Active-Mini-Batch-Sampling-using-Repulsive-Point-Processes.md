---
layout: post
title: "Active Mini-Batch Sampling using Repulsive Point Processes"
date: 2018-06-20 15:12:20
categories: arXiv_AI
tags: arXiv_AI Gradient_Descent
author: Cheng Zhang, Cengiz &#xd6;ztireli, Stephan Mandt, Giampiero Salvi
mathjax: true
---

* content
{:toc}

##### Abstract
The convergence speed of stochastic gradient descent (SGD) can be improved by actively selecting mini-batches. We explore sampling schemes where similar data points are less likely to be selected in the same mini-batch. In particular, we prove that such repulsive sampling schemes lowers the variance of the gradient estimator. This generalizes recent work on using Determinantal Point Processes (DPPs) for mini-batch diversification (Zhang et al., 2017) to the broader class of repulsive point processes. We first show that the phenomenon of variance reduction by diversified sampling generalizes in particular to non-stationary point processes. We then show that other point processes may be computationally much more efficient than DPPs. In particular, we propose and investigate Poisson Disk sampling---frequently encountered in the computer graphics community---for this task. We show empirically that our approach improves over standard SGD both in terms of convergence speed as well as final model performance.

##### Abstract (translated by Google)
通过主动选择小批量可以提高随机梯度下降（SGD）的收敛速度。我们探索采样方案，在相同的小批量中不太可能选择相似的数据点。特别是，我们证明这种排斥抽样方案降低了梯度估计器的方差。这推广了最近关于将微量分批多样化（Zhang等人，2017）的决定点过程（DPPs）用于更广泛的排斥点过程的工作。我们首先表明，多样化抽样的方差减少现象特别推广到非平稳点过程。然后我们证明其他点过程在计算上可能比DPP更有效。特别是，我们提出并研究Poisson Disk采样 - 在计算机图形学界经常遇到 - 用于此任务。我们凭经验证明，我们的方法在收敛速度以及最终模型性能方面均优于标准SGD。

##### URL
[http://arxiv.org/abs/1804.02772](http://arxiv.org/abs/1804.02772)

##### PDF
[http://arxiv.org/pdf/1804.02772](http://arxiv.org/pdf/1804.02772)


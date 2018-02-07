---
layout: post
title: "Towards Shockingly Easy Structured Classification: A Search-based Probabilistic Online Learning Framework"
date: 2018-02-06 02:20:57
categories: arXiv_AI
tags: arXiv_AI Optimization Classification
author: Xu Sun
mathjax: true
---

* content
{:toc}

##### Abstract
There are two major approaches for structured classification. One is the probabilistic gradient-based methods such as conditional random fields (CRF), which has high accuracy but with drawbacks: slow training, and no support of search-based optimization (which is important in many cases). The other one is the search-based learning methods such as perceptrons and margin infused relaxed algorithm (MIRA), which have fast training but also with drawbacks: low accuracy, no probabilistic information, and non-convergence in real-world tasks. We propose a novel and "shockingly easy" solution, a search-based probabilistic online learning method, to address most of those issues. This method searches the output candidates, derives probabilities, and conduct efficient online learning. We show that this method is with fast training, support search-based optimization, very easy to implement, with top accuracy, with probabilities, and with theoretical guarantees of convergence. Experiments on well-known tasks show that our method has better accuracy than CRF and almost as fast training speed as perceptron and MIRA. Results also show that SAPO can easily beat the state-of-the-art systems on those highly-competitive tasks, achieving record-breaking accuracies. The codes can be found at https://github.com/lancopku

##### Abstract (translated by Google)
有两种主要的结构化分类方法。一种是基于概率梯度的方法，如条件随机场（CRF），具有较高的准确率，但存在缺点：训练速度慢，不支持基于搜索的优化（这在许多情况下非常重要）。另一种是基于搜索的学习方法，如感知和边缘融合宽松算法（MIRA），其训练速度快，但也存在缺点：精度低，没有概率信息，在现实任务中不收敛。我们提出了一种新颖的“令人震惊的简单”解决方案，一种基于搜索的概率在线学习方法，以解决大部分这些问题。这种方法搜索输出候选人，推导出概率，并进行有效的在线学习。我们证明这种方法具有快速训练，支持基于搜索的优化，非常容易实现，具有最高的准确性，可能性以及收敛性的理论保证。众所周知的任务实验表明，我们的方法比CRF具有更好的准确性，几乎和感知器和MIRA一样快的训练速度。结果还表明，SAPO可以轻松击败那些高度竞争的任务的最先进的系统，达到破记录的准确性。代码可以在https://github.com/lancopku找到

##### URL
[http://arxiv.org/abs/1503.08381](http://arxiv.org/abs/1503.08381)

##### PDF
[http://arxiv.org/pdf/1503.08381](http://arxiv.org/pdf/1503.08381)


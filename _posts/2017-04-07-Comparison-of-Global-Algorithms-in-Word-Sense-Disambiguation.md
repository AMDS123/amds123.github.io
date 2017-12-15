---
layout: post
title: "Comparison of Global Algorithms in Word Sense Disambiguation"
date: 2017-04-07 17:04:51
categories: arXiv_CL
tags: arXiv_CL
author: Loïc Vial, Andon Tchechmedjiev, Didier Schwab
mathjax: true
---

* content
{:toc}

##### Abstract
This article compares four probabilistic algorithms (global algorithms) for Word Sense Disambiguation (WSD) in terms of the number of scorer calls (local algo- rithm) and the F1 score as determined by a gold-standard scorer. Two algorithms come from the state of the art, a Simulated Annealing Algorithm (SAA) and a Genetic Algorithm (GA) as well as two algorithms that we first adapt from WSD that are state of the art probabilistic search algorithms, namely a Cuckoo search algorithm (CSA) and a Bat Search algorithm (BS). As WSD requires to evaluate exponentially many word sense combinations (with branching factors of up to 6 or more), probabilistic algorithms allow to find approximate solution in a tractable time by sampling the search space. We find that CSA, GA and SA all eventually converge to similar results (0.98 F1 score), but CSA gets there faster (in fewer scorer calls) and reaches up to 0.95 F1 before SA in fewer scorer calls. In BA a strict convergence criterion prevents it from reaching above 0.89 F1.

##### Abstract (translated by Google)
本文比较了四个概率算法（全局算法）的Word Sense Disambiguation（WSD），根据得分者调用次数（本地算法）和F1得分由黄金标准得分者确定。两种算法来自现有技术，模拟退火算法（SAA）和遗传算法（GA），以及我们首先从WSD自适应的概率搜索算法，即杜鹃搜索算法（CSA）和蝙蝠搜索算法（BS）。由于WSD需要评估指数级的许多单词意义组合（具有多达6个或更多的分支因子），所以概率算法允许通过对搜索空间进行采样来在易处理时间内找到近似解。我们发现CSA，GA和SA最终都趋于相似的结果（0.98 F1得分），但是CSA在那里得到更快的得分（更少的得分手），而在SA之前达到0.95 F1的得分手就更少了。在BA中，一个严格的收敛标准阻止它达到0.89 F1以上。

##### URL
[https://arxiv.org/abs/1704.02293](https://arxiv.org/abs/1704.02293)

##### PDF
[https://arxiv.org/pdf/1704.02293](https://arxiv.org/pdf/1704.02293)


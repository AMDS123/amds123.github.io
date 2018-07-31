---
layout: post
title: "Clause Vivification by Unit Propagation in CDCL SAT Solvers"
date: 2018-07-29 14:05:55
categories: arXiv_AI
tags: arXiv_AI
author: Chu-Min Li, Fan Xiao, Mao Luo, Felip Many&#xe0;, Zhipeng L&#xfc;, Yu Li
mathjax: true
---

* content
{:toc}

##### Abstract
Original and learnt clauses in Conflict-Driven Clause Learning (CDCL) SAT solvers often contain redundant literals. This may have a negative impact on performance because redundant literals may deteriorate both the effectiveness of Boolean constraint propagation and the quality of subsequent learnt clauses. To overcome this drawback, we propose a clause vivification approach that eliminates redundant literals by applying unit propagation. The proposed clause vivification is activated before the SAT solver triggers some selected restarts, and only affects a subset of original and learnt clauses, which are considered to be more relevant according to metrics like the literal block distance (LBD). Moreover, we conducted an empirical investigation with instances coming from the hard combinatorial and application categories of recent SAT competitions. The results show that a remarkable number of additional instances are solved when the proposed approach is incorporated into five of the best performing CDCL SAT solvers (Glucose, TC_Glucose, COMiniSatPS, MapleCOMSPS and MapleCOMSPS_LRB). More importantly, the empirical investigation includes an in-depth analysis of the effectiveness of clause vivification. It is worth mentioning that one of the SAT solvers described here was ranked first in the main track of SAT Competition 2017 thanks to the incorporation of the proposed clause vivification. That solver was further improved in this paper and won the bronze medal in the main track of SAT Competition 2018.

##### Abstract (translated by Google)
冲突驱动条款学习（CDCL）SAT求解器中的原始和学习条款通常包含冗余文字。这可能会对性能产生负面影响，因为冗余文字可能会降低布尔约束传播的有效性和后续学习子句的质量。为了克服这个缺点，我们提出了一种子句生成方法，通过应用单元传播来消除冗余文字。在SAT求解器触发一些选定的重启之前激活所提议的子句生存，并且仅影响原始和学习子句的子集，根据诸如文字块距离（LBD）之类的度量，这些子句被认为是更相关的。此外，我们进行了一项实证调查，其中包括最近SAT比赛的硬组合和应用类别。结果表明，当将所提出的方法合并到五个性能最佳的CDCL SAT求解器（葡萄糖，TC_Glucose，COMiniSatPS，MapleCOMSPS和MapleCOMSPS_LRB）中时，解决了大量额外的实例。更重要的是，实证调查包括对条款生存的有效性的深入分析。值得一提的是，由于纳入了提议的条款生存，这里描述的SAT解决方案之一在2017年SAT竞赛的主要赛道中排名第一。该论文得到了进一步的改进，并在2018年SAT比赛的主要赛道上获得了铜牌。

##### URL
[http://arxiv.org/abs/1807.11061](http://arxiv.org/abs/1807.11061)

##### PDF
[http://arxiv.org/pdf/1807.11061](http://arxiv.org/pdf/1807.11061)


---
layout: post
title: "Analysis of Stopping Active Learning based on Stabilizing Predictions"
date: 2015-04-23 20:07:01
categories: arXiv_CL
tags: arXiv_CL Face Prediction Relation
author: Michael Bloodgood, John Grothendieck
mathjax: true
---

* content
{:toc}

##### Abstract
Within the natural language processing (NLP) community, active learning has been widely investigated and applied in order to alleviate the annotation bottleneck faced by developers of new NLP systems and technologies. This paper presents the first theoretical analysis of stopping active learning based on stabilizing predictions (SP). The analysis has revealed three elements that are central to the success of the SP method: (1) bounds on Cohen's Kappa agreement between successively trained models impose bounds on differences in F-measure performance of the models; (2) since the stop set does not have to be labeled, it can be made large in practice, helping to guarantee that the results transfer to previously unseen streams of examples at test/application time; and (3) good (low variance) sample estimates of Kappa between successive models can be obtained. Proofs of relationships between the level of Kappa agreement and the difference in performance between consecutive models are presented. Specifically, if the Kappa agreement between two models exceeds a threshold T (where $T>0$), then the difference in F-measure performance between those models is bounded above by $\frac{4(1-T)}{T}$ in all cases. If precision of the positive conjunction of the models is assumed to be $p$, then the bound can be tightened to $\frac{4(1-T)}{(p+1)T}$.

##### Abstract (translated by Google)
在自然语言处理（NLP）社区中，主动学习已被广​​泛研究和应用，以缓解开发新NLP系统和技术所面临的注释瓶颈。本文提出了基于稳定预测（SP）停止主动学习的第一个理论分析。分析揭示了SP方法成功的三个要素：（1）连续训练模型之间的Cohen Kappa协议的界限强化了模型的F-measure性能差异; （2）由于停止设置不需要标记，所以在实践中可以做得很大，有助于保证结果在测试/应用时转移到以前看不见的例子流; （3）可以获得连续模型之间Kappa的良好（低方差）样本估计。介绍了Kappa协议水平与连续模型性能差异之间关系的证据。具体而言，如果两个模型之间的Kappa协议超过阈值T（其中$ T> 0 $），那么这些模型之间的F测量性能的差异受到以上限制$ \ frac {4（1-T）} {T在所有情况下都是$。如果模型的正联合的精度被假定为$ p $，那么该界限可以被收紧到$ \ frac {4（1-T）} {（p + 1）T} $。

##### URL
[https://arxiv.org/abs/1504.06329](https://arxiv.org/abs/1504.06329)

##### PDF
[https://arxiv.org/pdf/1504.06329](https://arxiv.org/pdf/1504.06329)


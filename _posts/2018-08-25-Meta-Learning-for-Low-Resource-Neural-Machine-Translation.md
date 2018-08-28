---
layout: post
title: "Meta-Learning for Low-Resource Neural Machine Translation"
date: 2018-08-25 15:10:59
categories: arXiv_CL
tags: arXiv_CL Transfer_Learning NMT
author: Jiatao Gu, Yong Wang, Yun Chen, Kyunghyun Cho, Victor O.K. Li
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper, we propose to extend the recently introduced model-agnostic meta-learning algorithm (MAML) for low-resource neural machine translation (NMT). We frame low-resource translation as a meta-learning problem, and we learn to adapt to low-resource languages based on multilingual high-resource language tasks. We use the universal lexical representation~\citep{gu2018universal} to overcome the input-output mismatch across different languages. We evaluate the proposed meta-learning strategy using eighteen European languages (Bg, Cs, Da, De, El, Es, Et, Fr, Hu, It, Lt, Nl, Pl, Pt, Sk, Sl, Sv and Ru) as source tasks and five diverse languages (Ro, Lv, Fi, Tr and Ko) as target tasks. We show that the proposed approach significantly outperforms the multilingual, transfer learning based approach~\citep{zoph2016transfer} and enables us to train a competitive NMT system with only a fraction of training examples. For instance, the proposed approach can achieve as high as 22.04 BLEU on Romanian-English WMT'16 by seeing only 16,000 translated words (~600 parallel sentences).

##### Abstract (translated by Google)
在本文中，我们建议扩展最近引入的模型不可知元学习算法（MAML），用于低资源神经机器翻译（NMT）。我们将低资源翻译构建为元学习问题，并且我们学习基于多语言高资源语言任务来适应低资源语言。我们使用通用词法表示〜\ citep {gu2018universal}来克服不同语言的输入输出不匹配。我们使用十八种欧洲语言（Bg，Cs，Da，De，El，Es，Et，Fr，Hu，It，Lt，Nl，Pl，Pt，Sk，Sl，Sv和Ru）评估所提出的元学习策略。源任务和五种不同的语言（Ro，Lv，Fi，Tr和Ko）作为目标任务。我们表明，所提出的方法明显优于多语言，基于转移学习的方法〜\ citep {zoph2016transfer}，并使我们能够仅使用一小部分训练样例来训练具有竞争力的NMT系统。例如，通过仅查看16,000个翻译单词（约600个并行句子），所提出的方法可以在罗马尼亚语 - 英语WMT'16上实现高达22.04 BLEU。

##### URL
[http://arxiv.org/abs/1808.08437](http://arxiv.org/abs/1808.08437)

##### PDF
[http://arxiv.org/pdf/1808.08437](http://arxiv.org/pdf/1808.08437)


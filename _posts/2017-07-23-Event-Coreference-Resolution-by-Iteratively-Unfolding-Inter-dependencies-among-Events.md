---
layout: post
title: "Event Coreference Resolution by Iteratively Unfolding Inter-dependencies among Events"
date: 2017-07-23 20:49:18
categories: arXiv_CL
tags: arXiv_CL
author: Prafulla Kumar Choubey, Ruihong Huang
mathjax: true
---

* content
{:toc}

##### Abstract
We introduce a novel iterative approach for event coreference resolution that gradually builds event clusters by exploiting inter-dependencies among event mentions within the same chain as well as across event chains. Among event mentions in the same chain, we distinguish within- and cross-document event coreference links by using two distinct pairwise classifiers, trained separately to capture differences in feature distributions of within- and cross-document event clusters. Our event coreference approach alternates between WD and CD clustering and combines arguments from both event clusters after every merge, continuing till no more merge can be made. And then it performs further merging between event chains that are both closely related to a set of other chains of events. Experiments on the ECB+ corpus show that our model outperforms state-of-the-art methods in joint task of WD and CD event coreference resolution.

##### Abstract (translated by Google)
我们引入了一种新颖的事件共因解决方法，通过利用同一链中事件提及和事件链之间的相互依赖来逐步建立事件集群。在同一链中的事件提及中，我们通过使用两个不同的成对分类器来区分事件内部和事件间的相互链接，分别进行训练以捕获内部和跨文档事件集群的特征分布差异。我们的事件共享方法在WD和CD聚类之间交替，并且在每次合并之后将来自两个事件聚类的参数结合起来，直到不能再进行合并。然后它进一步合并与其他一系列事件密切相关的事件链。在ECB +语料库上的实验表明，我们的模型在WD和CD事件共同决议的联合任务中胜过了最先进的方法。

##### URL
[https://arxiv.org/abs/1707.07344](https://arxiv.org/abs/1707.07344)

##### PDF
[https://arxiv.org/pdf/1707.07344](https://arxiv.org/pdf/1707.07344)


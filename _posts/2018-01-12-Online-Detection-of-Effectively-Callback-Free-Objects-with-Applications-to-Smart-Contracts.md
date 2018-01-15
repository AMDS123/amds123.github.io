---
layout: post
title: "Online Detection of Effectively Callback Free Objects with Applications to Smart Contracts"
date: 2018-01-12 01:33:42
categories: arXiv_CV
tags: arXiv_CV Detection
author: Shelly Grossman, Ittai Abraham, Guy Golan-Gueta, Yan Michalevsky, Noam Rinetzky, Mooly Sagiv, Yoni Zohar
mathjax: true
---

* content
{:toc}

##### Abstract
Callbacks are essential in many programming environments, but drastically complicate program understanding and reasoning because they allow to mutate object's local states by external objects in unexpected fashions, thus breaking modularity. The famous DAO bug in the cryptocurrency framework Ethereum, employed callbacks to steal $150M. We define the notion of Effectively Callback Free (ECF) objects in order to allow callbacks without preventing modular reasoning. An object is ECF in a given execution trace if there exists an equivalent execution trace without callbacks to this object. An object is ECF if it is ECF in every possible execution trace. We study the decidability of dynamically checking ECF in a given execution trace and statically checking if an object is ECF. We also show that dynamically checking ECF in Ethereum is feasible and can be done online. By running the history of all execution traces in Ethereum, we were able to verify that virtually all existing contracts, excluding the DAO or contracts with similar known vulnerabilities, are ECF. Finally, we show that ECF, whether it is verified dynamically or statically, enables modular reasoning about objects with encapsulated state.

##### Abstract (translated by Google)
回调在许多编程环境中都是必不可少的，但是使程序的理解和推理大为复杂化，因为它们允许通过外部对象以意想不到的方式来改变对象的本地状态，从而破坏模块化。在加密货币框架Ethereum中着名的DAO bug中，雇佣了回调盗取了1.5亿美元。我们定义了有效回调免费（ECF）对象的概念，以便在不阻止模块推理的情况下进行回调。一个对象是ECF在给定的执行轨迹，如果存在一个等效的执行轨迹没有回调这个对象。如果在每个可能的执行轨迹中都是ECF，则该对象是ECF。我们研究在给定的执行轨迹中动态检查ECF的可判定性，并静态检查一个对象是否为ECF。我们还表明，在Ethereum中动态检查ECF是可行的，可以在线完成。通过运行以太坊中所有执行轨迹的历史记录，我们能够验证几乎所有现有的合同（不包括具有类似已知漏洞的DAO或合同）都是ECF。最后，我们展示ECF，无论是动态还是静态验证，都能够对具有封装状态的对象进行模块推理。

##### URL
[https://arxiv.org/abs/1801.04032](https://arxiv.org/abs/1801.04032)

##### PDF
[https://arxiv.org/pdf/1801.04032](https://arxiv.org/pdf/1801.04032)


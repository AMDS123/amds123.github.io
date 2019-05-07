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


##### URL
[https://arxiv.org/abs/1801.04032](https://arxiv.org/abs/1801.04032)

##### PDF
[https://arxiv.org/pdf/1801.04032](https://arxiv.org/pdf/1801.04032)


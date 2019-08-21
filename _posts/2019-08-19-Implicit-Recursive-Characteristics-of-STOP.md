---
layout: post
title: "Implicit Recursive Characteristics of STOP"
date: 2019-08-19 05:43:13
categories: arXiv_CL
tags: arXiv_CL Inference
author: Mike H. Ji
mathjax: true
---

* content
{:toc}

##### Abstract
The most important notations of Communicating Sequential Process(CSP) are the process and the prefix (event)$\rightarrow$(process) operator. While we can formally apply the $\rightarrow$ operator to define a live process's behavior, the STOP process, which usually resulted from deadlock, starving or livelock, is lack of formal description, defined by most literatures as "doing nothing but halt". In this paper, we argue that the STOP process should not be considered as a black box, it should follow the prefix $\rightarrow$ schema and the same inference rules so that a unified and consistent process algebra model can be established. In order to achieve this goal, we introduce a special event called "nil" that any process can take. This nil event will do nothing meaningful and leave nothing on a process's observable record. With the nil event and its well-defined rules, we can successfully use the $\rightarrow$ operator to formally describe a process's complete behavior in its whole life circle. More interestingly, we can use prefix $\rightarrow$ and nil event to fully describe the STOP process's internal behavior and conclude that the STOP's formal equation can be given as simple as STOP$_{\alpha X} = \mu$ X. nil $\rightarrow$ X.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1908.06601](http://arxiv.org/abs/1908.06601)

##### PDF
[http://arxiv.org/pdf/1908.06601](http://arxiv.org/pdf/1908.06601)


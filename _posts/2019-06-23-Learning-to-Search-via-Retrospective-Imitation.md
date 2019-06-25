---
layout: post
title: "Learning to Search via Retrospective Imitation"
date: 2019-06-23 17:23:11
categories: arXiv_AI
tags: arXiv_AI
author: Jialin Song, Ravi Lanka, Albert Zhao, Aadyot Bhatnagar, Yisong Yue, Masahiro Ono
mathjax: true
---

* content
{:toc}

##### Abstract
We study the problem of learning a good search policy for combinatorial search spaces. We propose retrospective imitation learning, which, after initial training by an expert, improves itself by learning from \textit{retrospective inspections} of its own roll-outs. That is, when the policy eventually reaches a feasible solution in a combinatorial search tree after making mistakes and backtracks, it retrospectively constructs an improved search trace to the solution by removing backtracks, which is then used to further train the policy. A key feature of our approach is that it can iteratively scale up, or transfer, to larger problem sizes than those solved by the initial expert demonstrations, thus dramatically expanding its applicability beyond that of conventional imitation learning. We showcase the effectiveness of our approach on a range of tasks, including synthetic maze solving and combinatorial problems expressed as integer programs.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1804.00846](http://arxiv.org/abs/1804.00846)

##### PDF
[http://arxiv.org/pdf/1804.00846](http://arxiv.org/pdf/1804.00846)


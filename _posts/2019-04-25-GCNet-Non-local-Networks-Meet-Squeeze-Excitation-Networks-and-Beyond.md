---
layout: post
title: "GCNet: Non-local Networks Meet Squeeze-Excitation Networks and Beyond"
date: 2019-04-25 17:59:42
categories: arXiv_AI
tags: arXiv_AI Recognition
author: Yue Cao, Jiarui Xu, Stephen Lin, Fangyun Wei, Han Hu
mathjax: true
---

* content
{:toc}

##### Abstract
The Non-Local Network (NLNet) presents a pioneering approach for capturing long-range dependencies, via aggregating query-specific global context to each query position. However, through a rigorous empirical analysis, we have found that the global contexts modeled by non-local network are almost the same for different query positions within an image. In this paper, we take advantage of this finding to create a simplified network based on a query-independent formulation, which maintains the accuracy of NLNet but with significantly less computation. We further observe that this simplified design shares similar structure with Squeeze-Excitation Network (SENet). Hence we unify them into a three-step general framework for global context modeling. Within the general framework, we design a better instantiation, called the global context (GC) block, which is lightweight and can effectively model the global context. The lightweight property allows us to apply it for multiple layers in a backbone network to construct a global context network (GCNet), which generally outperforms both simplified NLNet and SENet on major benchmarks for various recognition tasks. The code and configurations are released at https://github.com/xvjiarui/GCNet.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1904.11492](http://arxiv.org/abs/1904.11492)

##### PDF
[http://arxiv.org/pdf/1904.11492](http://arxiv.org/pdf/1904.11492)


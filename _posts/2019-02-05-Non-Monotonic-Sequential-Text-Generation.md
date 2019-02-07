---
layout: post
title: "Non-Monotonic Sequential Text Generation"
date: 2019-02-05 14:02:45
categories: arXiv_CL
tags: arXiv_CL Text_Generation
author: Sean Welleck, Kiant&#xe9; Brantley, Hal Daum&#xe9; III, Kyunghyun Cho
mathjax: true
---

* content
{:toc}

##### Abstract
Standard sequential generation methods assume a pre-specified generation order, such as text generation methods which generate words from left to right. In this work, we propose a framework for training models of text generation that operate in non-monotonic orders; the model directly learns good orders, without any additional annotation. Our framework operates by generating a word at an arbitrary position, and then recursively generating words to its left and then words to its right, yielding a binary tree. Learning is framed as imitation learning, including a coaching method which moves from imitating an oracle to reinforcing the policy's own preferences. Experimental results demonstrate that using the proposed method, it is possible to learn policies which generate text without pre-specifying a generation order, while achieving competitive performance with conventional left-to-right generation.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1902.02192](http://arxiv.org/abs/1902.02192)

##### PDF
[http://arxiv.org/pdf/1902.02192](http://arxiv.org/pdf/1902.02192)


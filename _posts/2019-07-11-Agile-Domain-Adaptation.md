---
layout: post
title: "Agile Domain Adaptation"
date: 2019-07-11 02:51:27
categories: arXiv_CV
tags: arXiv_CV Knowledge Classification Detection
author: Jingjing Li, Mengmeng Jing, Yue Xie, Ke Lu, Zi Huang
mathjax: true
---

* content
{:toc}

##### Abstract
Domain adaptation investigates the problem of leveraging knowledge from a well-labeled source domain to an unlabeled target domain, where the two domains are drawn from different data distributions. Because of the distribution shifts, different target samples have distinct degrees of difficulty in adaptation. However, existing domain adaptation approaches overwhelmingly neglect the degrees of difficulty and deploy exactly the same framework for all of the target samples. Generally, a simple or shadow framework is fast but rough. A sophisticated or deep framework, on the contrary, is accurate but slow. In this paper, we aim to challenge the fundamental contradiction between the accuracy and speed in domain adaptation tasks. We propose a novel approach, named {\it agile domain adaptation}, which agilely applies optimal frameworks to different target samples and classifies the target samples according to their adaptation difficulties. Specifically, we propose a paradigm which performs several early detections before the final classification. If a sample can be classified at one of the early stage with enough confidence, the sample would exit without the subsequent processes. Notably, the proposed method can significantly reduce the running cost of domain adaptation approaches, which can extend the application scenarios of domain adaptation to even mobile devices and real-time systems. Extensive experiments on two open benchmarks verify the effectiveness and efficiency of the proposed method.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1907.04978](http://arxiv.org/abs/1907.04978)

##### PDF
[http://arxiv.org/pdf/1907.04978](http://arxiv.org/pdf/1907.04978)


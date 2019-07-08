---
layout: post
title: "Incremental Concept Learning via Online Generative Memory Recall"
date: 2019-07-05 12:13:46
categories: arXiv_CV
tags: arXiv_CV Adversarial
author: Huaiyu Li, Weiming Dong, Bao-Gang Hu
mathjax: true
---

* content
{:toc}

##### Abstract
The ability to learn more and more concepts over time from incrementally arriving data is essential for the development of a life-long learning system. However, deep neural networks often suffer from forgetting previously learned concepts when continually learning new concepts, which is known as catastrophic forgetting problem. The main reason for catastrophic forgetting is that the past concept data is not available and neural weights are changed during incrementally learning new concepts. In this paper, we propose a pseudo-rehearsal based class incremental learning approach to make neural networks capable of continually learning new concepts. We use a conditional generative adversarial network to consolidate old concepts memory and recall pseudo samples during learning new concepts and a balanced online memory recall strategy is to maximally maintain old memories. And we design a comprehensible incremental concept learning network as well as a concept contrastive loss to alleviate the magnitude of neural weights change. We evaluate the proposed approach on MNIST, Fashion-MNIST and SVHN datasets and compare with other rehearsal based approaches. The extensive experiments demonstrate the effectiveness of our approach.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1907.02788](http://arxiv.org/abs/1907.02788)

##### PDF
[http://arxiv.org/pdf/1907.02788](http://arxiv.org/pdf/1907.02788)


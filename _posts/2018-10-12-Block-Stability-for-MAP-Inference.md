---
layout: post
title: "Block Stability for MAP Inference"
date: 2018-10-12 01:17:38
categories: arXiv_AI
tags: arXiv_AI Adversarial Inference
author: Hunter Lang, David Sontag, Aravindan Vijayaraghavan
mathjax: true
---

* content
{:toc}

##### Abstract
To understand the empirical success of approximate MAP inference, recent work (Lang et al., 2018) has shown that some popular approximation algorithms perform very well when the input instance is stable. The simplest stability condition assumes that the MAP solution does not change at all when some of the pairwise potentials are (adversarially) perturbed. Unfortunately, this strong condition does not seem to be satisfied in practice. In this paper, we introduce a significantly more relaxed condition that only requires blocks (portions) of an input instance to be stable. Under this block stability condition, we prove that the pairwise LP relaxation is persistent on the stable blocks. We complement our theoretical results with an empirical evaluation of real-world MAP inference instances from computer vision. We design an algorithm to find stable blocks, and find that these real instances have large stable regions. Our work gives a theoretical explanation for the widespread empirical phenomenon of persistency for this LP relaxation.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1810.05305](https://arxiv.org/abs/1810.05305)

##### PDF
[https://arxiv.org/pdf/1810.05305](https://arxiv.org/pdf/1810.05305)


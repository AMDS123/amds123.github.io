---
layout: post
title: "Towards Using Context-Dependent Symbols in CTC Without State-Tying Decision Trees"
date: 2019-01-14 16:23:35
categories: arXiv_CL
tags: arXiv_CL
author: Jan Chorowski, Adrian Lancucki, Bartosz Kostka, Michal Zapotoczny
mathjax: true
---

* content
{:toc}

##### Abstract
Deep neural acoustic models benefit from context dependent modeling of output symbols. However, their usage requires state-tying decision trees that are typically transferred from classical GMM-HMM systems. In this work we consider direct training of CTC networks with context dependent outputs. A state-tying decision tree is replaced with a neural network that predicts the weights of the final SoftMax classifier in a context-dependent way. This network is trained together with the rest of the acoustic model and lifts one of the last cases in which neural systems have to be bootstrapped from GMM-HMM ones. We describe changes to the CTC cost function that are needed to accommodate context-dependent symbols and validate this idea on bigram context dependent system built for character-based WSJ.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1901.04379](http://arxiv.org/abs/1901.04379)

##### PDF
[http://arxiv.org/pdf/1901.04379](http://arxiv.org/pdf/1901.04379)


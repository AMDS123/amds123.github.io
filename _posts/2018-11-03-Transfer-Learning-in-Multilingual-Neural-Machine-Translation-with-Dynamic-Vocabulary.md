---
layout: post
title: "Transfer Learning in Multilingual Neural Machine Translation with Dynamic Vocabulary"
date: 2018-11-03 00:38:45
categories: arXiv_CL
tags: arXiv_CL Knowledge Transfer_Learning NMT
author: Surafel M. Lakew, Aliia Erofeeva, Matteo Negri, Marcello Federico, Marco Turchi
mathjax: true
---

* content
{:toc}

##### Abstract
We propose a method to transfer knowledge across neural machine translation (NMT) models by means of a shared dynamic vocabulary. Our approach allows to extend an initial model for a given language pair to cover new languages by adapting its vocabulary as long as new data become available (i.e., introducing new vocabulary items if they are not included in the initial model). The parameter transfer mechanism is evaluated in two scenarios: i) to adapt a trained single language NMT system to work with a new language pair and ii) to continuously add new language pairs to grow to a multilingual NMT system. In both the scenarios our goal is to improve the translation performance, while minimizing the training convergence time. Preliminary experiments spanning five languages with different training data sizes (i.e., 5k and 50k parallel sentences) show a significant performance gain ranging from +3.85 up to +13.63 BLEU in different language directions. Moreover, when compared with training an NMT model from scratch, our transfer-learning approach allows us to reach higher performance after training up to 4% of the total training steps.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1811.01137](http://arxiv.org/abs/1811.01137)

##### PDF
[http://arxiv.org/pdf/1811.01137](http://arxiv.org/pdf/1811.01137)


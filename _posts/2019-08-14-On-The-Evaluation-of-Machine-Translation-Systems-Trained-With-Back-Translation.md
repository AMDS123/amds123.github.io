---
layout: post
title: "On The Evaluation of Machine Translation Systems Trained With Back-Translation"
date: 2019-08-14 16:24:56
categories: arXiv_CL
tags: arXiv_CL Language_Model
author: Sergey Edunov, Myle Ott, Marc&#x27;Aurelio Ranzato, Michael Auli
mathjax: true
---

* content
{:toc}

##### Abstract
Back-translation is a widely used data augmentation technique which leverages target monolingual data. However, its effectiveness has been challenged since automatic metrics such as BLEU only show significant improvements for test examples where the source itself is a translation, or translationese. This is believed to be due to translationese inputs better matching the back-translated training data. In this work, we show that this conjecture is not empirically supported and that back-translation improves translation quality of both naturally occurring text as well as translationese according to professional human translators. We provide empirical evidence to support the view that back-translation is preferred by humans because it produces more fluent outputs. BLEU cannot capture human preferences because references are translationese when source sentences are natural text. We recommend complementing BLEU with a language model score to measure fluency.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1908.05204](http://arxiv.org/abs/1908.05204)

##### PDF
[http://arxiv.org/pdf/1908.05204](http://arxiv.org/pdf/1908.05204)


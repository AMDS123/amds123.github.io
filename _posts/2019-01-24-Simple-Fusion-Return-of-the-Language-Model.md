---
layout: post
title: "Simple Fusion: Return of the Language Model"
date: 2019-01-24 18:00:25
categories: arXiv_CL
tags: arXiv_CL NMT Language_Model Prediction
author: Felix Stahlberg, James Cross, Veselin Stoyanov
mathjax: true
---

* content
{:toc}

##### Abstract
Neural Machine Translation (NMT) typically leverages monolingual data in training through backtranslation. We investigate an alternative simple method to use monolingual data for NMT training: We combine the scores of a pre-trained and fixed language model (LM) with the scores of a translation model (TM) while the TM is trained from scratch. To achieve that, we train the translation model to predict the residual probability of the training data added to the prediction of the LM. This enables the TM to focus its capacity on modeling the source sentence since it can rely on the LM for fluency. We show that our method outperforms previous approaches to integrate LMs into NMT while the architecture is simpler as it does not require gating networks to balance TM and LM. We observe gains of between +0.24 and +2.36 BLEU on all four test sets (English-Turkish, Turkish-English, Estonian-English, Xhosa-English) on top of ensembles without LM. We compare our method with alternative ways to utilize monolingual data such as backtranslation, shallow fusion, and cold fusion.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1809.00125](https://arxiv.org/abs/1809.00125)

##### PDF
[https://arxiv.org/pdf/1809.00125](https://arxiv.org/pdf/1809.00125)


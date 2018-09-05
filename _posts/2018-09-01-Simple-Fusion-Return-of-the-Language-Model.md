---
layout: post
title: "Simple Fusion: Return of the Language Model"
date: 2018-09-01 06:39:56
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
神经机器翻译（NMT）通常通过反向翻译在训练中利用单语数据。我们研究了使用单语数据进行NMT训练的另一种简单方法：我们将预训练和固定语言模型（LM）的分数与翻译模型（TM）的分数相结合，同时从头开始训练TM。为了实现这一点，我们训练翻译模型以预测添加到LM预测中的训练数据的残余概率。这使TM能够集中精力对源句进行建模，因为它可以依赖LM来提高流畅度。我们表明，我们的方法优于以前将LM集成到NMT的方法，而架构更简单，因为它不需要门控网络来平衡TM和LM。在没有LM的合奏的基础上，我们在所有四个测试集（英语 - 土耳其语，土耳其语 - 英语，爱沙尼亚语 - 英语，科萨 - 英语）上观察到+0.24和+2.36 BLEU之间的增益。我们将我们的方法与利用单语数据的替代方法进行比较，例如反向翻译，浅层融合和冷聚变。

##### URL
[http://arxiv.org/abs/1809.00125](http://arxiv.org/abs/1809.00125)

##### PDF
[http://arxiv.org/pdf/1809.00125](http://arxiv.org/pdf/1809.00125)


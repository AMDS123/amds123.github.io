---
layout: post
title: "EmotionX-HSU: Adopting Pre-trained BERT for Emotion Classification"
date: 2019-07-23 03:05:39
categories: arXiv_CL
tags: arXiv_CL Knowledge Face Classification Deep_Learning
author: Linkai Luo, Yue Wang
mathjax: true
---

* content
{:toc}

##### Abstract
This paper describes our approach to the EmotionX-2019, the shared task of SocialNLP 2019. To detect emotion for each utterance of two datasets from the TV show Friends and Facebook chat log EmotionPush, we propose two-step deep learning based methodology: (i) encode each of the utterance into a sequence of vectors that represent its meaning; and (ii) use a simply softmax classifier to predict one of the emotions amongst four candidates that an utterance may carry. Notice that the source of labeled utterances is not rich, we utilise a well-trained model, known as BERT, to transfer part of the knowledge learned from a large amount of corpus to our model. We then focus on fine-tuning our model until it well fits to the in-domain data. The performance of the proposed model is evaluated by micro-F1 scores, i.e., 79.1% and 86.2% for the testsets of Friends and EmotionPush, respectively. Our model ranks 3rd among 11 submissions.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1907.09669](http://arxiv.org/abs/1907.09669)

##### PDF
[http://arxiv.org/pdf/1907.09669](http://arxiv.org/pdf/1907.09669)


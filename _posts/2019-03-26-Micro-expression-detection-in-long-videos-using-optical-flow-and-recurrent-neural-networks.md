---
layout: post
title: "Micro-expression detection in long videos using optical flow and recurrent neural networks"
date: 2019-03-26 10:01:46
categories: arXiv_CV
tags: arXiv_CV Sentiment Review Face RNN Detection
author: Michiel Verburg, Vlado Menkovski
mathjax: true
---

* content
{:toc}

##### Abstract
Facial micro-expressions are subtle and involuntary expressions that can reveal concealed emotions. Micro-expressions are an invaluable source of information in application domains such as lie detection, mental health, sentiment analysis and more. One of the biggest challenges in this field of research is the small amount of available spontaneous micro-expression data. However, spontaneous data collection is burdened by time-consuming and expensive annotation. Hence, methods are needed which can reduce the amount of data that annotators have to review. This paper presents a novel micro-expression spotting method using a recurrent neural network (RNN) on optical flow features. We extract Histogram of Oriented Optical Flow (HOOF) features to encode the temporal changes in selected face regions. Finally, the RNN spots short intervals which are likely to contain occurrences of relevant facial micro-movements. The proposed method is evaluated on the SAMM database. Any chance of subject bias is eliminated by training the RNN using Leave-One-Subject-Out cross-validation. Comparing the spotted intervals with the labeled data shows that the method produced 1569 false positives while obtaining a recall of 0.4654. The initial results show that the proposed method would reduce the video length by a factor of 3.5, while still retaining almost half of the relevant micro-movements. Lastly, as the model gets more data, it becomes better at detecting intervals, which makes the proposed method suitable for supporting the annotation process.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1903.10765](http://arxiv.org/abs/1903.10765)

##### PDF
[http://arxiv.org/pdf/1903.10765](http://arxiv.org/pdf/1903.10765)


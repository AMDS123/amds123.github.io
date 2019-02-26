---
layout: post
title: "ABI Neural Ensemble Model for Gender Prediction Adapt Bar-Ilan Submission for the CLIN29 Shared Task on Gender Prediction"
date: 2019-02-23 22:17:08
categories: arXiv_CL
tags: arXiv_CL RNN Prediction Detection
author: Eva Vanmassenhove, Amit Moryossef, Alberto Poncelas, Andy Way, Dimitar Shterionov
mathjax: true
---

* content
{:toc}

##### Abstract
We present our system for the CLIN29 shared task on cross-genre gender detection for Dutch. We experimented with a multitude of neural models (CNN, RNN, LSTM, etc.), more "traditional" models (SVM, RF, LogReg, etc.), different feature sets as well as data pre-processing. The final results suggested that using tokenized, non-lowercased data works best for most of the neural models, while a combination of word clusters, character trigrams and word lists showed to be most beneficial for the majority of the more "traditional" (that is, non-neural) models, beating features used in previous tasks such as n-grams, character n-grams, part-of-speech tags and combinations thereof. In contradiction with the results described in previous comparable shared tasks, our neural models performed better than our best traditional approaches with our best feature set-up. Our final model consisted of a weighted ensemble model combining the top 25 models. Our final model won both the in-domain gender prediction task and the cross-genre challenge, achieving an average accuracy of 64.93% on the in-domain gender prediction task, and 56.26% on cross-genre gender prediction.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1902.08856](http://arxiv.org/abs/1902.08856)

##### PDF
[http://arxiv.org/pdf/1902.08856](http://arxiv.org/pdf/1902.08856)


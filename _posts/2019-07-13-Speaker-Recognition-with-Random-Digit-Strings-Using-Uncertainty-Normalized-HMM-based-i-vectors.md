---
layout: post
title: "Speaker Recognition with Random Digit Strings Using Uncertainty Normalized HMM-based i-vectors"
date: 2019-07-13 17:52:17
categories: arXiv_CL
tags: arXiv_CL Recognition
author: Nooshin Maghsoodi, Hossein Sameti, Hossein Zeinali, Themos~Stafylakis
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper, we combine Hidden Markov Models (HMMs) with i-vector extractors to address the problem of text-dependent speaker recognition with random digit strings. We employ digit-specific HMMs to segment the utterances into digits, to perform frame alignment to HMM states and to extract Baum-Welch statistics. By making use of the natural partition of input features into digits, we train digit-specific i-vector extractors on top of each HMM and we extract well-localized i-vectors, each modelling merely the phonetic content corresponding to a single digit. We then examine ways to perform channel and uncertainty compensation, and we propose a novel method for using the uncertainty in the i-vector estimates. The experiments on RSR2015 part III show that the proposed method attains 1.52\% and 1.77\% Equal Error Rate (EER) for male and female respectively, outperforming state-of-the-art methods such as x-vectors, trained on vast amounts of data. Furthermore, these results are attained by a single system trained entirely on RSR2015, and by a simple score-normalized cosine distance. Moreover, we show that the omission of channel compensation yields only a minor degradation in performance, meaning that the system attains state-of-the-art results even without recordings from multiple handsets per speaker for training or enrolment. Similar conclusions are drawn from our experiments on the RedDots corpus, where the same method is evaluated on phrases. Finally, we report results with bottleneck features and show that further improvement is attained when fusing them with spectral features.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1907.06111](http://arxiv.org/abs/1907.06111)

##### PDF
[http://arxiv.org/pdf/1907.06111](http://arxiv.org/pdf/1907.06111)


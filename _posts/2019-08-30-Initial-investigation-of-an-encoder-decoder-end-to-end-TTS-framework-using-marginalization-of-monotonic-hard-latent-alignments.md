---
layout: post
title: "Initial investigation of an encoder-decoder end-to-end TTS framework using marginalization of monotonic hard latent alignments"
date: 2019-08-30 05:00:06
categories: arXiv_CL
tags: arXiv_CL Attention Prediction
author: Yusuke Yasuda, Xin Wang, Junichi Yamagishi
mathjax: true
---

* content
{:toc}

##### Abstract
End-to-end text-to-speech (TTS) synthesis is a method that directly converts input text to output acoustic features using a single network. A recent advance of end-to-end TTS is due to a key technique called attention mechanisms, and all successful methods proposed so far have been based on soft attention mechanisms. However, although network structures are becoming increasingly complex, end-to-end TTS systems with soft attention mechanisms may still fail to learn and to predict accurate alignment between the input and output. This may be because the soft attention mechanisms are too flexible. Therefore, we propose an approach that has more explicit but natural constraints suitable for speech signals to make alignment learning and prediction of end-to-end TTS systems more robust. The proposed system, with the constrained alignment scheme borrowed from segment-to-segment neural transduction (SSNT), directly calculates the joint probability of acoustic features and alignment given an input text. The alignment is designed to be hard and monotonically increase by considering the speech nature, and it is treated as a latent variable and marginalized during training. During prediction, both the alignment and acoustic features can be generated from the probabilistic distributions. The advantages of our approach are that we can simplify many modules for the soft attention and that we can train the end-to-end TTS model using a single likelihood function. As far as we know, our approach is the first end-to-end TTS without a soft attention mechanism.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1908.11535](http://arxiv.org/abs/1908.11535)

##### PDF
[http://arxiv.org/pdf/1908.11535](http://arxiv.org/pdf/1908.11535)


---
layout: post
title: "wav2vec: Unsupervised Pre-training for Speech Recognition"
date: 2019-04-11 17:29:30
categories: arXiv_CL
tags: arXiv_CL Speech_Recognition CNN Classification Recognition
author: Steffen Schneider, Alexei Baevski, Ronan Collobert, Michael Auli
mathjax: true
---

* content
{:toc}

##### Abstract
We explore unsupervised pre-training for speech recognition by learning representations of raw audio. wav2vec is trained on large amounts of unlabeled audio data and the resulting representations are then used to improve acoustic model training. We pre-train a simple multi-layer convolutional neural network optimized via a noise contrastive binary classification task. Our experiments on WSJ reduce WER of a strong character-based log-mel filterbank baseline by up to 32% when only a few hours of transcribed data is available. Our approach achieves 2.78% WER on the nov92 test set. This outperforms Deep Speech 2, the best reported character-based system in the literature while using three orders of magnitude less labeled training data.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1904.05862](http://arxiv.org/abs/1904.05862)

##### PDF
[http://arxiv.org/pdf/1904.05862](http://arxiv.org/pdf/1904.05862)


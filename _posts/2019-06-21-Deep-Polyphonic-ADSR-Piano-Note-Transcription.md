---
layout: post
title: "Deep Polyphonic ADSR Piano Note Transcription"
date: 2019-06-21 14:38:36
categories: arXiv_SD
tags: arXiv_SD Segmentation Gradient_Descent
author: Rainer Kelz, Sebastian B&#xf6;ck, Gerhard Widmer
mathjax: true
---

* content
{:toc}

##### Abstract
We investigate a late-fusion approach to piano transcription, combined with a strong temporal prior in the form of a handcrafted Hidden Markov Model (HMM). The network architecture under consideration is compact in terms of its number of parameters and easy to train with gradient descent. The network outputs are fused over time in the final stage to obtain note segmentations, with an HMM whose transition probabilities are chosen based on a model of attack, decay, sustain, release (ADSR) envelopes, commonly used for sound synthesis. The note segments are then subject to a final binary decision rule to reject too weak note segment hypotheses. We obtain state-of-the-art results on the MAPS dataset, and are able to outperform other approaches by a large margin, when predicting complete note regions from onsets to offsets.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1906.09165](http://arxiv.org/abs/1906.09165)

##### PDF
[http://arxiv.org/pdf/1906.09165](http://arxiv.org/pdf/1906.09165)


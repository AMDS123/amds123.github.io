---
layout: post
title: "Learning from Past Mistakes: Improving Automatic Speech Recognition Output via Noisy-Clean Phrase Context Modeling"
date: 2019-03-28 23:28:46
categories: arXiv_CL
tags: arXiv_CL Speech_Recognition Language_Model Recognition
author: Prashanth Gurunath Shivakumar, Haoqi Li, Kevin Knight, Panayiotis Georgiou
mathjax: true
---

* content
{:toc}

##### Abstract
Automatic speech recognition (ASR) systems often make unrecoverable errors due to subsystem pruning (acoustic, language and pronunciation models); for example pruning words due to acoustics using short-term context, prior to rescoring with long-term context based on linguistics. In this work we model ASR as a phrase-based noisy transformation channel and propose an error correction system that can learn from the aggregate errors of all the independent modules constituting the ASR and attempt to invert those. The proposed system can exploit long-term context using a neural network language model and can better choose between existing ASR output possibilities as well as re-introduce previously pruned or unseen (out-of-vocabulary) phrases. It provides corrections under poorly performing ASR conditions without degrading any accurate transcriptions; such corrections are greater on top of out-of-domain and mismatched data ASR. Our system consistently provides improvements over the baseline ASR, even when baseline is further optimized through recurrent neural network language model rescoring. This demonstrates that any ASR improvements can be exploited independently and that our proposed system can potentially still provide benefits on highly optimized ASR. Finally, we present an extensive analysis of the type of errors corrected by our system.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1802.02607](http://arxiv.org/abs/1802.02607)

##### PDF
[http://arxiv.org/pdf/1802.02607](http://arxiv.org/pdf/1802.02607)


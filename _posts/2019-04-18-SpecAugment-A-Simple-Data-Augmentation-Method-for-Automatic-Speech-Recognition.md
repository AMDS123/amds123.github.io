---
layout: post
title: "SpecAugment: A Simple Data Augmentation Method for Automatic Speech Recognition"
date: 2019-04-18 17:53:38
categories: arXiv_CL
tags: arXiv_CL Speech_Recognition Language_Model Recognition
author: Daniel S. Park, William Chan, Yu Zhang, Chung-Cheng Chiu, Barret Zoph, Ekin D. Cubuk, Quoc V. Le
mathjax: true
---

* content
{:toc}

##### Abstract
We present SpecAugment, a simple data augmentation method for speech recognition. SpecAugment is applied directly to the feature inputs of a neural network (i.e., filter bank coefficients). The augmentation policy consists of warping the features, masking blocks of frequency channels, and masking blocks of time steps. We apply SpecAugment on Listen, Attend and Spell networks for end-to-end speech recognition tasks. We achieve state-of-the-art performance on the LibriSpeech 960h and Swichboard 300h tasks, outperforming all prior work. On LibriSpeech, we achieve 6.8% WER on test-other without the use of a language model, and 5.8% WER with shallow fusion with a language model. This compares to the previous state-of-the-art hybrid system of 7.5% WER. For Switchboard, we achieve 7.2%/14.6% on the Switchboard/CallHome portion of the Hub5'00 test set without the use of a language model, and 6.8%/14.1% with shallow fusion, which compares to the previous state-of-the-art hybrid system at 8.3%/17.3% WER.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1904.08779](http://arxiv.org/abs/1904.08779)

##### PDF
[http://arxiv.org/pdf/1904.08779](http://arxiv.org/pdf/1904.08779)


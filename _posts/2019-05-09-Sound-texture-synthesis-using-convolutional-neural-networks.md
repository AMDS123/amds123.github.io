---
layout: post
title: "Sound texture synthesis using convolutional neural networks"
date: 2019-05-09 13:51:27
categories: arXiv_SD
tags: arXiv_SD CNN Relation
author: Hugo Caracalla, Axel Roebel
mathjax: true
---

* content
{:toc}

##### Abstract
The following article introduces a new parametric synthesis algorithm for sound textures inspired by existing methods used for visual textures. Using a 2D Convolutional Neural Network (CNN), a sound signal is modified until the temporal cross-correlations of the feature maps of its log-spectrogram resemble those of a target texture. We show that the resulting synthesized sound signal is both different from the original and of high quality, while being able to reproduce singular events appearing in the original. This process is performed in the time domain, discarding the harmful phase recovery step which usually concludes synthesis performed in the time-frequency domain. It is also straightforward and flexible, as it does not require any fine tuning between several losses when synthesizing diverse sound textures. A way of extending the synthesis in order to produce a sound of any length is also presented, after which synthesized spectrograms and sound signals are showcased. We also discuss on the choice of CNN, on border effects in our synthesized signals and on possible ways of modifying the algorithm in order to improve its current long computation time.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1905.03637](http://arxiv.org/abs/1905.03637)

##### PDF
[http://arxiv.org/pdf/1905.03637](http://arxiv.org/pdf/1905.03637)


---
layout: post
title: "Salient Speech Representations Based on Cloned Networks"
date: 2019-08-19 19:38:01
categories: arXiv_SD
tags: arXiv_SD Salient
author: W. Bastiaan Kleijn, Felicia S. C. Lim, Michael Chinen, Jan Skoglund
mathjax: true
---

* content
{:toc}

##### Abstract
We define salient features as features that are shared by signals that are defined as being equivalent by a system designer. The definition allows the designer to contribute qualitative information. We aim to find salient features that are useful as conditioning for generative networks. We extract salient features by jointly training a set of clones of an encoder network. Each network clone receives as input a different signal from a set of equivalent signals. The objective function encourages the network clones to map their input into a set of features that is identical across the clones. It additionally encourages feature independence and, optionally, reconstruction of a desired target signal by a decoder. As an application, we train a system that extracts a time-sequence of feature vectors of speech and uses it as a conditioning of a WaveNet generative system, facilitating both coding and enhancement.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1908.07045](http://arxiv.org/abs/1908.07045)

##### PDF
[http://arxiv.org/pdf/1908.07045](http://arxiv.org/pdf/1908.07045)


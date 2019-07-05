---
layout: post
title: "Blind Audio Source Separation with Minimum-Volume Beta-Divergence NMF"
date: 2019-07-04 13:56:25
categories: arXiv_SD
tags: arXiv_SD
author: Valentin Leplat, Nicolas Gillis, Man Shun Ang
mathjax: true
---

* content
{:toc}

##### Abstract
Considering a mixed signal composed of various audio sources and recorded with a single microphone, we consider on this paper the blind audio source separation problem which consists in isolating and extracting each of the sources. To perform this task, nonnegative matrix factorization (NMF) based on the Kullback-Leibler and Itakura-Saito $\beta$-divergences is a standard and state-of-the-art technique that uses the time-frequency representation of the signal. We present a new NMF model better suited for this task. It is based on the minimization of $\beta$-divergences along with a penalty term that promotes the columns of the dictionary matrix to have a small volume. Under some mild assumptions and in noiseless conditions, we prove that this model is provably able to identify the sources. In order to solve this problem, we propose multiplicative updates whose derivations are based on the standard majorization-minimization framework. We show on several numerical experiments that our new model is able to obtain more interpretable results than standard NMF models. Moreover, we show that it is able to recover the sources even when the number of sources present into the mixed signal is overestimated. In fact, our model automatically sets sources to zero in this situation, hence performs model order selection automatically.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1907.02404](http://arxiv.org/abs/1907.02404)

##### PDF
[http://arxiv.org/pdf/1907.02404](http://arxiv.org/pdf/1907.02404)


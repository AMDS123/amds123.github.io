---
layout: post
title: "Speech Separation Using Gain-Adapted Factorial Hidden Markov Models"
date: 2019-01-22 20:17:07
categories: arXiv_SD
tags: arXiv_SD Optimization Inference
author: Martin H. Radfar, Richard M. Dansereau, Willy Wong
mathjax: true
---

* content
{:toc}

##### Abstract
We present a new probabilistic graphical model which generalizes factorial hidden Markov models (FHMM) for the problem of single-channel speech separation (SCSS) in which we wish to separate the two speech signals $X(t)$ and $V(t)$ from a single recording of their mixture $Y(t)=X(t)+V(t)$ using the trained models of the speakers' speech signals. Current techniques assume the data used in the training and test phases of the separation model have the same loudness. In this paper, we introduce GFHMM, gain adapted FHMM, to extend SCSS to the general case in which $Y(t)=g_xX(t)+g_vV(t)$, where $g_x$ and $g_v$ are unknown gain factors. GFHMM consists of two independent-state HMMs and a hidden node which model spectral patterns and gain difference, respectively. A novel inference method is presented using the Viterbi algorithm and quadratic optimization with minimal computational overhead. Experimental results, conducted on 180 mixtures with gain differences from 0 to 15~dB, show that the proposed technique significantly outperforms FHMM and its memoryless counterpart, i.e., vector quantization (VQ)-based SCSS.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1901.07604](http://arxiv.org/abs/1901.07604)

##### PDF
[http://arxiv.org/pdf/1901.07604](http://arxiv.org/pdf/1901.07604)


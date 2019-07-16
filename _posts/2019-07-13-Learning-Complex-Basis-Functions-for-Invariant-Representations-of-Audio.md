---
layout: post
title: "Learning Complex Basis Functions for Invariant Representations of Audio"
date: 2019-07-13 00:23:26
categories: arXiv_CV
tags: arXiv_CV
author: Stefan Lattner, Monika D&#xf6;rfler, Andreas Arzt
mathjax: true
---

* content
{:toc}

##### Abstract
Learning features from data has shown to be more successful than using hand-crafted features for many machine learning tasks. In music information retrieval (MIR), features learned from windowed spectrograms are highly variant to transformations like transposition or time-shift. Such variances are undesirable when they are irrelevant for the respective MIR task. We propose an architecture called Complex Autoencoder (CAE) which learns features invariant to orthogonal transformations. Mapping signals onto complex basis functions learned by the CAE results in a transformation-invariant "magnitude space" and a transformation-variant "phase space". The phase space is useful to infer transformations between data pairs. When exploiting the invariance-property of the magnitude space, we achieve state-of-the-art results in audio-to-score alignment and repeated section discovery for audio. A PyTorch implementation of the CAE, including the repeated section discovery method, is available online.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1907.05982](http://arxiv.org/abs/1907.05982)

##### PDF
[http://arxiv.org/pdf/1907.05982](http://arxiv.org/pdf/1907.05982)


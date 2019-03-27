---
layout: post
title: "Diversifying Reply Suggestions using a Matching-Conditional Variational Autoencoder"
date: 2019-03-25 23:12:56
categories: arXiv_CL
tags: arXiv_CL Inference
author: Budhaditya Deb, Peter Bailey, Milad Shokouhi
mathjax: true
---

* content
{:toc}

##### Abstract
We consider the problem of diversifying automated reply suggestions for a commercial instant-messaging (IM) system (Skype). Our conversation model is a standard matching based information retrieval architecture, which consists of two parallel encoders to project messages and replies into a common feature representation. During inference, we select replies from a fixed response set using nearest neighbors in the feature space. To diversify responses, we formulate the model as a generative latent variable model with Conditional Variational Auto-Encoder (M-CVAE). We propose a constrained-sampling approach to make the variational inference in M-CVAE efficient for our production system. In offline experiments, M-CVAE consistently increased diversity by ~30-40% without significant impact on relevance. This translated to a 5% gain in click-rate in our online production system.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1903.10630](http://arxiv.org/abs/1903.10630)

##### PDF
[http://arxiv.org/pdf/1903.10630](http://arxiv.org/pdf/1903.10630)


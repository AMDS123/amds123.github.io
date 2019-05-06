---
layout: post
title: "Learning Hard Alignments with Variational Inference"
date: 2017-11-01 19:08:18
categories: arXiv_CV
tags: arXiv_CV Attention Speech_Recognition Caption Inference Recognition
author: Dieterich Lawson, Chung-Cheng Chiu, George Tucker, Colin Raffel, Kevin Swersky, Navdeep Jaitly
mathjax: true
---

* content
{:toc}

##### Abstract
There has recently been significant interest in hard attention models for tasks such as object recognition, visual captioning and speech recognition. Hard attention can offer benefits over soft attention such as decreased computational cost, but training hard attention models can be difficult because of the discrete latent variables they introduce. Previous work used REINFORCE and Q-learning to approach these issues, but those methods can provide high-variance gradient estimates and be slow to train. In this paper, we tackle the problem of learning hard attention for a sequential task using variational inference methods, specifically the recently introduced VIMCO and NVIL. Furthermore, we propose a novel baseline that adapts VIMCO to this setting. We demonstrate our method on a phoneme recognition task in clean and noisy environments and show that our method outperforms REINFORCE, with the difference being greater for a more complicated task.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1705.05524](https://arxiv.org/abs/1705.05524)

##### PDF
[https://arxiv.org/pdf/1705.05524](https://arxiv.org/pdf/1705.05524)


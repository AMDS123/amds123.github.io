---
layout: post
title: "Cycle-SUM: Cycle-consistent Adversarial LSTM Networks for Unsupervised Video Summarization"
date: 2019-04-17 13:30:49
categories: arXiv_CV
tags: arXiv_CV Adversarial GAN Summarization RNN Relation
author: Li Yuan, Francis EH Tay, Ping Li, Li Zhou, Jiashi Feng
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper, we present a novel unsupervised video summarization model that requires no manual annotation. The proposed model termed Cycle-SUM adopts a new cycle-consistent adversarial LSTM architecture that can effectively maximize the information preserving and compactness of the summary video. It consists of a frame selector and a cycle-consistent learning based evaluator. The selector is a bi-direction LSTM network that learns video representations that embed the long-range relationships among video frames. The evaluator defines a learnable information preserving metric between original video and summary video and "supervises" the selector to identify the most informative frames to form the summary video. In particular, the evaluator is composed of two generative adversarial networks (GANs), in which the forward GAN is learned to reconstruct original video from summary video while the backward GAN learns to invert the processing. The consistency between the output of such cycle learning is adopted as the information preserving metric for video summarization. We demonstrate the close relation between mutual information maximization and such cycle learning procedure. Experiments on two video summarization benchmark datasets validate the state-of-the-art performance and superiority of the Cycle-SUM model over previous baselines.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1904.08265](http://arxiv.org/abs/1904.08265)

##### PDF
[http://arxiv.org/pdf/1904.08265](http://arxiv.org/pdf/1904.08265)


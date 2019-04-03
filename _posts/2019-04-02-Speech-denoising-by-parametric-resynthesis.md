---
layout: post
title: "Speech denoising by parametric resynthesis"
date: 2019-04-02 16:50:46
categories: arXiv_SD
tags: arXiv_SD
author: Soumi Maiti, Michael I Mandel
mathjax: true
---

* content
{:toc}

##### Abstract
This work proposes the use of clean speech vocoder parameters as the target for a neural network performing speech enhancement. These parameters have been designed for text-to-speech synthesis so that they both produce high-quality resyntheses and also are straightforward to model with neural networks, but have not been utilized in speech enhancement until now. In comparison to a matched text-to-speech system that is given the ground truth transcripts of the noisy speech, our model is able to produce more natural speech because it has access to the true prosody in the noisy speech. In comparison to two denoising systems, the oracle Wiener mask and a DNN-based mask predictor, our model equals the oracle Wiener mask in subjective quality and intelligibility and surpasses the realistic system. A vocoder-based upper bound shows that there is still room for improvement with this approach beyond the oracle Wiener mask. We test speaker-dependence with two speakers and show that a single model can be used for multiple speakers.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1904.01537](http://arxiv.org/abs/1904.01537)

##### PDF
[http://arxiv.org/pdf/1904.01537](http://arxiv.org/pdf/1904.01537)


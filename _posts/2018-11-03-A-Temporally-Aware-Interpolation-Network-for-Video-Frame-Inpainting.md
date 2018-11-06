---
layout: post
title: "A Temporally-Aware Interpolation Network for Video Frame Inpainting"
date: 2018-11-03 23:34:33
categories: arXiv_CV
tags: arXiv_CV CNN RNN Deep_Learning Prediction
author: Ximeng Sun, Ryan Szeto, Jason J. Corso
mathjax: true
---

* content
{:toc}

##### Abstract
We propose the first deep learning solution to video frame inpainting, a challenging instance of the general video inpainting problem with applications in video editing, manipulation, and forensics. Our task is less ambiguous than frame interpolation and video prediction because we have access to both the temporal context and a partial glimpse of the future, allowing us to better evaluate the quality of a model's predictions objectively. We devise a pipeline composed of two modules: a bidirectional video prediction module, and a temporally-aware frame interpolation module. The prediction module makes two intermediate predictions of the missing frames, one conditioned on the preceding frames and the other conditioned on the following frames, using a shared convolutional LSTM-based encoder-decoder. The interpolation module blends the intermediate predictions to form the final result. Specifically, it utilizes time information and hidden activations from the video prediction module to resolve disagreements between the predictions. Our experiments demonstrate that our approach produces more accurate and qualitatively satisfying results than a state-of-the-art video prediction method and many strong frame inpainting baselines.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1803.07218](http://arxiv.org/abs/1803.07218)

##### PDF
[http://arxiv.org/pdf/1803.07218](http://arxiv.org/pdf/1803.07218)


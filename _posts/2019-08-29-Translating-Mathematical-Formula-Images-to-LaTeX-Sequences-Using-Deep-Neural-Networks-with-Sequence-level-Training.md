---
layout: post
title: "Translating Mathematical Formula Images to LaTeX Sequences Using Deep Neural Networks with Sequence-level Training"
date: 2019-08-29 18:33:21
categories: arXiv_CV
tags: arXiv_CV Attention Reinforcement_Learning CNN RNN Language_Model Relation
author: Zelun Wang, Jyh-Charn Liu
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper we propose a deep neural network model with an encoder-decoder architecture that translates images of math formulas into their LaTeX markup sequences. The encoder is a convolutional neural network (CNN) that transforms images into a group of feature maps. To better capture the spatial relationships of math symbols, the feature maps are augmented with 2D positional encoding before being unfolded into a vector. The decoder is a stacked bidirectional long short-term memory (LSTM) model integrated with soft attention mechanism, which works as a language model to translate the encoder output into a sequence of LaTeX tokens. The neural network is trained in two steps. The first step is token-level training using the Maximum-Likelihood Estimation (MLE) as the objective function. Next, at completion of the token-level training, we advance to a sequence-level training based on a new objective function inspired by the policy gradient algorithm from reinforcement learning. Our design also overcomes the exposure bias problem by closing the feedback loop in the decoder during sequence-level training, i.e., feeding in the predicted token instead of the ground truth token at every time step. The model is trained and evaluated on the IM2LATEX-100K dataset and shows state-of-the-art performance on both sequence-based and image-based evaluation metrics.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1908.11415](http://arxiv.org/abs/1908.11415)

##### PDF
[http://arxiv.org/pdf/1908.11415](http://arxiv.org/pdf/1908.11415)


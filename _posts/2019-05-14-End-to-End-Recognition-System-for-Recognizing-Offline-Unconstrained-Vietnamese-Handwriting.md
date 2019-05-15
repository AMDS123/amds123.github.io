---
layout: post
title: "End to End Recognition System for Recognizing Offline Unconstrained Vietnamese Handwriting"
date: 2019-05-14 03:59:46
categories: arXiv_CV
tags: arXiv_CV Image_Caption Attention Caption RNN Language_Model Recognition
author: Anh Duc Le, Hung Tuan Nguyen, Masaki Nakagawa
mathjax: true
---

* content
{:toc}

##### Abstract
Inspired by recent successes in neural machine translation and image caption generation, we present an attention based encoder decoder model (AED) to recognize Vietnamese Handwritten Text. The model composes of two parts: a DenseNet for extracting invariant features, and a Long Short-Term Memory network (LSTM) with an attention model incorporated for generating output text (LSTM decoder), which are connected from the CNN part to the attention model. The input of the CNN part is a handwritten text image and the target of the LSTM decoder is the corresponding text of the input image. Our model is trained end-to-end to predict the text from a given input image since all the parts are differential components. In the experiment section, we evaluate our proposed AED model on the VNOnDB-Word and VNOnDB-Line datasets to verify its efficiency. The experiential results show that our model achieves 12.30% of word error rate without using any language model. This result is competitive with the handwriting recognition system provided by Google in the Vietnamese Online Handwritten Text Recognition competition.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1905.05381](https://arxiv.org/abs/1905.05381)

##### PDF
[https://arxiv.org/pdf/1905.05381](https://arxiv.org/pdf/1905.05381)


---
layout: post
title: "Token-level and sequence-level loss smoothing for RNN language models"
date: 2018-05-14 08:37:50
categories: arXiv_CV
tags: arXiv_CV Image_Caption Caption RNN Language_Model Prediction
author: Maha Elbayad, Laurent Besacier, Jakob Verbeek
mathjax: true
---

* content
{:toc}

##### Abstract
Despite the effectiveness of recurrent neural network language models, their maximum likelihood estimation suffers from two limitations. It treats all sentences that do not match the ground truth as equally poor, ignoring the structure of the output space. Second, it suffers from "exposure bias": during training tokens are predicted given ground-truth sequences, while at test time prediction is conditioned on generated output sequences. To overcome these limitations we build upon the recent reward augmented maximum likelihood approach \ie sequence-level smoothing that encourages the model to predict sentences close to the ground truth according to a given performance metric. We extend this approach to token-level loss smoothing, and propose improvements to the sequence-level smoothing approach. Our experiments on two different tasks, image captioning and machine translation, show that token-level and sequence-level loss smoothing are complementary, and significantly improve results.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1805.05062](https://arxiv.org/abs/1805.05062)

##### PDF
[https://arxiv.org/pdf/1805.05062](https://arxiv.org/pdf/1805.05062)


---
layout: post
title: "CNN+CNN: Convolutional Decoders for Image Captioning"
date: 2018-05-23 09:16:59
categories: arXiv_CV
tags: arXiv_CV Image_Caption Attention Caption CNN RNN
author: Qingzhong Wang, Antoni B. Chan
mathjax: true
---

* content
{:toc}

##### Abstract
Image captioning is a challenging task that combines the field of computer vision and natural language processing. A variety of approaches have been proposed to achieve the goal of automatically describing an image, and recurrent neural network (RNN) or long-short term memory (LSTM) based models dominate this field. However, RNNs or LSTMs cannot be calculated in parallel and ignore the underlying hierarchical structure of a sentence. In this paper, we propose a framework that only employs convolutional neural networks (CNNs) to generate captions. Owing to parallel computing, our basic model is around 3 times faster than NIC (an LSTM-based model) during training time, while also providing better results. We conduct extensive experiments on MSCOCO and investigate the influence of the model width and depth. Compared with LSTM-based models that apply similar attention mechanisms, our proposed models achieves comparable scores of BLEU-1,2,3,4 and METEOR, and higher scores of CIDEr. We also test our model on the paragraph annotation dataset, and get higher CIDEr score compared with hierarchical LSTMs

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1805.09019](https://arxiv.org/abs/1805.09019)

##### PDF
[https://arxiv.org/pdf/1805.09019](https://arxiv.org/pdf/1805.09019)


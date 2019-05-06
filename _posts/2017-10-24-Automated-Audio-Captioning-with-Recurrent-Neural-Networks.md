---
layout: post
title: "Automated Audio Captioning with Recurrent Neural Networks"
date: 2017-10-24 11:36:08
categories: arXiv_CV
tags: arXiv_CV Image_Caption Caption RNN Classification
author: Konstantinos Drossos, Sharath Adavanne, Tuomas Virtanen
mathjax: true
---

* content
{:toc}

##### Abstract
We present the first approach to automated audio captioning. We employ an encoder-decoder scheme with an alignment model in between. The input to the encoder is a sequence of log mel-band energies calculated from an audio file, while the output is a sequence of words, i.e. a caption. The encoder is a multi-layered, bi-directional gated recurrent unit (GRU) and the decoder a multi-layered GRU with a classification layer connected to the last GRU of the decoder. The classification layer and the alignment model are fully connected layers with shared weights between timesteps. The proposed method is evaluated using data drawn from a commercial sound effects library, ProSound Effects. The resulting captions were rated through metrics utilized in machine translation and image captioning fields. Results from metrics show that the proposed method can predict words appearing in the original caption, but not always correctly ordered.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1706.10006](https://arxiv.org/abs/1706.10006)

##### PDF
[https://arxiv.org/pdf/1706.10006](https://arxiv.org/pdf/1706.10006)


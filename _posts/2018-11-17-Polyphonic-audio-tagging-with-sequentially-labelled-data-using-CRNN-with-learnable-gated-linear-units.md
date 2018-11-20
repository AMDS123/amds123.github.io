---
layout: post
title: "Polyphonic audio tagging with sequentially labelled data using CRNN with learnable gated linear units"
date: 2018-11-17 01:19:25
categories: arXiv_SD
tags: arXiv_SD CNN RNN Classification
author: Yuanbo Hou, Qiuqiang Kong, Jun Wang, Shengchen Li
mathjax: true
---

* content
{:toc}

##### Abstract
Audio tagging aims to detect the types of sound events occurring in an audio recording. To tag the polyphonic audio recordings, we propose to use Connectionist Temporal Classification (CTC) loss function on the top of Convolutional Recurrent Neural Network (CRNN) with learnable Gated Linear Units (GLU-CTC), based on a new type of audio label data: Sequentially Labelled Data (SLD). In GLU-CTC, CTC objective function maps the frame-level probability of labels to clip-level probability of labels. To compare the mapping ability of GLU-CTC for sound events, we train a CRNN with GLU based on Global Max Pooling (GLU-GMP) and a CRNN with GLU based on Global Average Pooling (GLU-GAP). And we also compare the proposed GLU-CTC system with the baseline system, which is a CRNN trained using CTC loss function without GLU. The experiments show that the GLU-CTC achieves an Area Under Curve (AUC) score of 0.882 in audio tagging, outperforming the GLU-GMP of 0.803, GLU-GAP of 0.766 and baseline system of 0.837. That means based on the same CRNN model with GLU, the performance of CTC mapping is better than the GMP and GAP mapping. Given both based on the CTC mapping, the CRNN with GLU outperforms the CRNN without GLU.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1811.07072](http://arxiv.org/abs/1811.07072)

##### PDF
[http://arxiv.org/pdf/1811.07072](http://arxiv.org/pdf/1811.07072)


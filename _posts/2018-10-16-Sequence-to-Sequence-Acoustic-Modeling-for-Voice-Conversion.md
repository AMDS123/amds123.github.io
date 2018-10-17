---
layout: post
title: "Sequence-to-Sequence Acoustic Modeling for Voice Conversion"
date: 2018-10-16 08:11:32
categories: arXiv_SD
tags: arXiv_SD Attention Speech_Recognition Recognition
author: Jing-Xuan Zhang, Zhen-Hua Ling, Li-Rong Dai, Li-Juan Liu, Yuan Jiang, Li-Rong Dai
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper, a neural network named Sequence-to- sequence ConvErsion NeTwork (SCENT) is presented for acoustic modeling in voice conversion. At training stage, a SCENT model is estimated by aligning the feature sequences of source and target speakers implicitly using attention mechanism. At conversion stage, acoustic features and durations of source utterances are converted simultaneously using the unified acoustic model, which is difficult to be achieved in conventional method. Mel-scale spectrograms are adopted as acoustic features which contain both excitation and vocal tract descriptions of speech signals. The bottleneck features extracted from source speech using an automatic speech recognition (ASR) model are appended as auxiliary input. A WaveNet vocoder conditioned on mel- spectrograms is built to reconstruct waveforms from the output of the SCENT model. Experimental results show that our proposed method achieved better objective and subjective performance than the baseline methods using Gaussian mixture models (GMM) and deep neural networks (DNN) as acoustic models. This proposed method also outperformed our previous work which achieved the top rank in Voice Conversion Challenge 2018. Ablation tests further confirm the effectiveness of appending bottleneck features and using attention module in our proposed method.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1810.06865](http://arxiv.org/abs/1810.06865)

##### PDF
[http://arxiv.org/pdf/1810.06865](http://arxiv.org/pdf/1810.06865)


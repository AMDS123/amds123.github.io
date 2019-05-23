---
layout: post
title: "FastSpeech: Fast, Robust and Controllable Text to Speech"
date: 2019-05-22 17:50:21
categories: arXiv_CL
tags: arXiv_CL Attention Inference Prediction
author: Yi Ren, Yangjun Ruan, Xu Tan, Tao Qin, Sheng Zhao, Zhou Zhao, Tie-Yan Liu
mathjax: true
---

* content
{:toc}

##### Abstract
Neural network based end-to-end text to speech (TTS) has significantly improved the quality of synthesized speech. Prominent methods (e.g., Tacotron 2) usually first generate mel-spectrogram from text, and then synthesize speech from mel-spectrogram using vocoder such as WaveNet. Compared with traditional concatenative and statistical parametric approaches, neural network based end-to-end models suffer from slow inference speed, and the synthesized speech is usually not robust (i.e., some words are skipped or repeated) and lack of controllability (voice speed or prosody control). In this work, we propose a novel feed-forward network based on Transformer to generate mel-spectrogram in parallel for TTS. Specifically, we extract attention alignments from an encoder-decoder based teacher model for phoneme duration prediction, which is used by a length regulator to expand the source phoneme sequence to match the length of target mel-sprectrogram sequence for parallel mel-sprectrogram generation. Experiments on the LJSpeech dataset show that our parallel model matches autoregressive models in terms of speech quality, nearly eliminates the skipped words and repeated words, and can adjust voice speed smoothly. Most importantly, compared with autoregressive models, our model speeds up the mel-sprectrogram generation by 270x. Therefore, we call our model FastSpeech. We will release the code on Github.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1905.09263](http://arxiv.org/abs/1905.09263)

##### PDF
[http://arxiv.org/pdf/1905.09263](http://arxiv.org/pdf/1905.09263)


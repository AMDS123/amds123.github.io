---
layout: post
title: "OMG Emotion Challenge - ExCouple Team"
date: 2018-05-02 21:53:23
categories: arXiv_SD
tags: arXiv_SD GAN CNN Prediction Recognition
author: Ingryd Pereira, Diego Santos
mathjax: true
---

* content
{:toc}

##### Abstract
The proposed model is only for the audio module. All videos in the OMG Emotion Dataset are converted to WAV files. The proposed model makes use of semi-supervised learning for the emotion recognition. A GAN is trained with unsupervised learning, with another database (IEMOCAP), and part of the GAN structure (part of the autoencoder) will be used for the audio representation. The audio spectrogram will be extracted in 1-second windows of 16khz frequency, and this will serve as input to the model of audio representation trained with another database in an unsupervised way. This audio representation will serve as input to a convolutional network and a Dense layer with 'tanh' activation that performs the prediction of Arousal and Valence values. For joining the 1-second pieces of audio, the median of the predicted values of a given utterance will be taken.

##### Abstract (translated by Google)
建议的模型仅适用于音频模块。 OMG Emotion Dataset中的所有视频都将转换为WAV文件。该模型利用半监督学习进行情感识别。 GAN通过无监督学习训练，另一个数据库（IEMOCAP）和部分GAN结构（autoencoder的一部分）将用于音频表示。音频谱图将在16khz频率的1秒钟窗口中提取，并且这将用作以无监督方式用另一个数据库训练的音频表示模型的输入。这种音频表示将作为卷积网络的输入和具有'tanh'激活的密集层来执行唤醒和价值的预测。为了加入1秒钟的音频，将获得给定话语的预测值的中值。

##### URL
[http://arxiv.org/abs/1805.01576](http://arxiv.org/abs/1805.01576)

##### PDF
[http://arxiv.org/pdf/1805.01576](http://arxiv.org/pdf/1805.01576)


---
layout: post
title: "Transfer Learning from Speaker Verification to Multispeaker Text-To-Speech Synthesis"
date: 2018-06-12 14:29:22
categories: arXiv_CL
tags: arXiv_CL Knowledge Embedding Transfer_Learning
author: Ye Jia, Yu Zhang, Ron J. Weiss, Quan Wang, Jonathan Shen, Fei Ren, Zhifeng Chen, Patrick Nguyen, Ruoming Pang, Ignacio Lopez Moreno, Yonghui Wu
mathjax: true
---

* content
{:toc}

##### Abstract
We describe a neural network-based system for text-to-speech (TTS) synthesis that is able to generate speech audio in the voice of many different speakers, including those unseen during training. Our system consists of three independently trained components: (1) a speaker encoder network, trained on a speaker verification task using an independent dataset of noisy speech from thousands of speakers without transcripts, to generate a fixed-dimensional embedding vector from seconds of reference speech from a target speaker; (2) a sequence-to-sequence synthesis network based on Tacotron 2, which generates a mel spectrogram from text, conditioned on the speaker embedding; (3) an auto-regressive WaveNet-based vocoder that converts the mel spectrogram into a sequence of time domain waveform samples. We demonstrate that the proposed model is able to transfer the knowledge of speaker variability learned by the discriminatively-trained speaker encoder to the new task, and is able to synthesize natural speech from speakers that were not seen during training. We quantify the importance of training the speaker encoder on a large and diverse speaker set in order to obtain the best generalization performance. Finally, we show that randomly sampled speaker embeddings can be used to synthesize speech in the voice of novel speakers dissimilar from those used in training, indicating that the model has learned a high quality speaker representation.

##### Abstract (translated by Google)
我们描述了一种基于神经网络的文本到语音（TTS）合成系统，能够在许多不同讲话者的声音中产生语音音频，包括在训练期间看不到的那些讲话者。我们的系统由三个独立训练的组件构成：（1）扬声器编码器网络，使用来自数千个没有转录本的扬声器的有噪语音的独立数据集对讲话者验证任务进行训练，以从参考语音的秒数生成固定维嵌入向量来自目标说话人; （2）基于Tacotron 2的序列到序列综合网络，它根据说话人嵌入条件从文本生成mel谱图; （3）基于WaveNet的自回归声码器，将mel谱图转换为时域波形采样序列。我们证明了所提出的模型能够将由差异训练的说话人编码器学习到的说话者变化的知识传递给新的任务，并且能够从训练期间没有看到的说话者合成自然语音。为了获得最佳泛化性能，我们量化了在大型多样化扬声器集上训练扬声器编码器的重要性。最后，我们表明，随机采样的说话人嵌入可以用来合成与训练中使用的不同的新说话人语音中的语音，表明该模型已经学习了高质量说话人表示。

##### URL
[http://arxiv.org/abs/1806.04558](http://arxiv.org/abs/1806.04558)

##### PDF
[http://arxiv.org/pdf/1806.04558](http://arxiv.org/pdf/1806.04558)


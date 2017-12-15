---
layout: post
title: "Dynamic Layer Normalization for Adaptive Neural Acoustic Modeling in Speech Recognition"
date: 2017-07-19 13:04:09
categories: arXiv_CL
tags: arXiv_CL Speech_Recognition RNN Recognition
author: Taesup Kim, Inchul Song, Yoshua Bengio
mathjax: true
---

* content
{:toc}

##### Abstract
Layer normalization is a recently introduced technique for normalizing the activities of neurons in deep neural networks to improve the training speed and stability. In this paper, we introduce a new layer normalization technique called Dynamic Layer Normalization (DLN) for adaptive neural acoustic modeling in speech recognition. By dynamically generating the scaling and shifting parameters in layer normalization, DLN adapts neural acoustic models to the acoustic variability arising from various factors such as speakers, channel noises, and environments. Unlike other adaptive acoustic models, our proposed approach does not require additional adaptation data or speaker information such as i-vectors. Moreover, the model size is fixed as it dynamically generates adaptation parameters. We apply our proposed DLN to deep bidirectional LSTM acoustic models and evaluate them on two benchmark datasets for large vocabulary ASR experiments: WSJ and TED-LIUM release 2. The experimental results show that our DLN improves neural acoustic models in terms of transcription accuracy by dynamically adapting to various speakers and environments.

##### Abstract (translated by Google)
层规范化是最近引入的用于规范化深度神经网络中的神经元活动以提高训练速度和稳定性的技术。在本文中，我们引入了一种称为动态层标准化（DLN）的新层归一化技术，用于语音识别中的自适应神经声学建模。通过在层规范化中动态生成缩放和移位参数，DLN使神经声学模型适用于由扬声器，声道噪声和环境等各种因素引起的声学变化。与其他自适应声学模型不同，我们提出的方法不需要额外的自适应数据或扬声器信息，如i向量。此外，模型的大小是固定的，因为它动态地生成适应参数。我们将我们提出的DLN应用于深层双向LSTM声学模型，并在两个基准数据集上进行评估，以用于大型词汇ASR实验：WSJ和TED-LIUM版本2.实验结果表明，我们的DLN动态地改进了神经声学模型的转录精度适应各种扬声器和环境。

##### URL
[https://arxiv.org/abs/1707.06065](https://arxiv.org/abs/1707.06065)

##### PDF
[https://arxiv.org/pdf/1707.06065](https://arxiv.org/pdf/1707.06065)


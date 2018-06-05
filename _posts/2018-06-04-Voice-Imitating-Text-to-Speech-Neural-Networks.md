---
layout: post
title: "Voice Imitating Text-to-Speech Neural Networks"
date: 2018-06-04 02:10:48
categories: arXiv_SD
tags: arXiv_SD Embedding
author: Younggun Lee, Taesu Kim, Soo-Young Lee
mathjax: true
---

* content
{:toc}

##### Abstract
We propose a neural text-to-speech (TTS) model that can imitate a new speaker's voice using only a small amount of speech sample. We demonstrate voice imitation using only a 6-seconds long speech sample without any other information such as transcripts. Our model also enables voice imitation instantly without additional training of the model. We implemented the voice imitating TTS model by combining a speaker embedder network with a state-of-the-art TTS model, Tacotron. The speaker embedder network takes a new speaker's speech sample and returns a speaker embedding. The speaker embedding with a target sentence are fed to Tacotron, and speech is generated with the new speaker's voice. We show that the speaker embeddings extracted by the speaker embedder network can represent the latent structure in different voices. The generated speech samples from our model have comparable voice quality to the ones from existing multi-speaker TTS models.

##### Abstract (translated by Google)
我们提出了一种神经文本到语音（TTS）模型，可以使用少量的语音样本来模仿新的说话者的语音。我们仅使用6秒长的语音样本来演示语音模仿，而没有任何其他信息，如成绩单。我们的模型也可以立即启用语音模仿，无需对模型进行额外的培训。我们通过将扬声器嵌入器网络与最先进的TTS模型Tacotron相结合，实现了语音模拟TTS模型。扬声器嵌入器网络采用新扬声器的语音采样并返回扬声器嵌入。用目标句子嵌入说话者被送到Tacotron，并用新的说话者语音生成语音。我们证明，由说话人嵌入网络提取的说话人嵌入可以表示不同语音中的潜在结构。我们模型生成的语音样本具有与现有多扬声器TTS模型相当的语音质量。

##### URL
[http://arxiv.org/abs/1806.00927](http://arxiv.org/abs/1806.00927)

##### PDF
[http://arxiv.org/pdf/1806.00927](http://arxiv.org/pdf/1806.00927)


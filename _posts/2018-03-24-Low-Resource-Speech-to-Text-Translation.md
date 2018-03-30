---
layout: post
title: "Low-Resource Speech-to-Text Translation"
date: 2018-03-24 21:17:52
categories: arXiv_CL
tags: arXiv_CL Speech_Recognition Recognition
author: Sameer Bansal, Herman Kamper, Karen Livescu, Adam Lopez, Sharon Goldwater
mathjax: true
---

* content
{:toc}

##### Abstract
Speech-to-text translation has many potential applications for low-resource languages, but the typical approach of cascading speech recognition with machine translation is often impossible, since the transcripts needed to train a speech recognizer are usually not available for low-resource languages. Recent work has found that neural encoder-decoder models can learn to directly translate foreign speech in high-resource scenarios, without the need for intermediate transcription. We investigate whether this approach also works in settings where both data and computation are limited. To make the approach efficient, we make several architectural changes, including a change from character-level to word-level decoding. We find that this choice yields crucial speed improvements that allow us to train with fewer computational resources, yet still performs well on frequent words. We explore models trained on between 20 and 160 hours of data, and find that although models trained on less data have considerably lower BLEU scores, they can still predict words with relatively high precision and recall---around 50% for a model trained on 50 hours of data, versus around 60% for the full 160 hour model. Thus, they may still be useful for some low-resource scenarios.

##### Abstract (translated by Google)
语音到文本翻译对于低资源语言有许多潜在的应用，但是将机器翻译级联语音识别的典型方法通常是不可能的，因为训练语音识别器所需的成绩单通常不适用于低资源语言。最近的研究发现，神经编码器 - 解码器模型可以学习在高资源情况下直接翻译外语，而不需要中间转录。我们调查这种方法是否也适用于数据和计算都有限的环境。为了使这种方法高效，我们进行了一些架构变更，包括从字符级到字级解码的变化。我们发现这种选择产生了关键的速度改进，使我们能够用更少的计算资源进行训练，但仍能在频繁的单词上表现良好。我们探索在20到160小时的数据之间训练的模型，发现虽然训练在较少数据上的模型的BLEU得分显着较低，但他们仍然可以以较高的精度预测单词并且回忆 - 对于训练过的模型，约有50％ 50小时的数据，而整个160小时的模型约为60％。因此，它们对于一些低资源情况可能仍然有用。

##### URL
[https://arxiv.org/abs/1803.09164](https://arxiv.org/abs/1803.09164)

##### PDF
[https://arxiv.org/pdf/1803.09164](https://arxiv.org/pdf/1803.09164)


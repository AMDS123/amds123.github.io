---
layout: post
title: "Improved Chord Recognition by Combining Duration and Harmonic Language Models"
date: 2018-08-16 03:34:27
categories: arXiv_SD
tags: arXiv_SD RNN Language_Model Prediction Relation Recognition
author: Filip Korzeniowski, Gerhard Widmer
mathjax: true
---

* content
{:toc}

##### Abstract
Chord recognition systems typically comprise an acoustic model that predicts chords for each audio frame, and a temporal model that casts these predictions into labelled chord segments. However, temporal models have been shown to only smooth predictions, without being able to incorporate musical information about chord progressions. Recent research discovered that it might be the low hierarchical level such models have been applied to (directly on audio frames) which prevents learning musical relationships, even for expressive models such as recurrent neural networks (RNNs). However, if applied on the level of chord sequences, RNNs indeed can become powerful chord predictors. In this paper, we disentangle temporal models into a harmonic language model---to be applied on chord sequences---and a chord duration model that connects the chord-level predictions of the language model to the frame-level predictions of the acoustic model. In our experiments, we explore the impact of each model on the chord recognition score, and show that using harmonic language and duration models improves the results.

##### Abstract (translated by Google)
和弦识别系统通常包括预测每个音频帧的和弦的声学模型，以及将这些预测投射到标记的和弦段中的时间模型。然而，时间模型已经被证明仅仅是平滑的预测，而不能结合关于和弦进行的音乐信息。最近的研究发现，这种模型可能是低层次级别（直接在音频帧上），即使对于诸如递归神经网络（RNN）等表达模型，也会阻止学习音乐关系。但是，如果应用于和弦序列的级别，RNN确实可以成为强大的和弦预测器。在本文中，我们将时间模型解析为一个谐波语言模型---应用于和弦序列---和一个和弦持续时间模型，它连接语言模型的和弦级预测与声学的帧级预测模型。在我们的实验中，我们探索了每个模型对和弦识别得分的影响，并表明使用和声语言和持续时间模型可以改善结果。

##### URL
[http://arxiv.org/abs/1808.05335](http://arxiv.org/abs/1808.05335)

##### PDF
[http://arxiv.org/pdf/1808.05335](http://arxiv.org/pdf/1808.05335)


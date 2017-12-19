---
layout: post
title: "Attention-Based Models for Speech Recognition"
date: 2015-06-24 19:10:33
categories: arXiv_CV
tags: arXiv_CV Image_Caption Attention Speech_Recognition Caption Recognition
author: Jan Chorowski, Dzmitry Bahdanau, Dmitriy Serdyuk, Kyunghyun Cho, Yoshua Bengio
mathjax: true
---

* content
{:toc}

##### Abstract
Recurrent sequence generators conditioned on input data through an attention mechanism have recently shown very good performance on a range of tasks in- cluding machine translation, handwriting synthesis and image caption gen- eration. We extend the attention-mechanism with features needed for speech recognition. We show that while an adaptation of the model used for machine translation in reaches a competitive 18.7% phoneme error rate (PER) on the TIMIT phoneme recognition task, it can only be applied to utterances which are roughly as long as the ones it was trained on. We offer a qualitative explanation of this failure and propose a novel and generic method of adding location-awareness to the attention mechanism to alleviate this issue. The new method yields a model that is robust to long inputs and achieves 18% PER in single utterances and 20% in 10-times longer (repeated) utterances. Finally, we propose a change to the at- tention mechanism that prevents it from concentrating too much on single frames, which further reduces PER to 17.6% level.

##### Abstract (translated by Google)
通过注意机制对输入数据进行处理的循环序列生成器最近在包括机器翻译，手写合成和图像字幕生成在内的各种任务中表现出非常好的性能。我们通过语音识别所需的特性扩展了注意机制。我们表明，尽管用于机器翻译的模型的适应在TIMIT音素识别任务中达到了有竞争力的18.7％的音素错误率（PER），但是它只能被应用于与其被训练的长度大致相同的话语上。我们提供了这种失败的定性解释，并提出了一种新颖的，通用的方法来增加位置意识的注意机制，以缓解这个问题。新方法产生的模型对于长时间投入是稳健的，在单个话语中PER达到18％，在10倍长（重复）话语中PER达到20％。最后，我们建议改变注意机制，以防止它过分集中在单帧上，这进一步将PER降低到17.6％的水平。

##### URL
[https://arxiv.org/abs/1506.07503](https://arxiv.org/abs/1506.07503)

##### PDF
[https://arxiv.org/pdf/1506.07503](https://arxiv.org/pdf/1506.07503)


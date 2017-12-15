---
layout: post
title: "Towards speech-to-text translation without speech recognition"
date: 2017-02-13 16:30:23
categories: arXiv_SD
tags: arXiv_SD Face Speech_Recognition Recognition
author: Sameer Bansal, Herman Kamper, Adam Lopez, Sharon Goldwater
mathjax: true
---

* content
{:toc}

##### Abstract
We explore the problem of translating speech to text in low-resource scenarios where neither automatic speech recognition (ASR) nor machine translation (MT) are available, but we have training data in the form of audio paired with text translations. We present the first system for this problem applied to a realistic multi-speaker dataset, the CALLHOME Spanish-English speech translation corpus. Our approach uses unsupervised term discovery (UTD) to cluster repeated patterns in the audio, creating a pseudotext, which we pair with translations to create a parallel text and train a simple bag-of-words MT model. We identify the challenges faced by the system, finding that the difficulty of cross-speaker UTD results in low recall, but that our system is still able to correctly translate some content words in test data.

##### Abstract (translated by Google)
我们研究在自动语音识别（ASR）和机器翻译（MT）都不可用的低资源情况下将语音转换为文本的问题，但是我们已经将音频形式的训练数据与文本翻译配对。我们将这个问题的第一个系统应用到一个现实的多说话人数据集，即CALLHOME西班牙语 - 英语语音翻译语料库。我们的方法使用无监督词条发现（UTD）对音频中的重复模式进行聚类，创建一个伪文本，我们将其与翻译结合起来创建一个平行文本，并训练一个简单的词袋式MT模型。我们发现系统所面临的挑战，发现跨语言UTD的难度导致回忆率低，但是我们的系统仍然能够正确翻译测试数据中的一些内容字。

##### URL
[https://arxiv.org/abs/1702.03856](https://arxiv.org/abs/1702.03856)

##### PDF
[https://arxiv.org/pdf/1702.03856](https://arxiv.org/pdf/1702.03856)


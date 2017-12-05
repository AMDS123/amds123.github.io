---
layout: post
title:  Mitigating the Impact of Speech Recognition Errors on Chatbot using Sequence-to-Sequence Model
date:   2017-12-05 18:20:28
categories: CL
tags: CL
author: Pin-Jung Chen, I-Hung Hsu, Yi-Yao Huang, Hung-Yi Lee
---

* content
{:toc}

##### Abstract
We apply sequence-to-sequence model to mitigate the impact of speech recognition errors on open domain end-to-end dialog generation. We cast the task as a domain adaptation problem where ASR transcriptions and original text are in two different domains. In this paper, our proposed model includes two individual encoders for each domain data and make their hidden states similar to ensure the decoder predict the same dialog text. The method shows that the sequence-to-sequence model can learn the ASR transcriptions and original text pair having the same meaning and eliminate the speech recognition errors. Experimental results on Cornell movie dialog dataset demonstrate that the domain adaption system help the spoken dialog system generate more similar responses with the original text answers.

##### Abstract (translated by Google)
我们应用序列 - 序列模型来减轻语音识别错误对开放域端到端对话生成的影响。我们把这个任务作为一个领域适应问题来处理，其中ASR的转录和原文在两个不同的领域。在本文中，我们提出的模型包括两个单独的编码器为每个领域的数据，并使他们的隐藏状态相似，以确保解码器预测相同的对话文本。该方法表明序列 - 序列模型可以学习具有相同含义的ASR转录和原文对，消除语音识别错误。康奈尔电影对话数据集上的实验结果表明，域自适应系统可以帮助口语对话系统产生更多与原文答案相似的答案。


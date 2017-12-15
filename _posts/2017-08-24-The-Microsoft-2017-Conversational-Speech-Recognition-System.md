---
layout: post
title: "The Microsoft 2017 Conversational Speech Recognition System"
date: 2017-08-24 23:30:37
categories: arXiv_CL
tags: arXiv_CL Speech_Recognition RNN Language_Model Recognition
author: W. Xiong, L. Wu, F. Alleva, J. Droppo, X. Huang, A. Stolcke
mathjax: true
---

* content
{:toc}

##### Abstract
We describe the 2017 version of Microsoft's conversational speech recognition system, in which we update our 2016 system with recent developments in neural-network-based acoustic and language modeling to further advance the state of the art on the Switchboard speech recognition task. The system adds a CNN-BLSTM acoustic model to the set of model architectures we combined previously, and includes character-based and dialog session aware LSTM language models in rescoring. For system combination we adopt a two-stage approach, whereby subsets of acoustic models are first combined at the senone/frame level, followed by a word-level voting via confusion networks. We also added a confusion network rescoring step after system combination. The resulting system yields a 5.1\% word error rate on the 2000 Switchboard evaluation set.

##### Abstract (translated by Google)
我们描述了微软的对话式语音识别系统2017版，在这个系统中，我们更新了我们的2016系统，最近在基于神经网络的声学和语言建模方面取得了新的进展，从而进一步提高了交换机语音识别任务的最新技术水平。系统为我们之前合并的一组模型体系结构添加了一个CNN-BLSTM声学模型，并且在重新分类中包括基于字符和对话会话的LSTM语言模型。对于系统组合，我们采用两阶段方法，其中声学模型的子集首先在句音/帧级组合，然后通过混淆网络进行单词级投票。系统组合后，我们还添加了混淆网络重新调整步骤。由此产生的系统在2000总机评估集上产生5.1 \％的字错误率。

##### URL
[https://arxiv.org/abs/1708.06073](https://arxiv.org/abs/1708.06073)

##### PDF
[https://arxiv.org/pdf/1708.06073](https://arxiv.org/pdf/1708.06073)


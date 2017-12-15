---
layout: post
title: "Voice Conversion Using Sequence-to-Sequence Learning of Context Posterior Probabilities"
date: 2017-08-07 02:42:01
categories: arXiv_CL
tags: arXiv_CL Speech_Recognition Recognition
author: Hiroyuki Miyoshi, Yuki Saito, Shinnosuke Takamichi, Hiroshi Saruwatari
mathjax: true
---

* content
{:toc}

##### Abstract
Voice conversion (VC) using sequence-to-sequence learning of context posterior probabilities is proposed. Conventional VC using shared context posterior probabilities predicts target speech parameters from the context posterior probabilities estimated from the source speech parameters. Although conventional VC can be built from non-parallel data, it is difficult to convert speaker individuality such as phonetic property and speaking rate contained in the posterior probabilities because the source posterior probabilities are directly used for predicting target speech parameters. In this work, we assume that the training data partly include parallel speech data and propose sequence-to-sequence learning between the source and target posterior probabilities. The conversion models perform non-linear and variable-length transformation from the source probability sequence to the target one. Further, we propose a joint training algorithm for the modules. In contrast to conventional VC, which separately trains the speech recognition that estimates posterior probabilities and the speech synthesis that predicts target speech parameters, our proposed method jointly trains these modules along with the proposed probability conversion modules. Experimental results demonstrate that our approach outperforms the conventional VC.

##### Abstract (translated by Google)
提出了使用上下文概率的序列到序列学习的语音转换（VC）。使用共享上下文后验概率的常规VC根据源语音参数估计的上下文后验概率来预测目标语音参数。虽然传统的VC可以由非平行数据构建，但由于后验概率直接用于预测目标语音参数，所以很难将后置概率中包含的语音属性和语音速率等语音个性进行转换。在这项工作中，我们假设训练数据部分包含并行语音数据，并提出源和目标后验概率之间的序列到序列学习。转换模型执行从源概率序列到目标概率序列的非线性和可变长度转换。此外，我们提出了一个模块的联合训练算法。与传统的VC（分别训练估计后验概率的语音识别和预测目标语音参数的语音合成）相比，我们提出的方法与所提出的概率转换模块一起联合训练这些模块。实验结果表明，我们的方法胜过传统的VC。

##### URL
[https://arxiv.org/abs/1704.02360](https://arxiv.org/abs/1704.02360)

##### PDF
[https://arxiv.org/pdf/1704.02360](https://arxiv.org/pdf/1704.02360)


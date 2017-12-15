---
layout: post
title: "Deep LSTM for Large Vocabulary Continuous Speech Recognition"
date: 2017-03-21 08:24:50
categories: arXiv_SD
tags: arXiv_SD Speech_Recognition Transfer_Learning RNN Recognition
author: Xu Tian, Jun Zhang, Zejun Ma, Yi He, Juan Wei, Peihao Wu, Wenchang Situ, Shuai Li, Yang Zhang
mathjax: true
---

* content
{:toc}

##### Abstract
Recurrent neural networks (RNNs), especially long short-term memory (LSTM) RNNs, are effective network for sequential task like speech recognition. Deeper LSTM models perform well on large vocabulary continuous speech recognition, because of their impressive learning ability. However, it is more difficult to train a deeper network. We introduce a training framework with layer-wise training and exponential moving average methods for deeper LSTM models. It is a competitive framework that LSTM models of more than 7 layers are successfully trained on Shenma voice search data in Mandarin and they outperform the deep LSTM models trained by conventional approach. Moreover, in order for online streaming speech recognition applications, the shallow model with low real time factor is distilled from the very deep model. The recognition accuracy have little loss in the distillation process. Therefore, the model trained with the proposed training framework reduces relative 14\% character error rate, compared to original model which has the similar real-time capability. Furthermore, the novel transfer learning strategy with segmental Minimum Bayes-Risk is also introduced in the framework. The strategy makes it possible that training with only a small part of dataset could outperform full dataset training from the beginning.

##### Abstract (translated by Google)
递归神经网络（RNN），尤其是长时间短记忆（LSTM）RNN，是语音识别等连续任务的有效网络。由于其深刻的学习能力，深入的LSTM模型在大型词汇连续语音识别方面表现良好。但是，培养更深层次的网络则更为困难。我们引入了层次训练和指数移动平均方法的深层次LSTM模型的训练框架。这是一个有竞争力的框架，超过7层的LSTM模型成功地训练了神马语音搜索数据的普通话，并且胜过了通过传统方法训练的深层LSTM模型。此外，为了在线流式语音识别应用，从非常深的模型中提取具有低实时因子的浅层模型。识别精度在蒸馏过程中几乎没有损失。因此，与具有相似实时能力的原始模型相比，使用所提出的训练框架训练的模型减少了相对14％的字符错误率。此外，框架还引入了具有分段最小贝叶斯风险的新型转移学习策略。该策略使得仅用一小部分数据集进行训练就可以从一开始就胜过整个数据集训练。

##### URL
[https://arxiv.org/abs/1703.07090](https://arxiv.org/abs/1703.07090)

##### PDF
[https://arxiv.org/pdf/1703.07090](https://arxiv.org/pdf/1703.07090)


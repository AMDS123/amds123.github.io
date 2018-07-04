---
layout: post
title: "Weakly Supervised Deep Recurrent Neural Networks for Basic Dance Step Generation"
date: 2018-07-03 12:47:15
categories: arXiv_SD
tags: arXiv_SD Weakly_Supervised CNN RNN
author: Nelson Yalta, Shinji Watanabe, Kazuhiro Nakadai, Tetsuya Ogata
mathjax: true
---

* content
{:toc}

##### Abstract
A deep recurrent neural network with audio input is applied to model basic dance steps. The proposed model employs multilayered Long Short-Term Memory (LSTM) layers and convolutional layers to process the audio power spectrum. Then, another deep LSTM layer decodes the target dance sequence. This end-to-end approach has an auto-conditioned decode configuration that reduces accumulation of feedback error. Experimental results demonstrate that, after training using a small dataset, the model generates basic dance steps with low cross entropy and maintains a motion beat F-measure score similar to that of a baseline dancer. In addition, we investigate the use of a contrastive cost function for music-motion regulation. This cost function targets motion direction and maps similarities between music frames. Experimental result demonstrate that the cost function improves the motion beat f-score.

##### Abstract (translated by Google)
具有音频输入的深度递归神经网络被应用于模拟基本舞步。所提出的模型采用多层长短期记忆（LSTM）层和卷积层来处理音频功率谱。然后，另一个深LSTM层解码目标舞蹈序列。这种端到端方法具有自动调节解​​码配置，可减少反馈误差的累积。实验结果表明，在使用小数据集训练后，该模型生成具有低交叉熵的基本舞步并且保持与基线舞者类似的运动节拍F-测量分数。此外，我们还研究了对比成本函数在音乐运动调节中的应用。该成本函数以运动方向为目标并映射音乐帧之间的相似性。实验结果表明，成本函数改善了运动节拍f分数。

##### URL
[https://arxiv.org/abs/1807.01126](https://arxiv.org/abs/1807.01126)

##### PDF
[https://arxiv.org/pdf/1807.01126](https://arxiv.org/pdf/1807.01126)


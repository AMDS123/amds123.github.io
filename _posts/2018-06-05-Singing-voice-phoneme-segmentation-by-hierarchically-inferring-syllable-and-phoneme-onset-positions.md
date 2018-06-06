---
layout: post
title: "Singing voice phoneme segmentation by hierarchically inferring syllable and phoneme onset positions"
date: 2018-06-05 12:54:19
categories: arXiv_SD
tags: arXiv_SD Segmentation CNN Inference Detection
author: Rong Gong, Xavier Serra
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper, we tackle the singing voice phoneme segmentation problem in the singing training scenario by using language-independent information -- onset and prior coarse duration. We propose a two-step method. In the first step, we jointly calculate the syllable and phoneme onset detection functions (ODFs) using a convolutional neural network (CNN). In the second step, the syllable and phoneme boundaries and labels are inferred hierarchically by using a duration-informed hidden Markov model (HMM). To achieve the inference, we incorporate the a priori duration model as the transition probabilities and the ODFs as the emission probabilities into the HMM. The proposed method is designed in a language-independent way such that no phoneme class labels are used. For the model training and algorithm evaluation, we collect a new jingju (also known as Beijing or Peking opera) solo singing voice dataset and manually annotate the boundaries and labels at phrase, syllable and phoneme levels. The dataset is publicly available. The proposed method is compared with a baseline method based on hidden semi-Markov model (HSMM) forced alignment. The evaluation results show that the proposed method outperforms the baseline by a large margin regarding both segmentation and onset detection tasks.

##### Abstract (translated by Google)
在本文中，我们使用与语言无关的信息 - 起始和先前的粗略持续时间来处理歌唱训练场景中的歌声音素分段问题。我们提出了一个两步法。在第一步中，我们使用卷积神经网络（CNN）联合计算音节和音素起始检测函数（ODF）。在第二步中，通过使用持续时间通知的隐马尔可夫模型（HMM）来分层推断音节和音素边界和标签。为了实现推理，我们将先验持续时间模型作为转换概率，将ODF作为发射概率并入HMM。所提出的方法以与语言无关的方式设计，使得不使用音素类别标签。对于模型训练和算法评估，我们收集一个新的京剧（也被称为北京或京剧）独唱歌唱声音数据集，并手动注释短语，音节和音素层次的边界和标签。数据集是公开可用的。将所提出的方法与基于隐马尔可夫模型（HSMM）强制对齐的基线方法进行比较。评估结果显示，所提出的方法在分割和起始检测任务方面优于基线。

##### URL
[http://arxiv.org/abs/1806.01665](http://arxiv.org/abs/1806.01665)

##### PDF
[http://arxiv.org/pdf/1806.01665](http://arxiv.org/pdf/1806.01665)


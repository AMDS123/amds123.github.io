---
layout: post
title: "Learning Spatio-temporal Features with Partial Expression Sequences for on-the-Fly Prediction"
date: 2017-11-29 15:27:22
categories: arXiv_CV
tags: arXiv_CV Segmentation Prediction Recognition
author: Wissam J. Baddar, Yong Man Ro
mathjax: true
---

* content
{:toc}

##### Abstract
Spatio-temporal feature encoding is essential for encoding facial expression dynamics in video sequences. At test time, most spatio-temporal encoding methods assume that a temporally segmented sequence is fed to a learned model, which could require the prediction to wait until the full sequence is available to an auxiliary task that performs the temporal segmentation. This causes a delay in predicting the expression. In an interactive setting, such as affective interactive agents, such delay in the prediction could not be tolerated. Therefore, training a model that can accurately predict the facial expression "on-the-fly" (as they are fed to the system) is essential. In this paper, we propose a new spatio-temporal feature learning method, which would allow prediction with partial sequences. As such, the prediction could be performed on-the-fly. The proposed method utilizes an estimated expression intensity to generate dense labels, which are used to regulate the prediction model training with a novel objective function. As results, the learned spatio-temporal features can robustly predict the expression with partial (incomplete) expression sequences, on-the-fly. Experimental results showed that the proposed method achieved higher recognition rates compared to the state-of-the-art methods on both datasets. More importantly, the results verified that the proposed method improved the prediction frames with partial expression sequence inputs.

##### Abstract (translated by Google)
时空特征编码对于编码视频序列中的面部表情动态是必不可少的。在测试时间，大多数时空编码方法假设将时间分段的序列馈送到学习模型，这可能需要预测等待，直到全序列可用于执行时间分段的辅助任务。这导致预测表达延迟。在交互式环境中，如情感互动代理，这种预测的延迟是不能容忍的。因此，训练一个能准确预测面部表情的模型（当他们被送入系统时）是至关重要的。在本文中，我们提出了一种新的时空特征学习方法，可以用部分序列进行预测。因此，预测可以在即时执行。所提出的方法利用估计的表达强度来生成密集标签，其用于利用新的目标函数来调节预测模型训练。作为结果，学习的时空特征可以强有力地预测具有部分（不完整）表达序列的表达。实验结果表明，与两种数据集上的最先进的方法相比，所提出的方法实现了更高的识别率。更重要的是，结果验证了所提出的方法改进了具有部分表达序列输入的预测帧。

##### URL
[https://arxiv.org/abs/1711.10914](https://arxiv.org/abs/1711.10914)

##### PDF
[https://arxiv.org/pdf/1711.10914](https://arxiv.org/pdf/1711.10914)


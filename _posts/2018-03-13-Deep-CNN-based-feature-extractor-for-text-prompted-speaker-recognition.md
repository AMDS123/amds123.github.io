---
layout: post
title: "Deep CNN based feature extractor for text-prompted speaker recognition"
date: 2018-03-13 10:59:24
categories: arXiv_CL
tags: arXiv_CL CNN Deep_Learning Recognition
author: Sergey Novoselov, Oleg Kudashev, Vadim Schemelinin, Ivan Kremnev, Galina Lavrentyeva
mathjax: true
---

* content
{:toc}

##### Abstract
Deep learning is still not a very common tool in speaker verification field. We study deep convolutional neural network performance in the text-prompted speaker verification task. The prompted passphrase is segmented into word states - i.e. digits -to test each digit utterance separately. We train a single high-level feature extractor for all states and use cosine similarity metric for scoring. The key feature of our network is the Max-Feature-Map activation function, which acts as an embedded feature selector. By using multitask learning scheme to train the high-level feature extractor we were able to surpass the classic baseline systems in terms of quality and achieved impressive results for such a novice approach, getting 2.85% EER on the RSR2015 evaluation set. Fusion of the proposed and the baseline systems improves this result.

##### Abstract (translated by Google)
在说话人验证领域，深度学习仍然不是一个非常常见的工具。我们在文本提示说话者验证任务中研究深度卷积神经网络性能。提示的密码短语被分成字状态 - 即数字 - 以分别测试每个数字话语。我们为所有状态训练单个高级特征提取器，并使用余弦相似性度量来评分。我们网络的关键特征是最大特征映射激活功能，它充当嵌入式特征选择器。通过使用多任务学习方案来训练高级特征提取器，我们能够在质量方面超越经典基线系统，并为这种新手方法取得了令人印象深刻的结果，在RSR2015评估集中获得了2.85％的EER。拟议的和基准系统的融合改善了这一结果。

##### URL
[https://arxiv.org/abs/1803.05307](https://arxiv.org/abs/1803.05307)

##### PDF
[https://arxiv.org/pdf/1803.05307](https://arxiv.org/pdf/1803.05307)


---
layout: post
title: "A disciplined approach to neural network hyper-parameters: Part 1 -- learning rate, batch size, momentum, and weight decay"
date: 2018-03-26 20:05:59
categories: arXiv_CV
tags: arXiv_CV Regularization Deep_Learning
author: Leslie N. Smith
mathjax: true
---

* content
{:toc}

##### Abstract
Although deep learning has produced dazzling successes for applications of image, speech, and video processing in the past few years, most trainings are with suboptimal hyper-parameters, requiring unnecessarily long training times. Setting the hyper-parameters remains a black art that requires years of experience to acquire. This report proposes several efficient ways to set the hyper-parameters that significantly reduce training time and improves performance. Specifically, this report shows how to examine the training validation/test loss function for subtle clues of underfitting and overfitting and suggests guidelines for moving toward the optimal balance point. Then it discusses how to increase/decrease the learning rate/momentum to speed up training. Our experiments show that it is crucial to balance every manner of regularization for each dataset and architecture. Weight decay is used as a sample regularizer to show how its optimal value is tightly coupled with the learning rates and momentums.

##### Abstract (translated by Google)
虽然深度学习在过去几年中为图像，语音和视频处理应用带来了令人瞩目的成功，但大多数训练的超参数并不理想，需要不必要的长时间训练。设置超参数仍然是一种黑色艺术，需要多年的经验才能获得。本报告提出了几种有效的方法来设置超参数，从而显着缩短培训时间并提高性能。具体而言，本报告展示了如何检查训练验证/测试损失函数以寻找适合不足和过度拟合的细微线索，并提出了走向最佳平衡点的指导方针。然后讨论如何增加/减少学习速度/动力来加速训练。我们的实验表明，平衡每种数据集和体系结构的正规化方式至关重要。重量衰减被用作样本调节器来显示其最优值与学习速率和动量紧密结合的方式。

##### URL
[https://arxiv.org/abs/1803.09820](https://arxiv.org/abs/1803.09820)

##### PDF
[https://arxiv.org/pdf/1803.09820](https://arxiv.org/pdf/1803.09820)


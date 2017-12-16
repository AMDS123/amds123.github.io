---
layout: post
title: "Transformation-Based Models of Video Sequences"
date: 2017-04-24 20:20:40
categories: arXiv_CV
tags: arXiv_CV Prediction
author: Joost van Amersfoort, Anitha Kannan, Marc'Aurelio Ranzato, Arthur Szlam, Du Tran, Soumith Chintala
mathjax: true
---

* content
{:toc}

##### Abstract
In this work we propose a simple unsupervised approach for next frame prediction in video. Instead of directly predicting the pixels in a frame given past frames, we predict the transformations needed for generating the next frame in a sequence, given the transformations of the past frames. This leads to sharper results, while using a smaller prediction model. In order to enable a fair comparison between different video frame prediction models, we also propose a new evaluation protocol. We use generated frames as input to a classifier trained with ground truth sequences. This criterion guarantees that models scoring high are those producing sequences which preserve discrim- inative features, as opposed to merely penalizing any deviation, plausible or not, from the ground truth. Our proposed approach compares favourably against more sophisticated ones on the UCF-101 data set, while also being more efficient in terms of the number of parameters and computational cost.

##### Abstract (translated by Google)
在这项工作中，我们提出了一个简单的无监督的方法在视频中的下一帧预测。在给定过去帧的变换的情况下，我们不是直接预测给定过去帧的帧中的像素，而是预测在序列中产生下一帧所需的变换。这导致更清晰的结果，同时使用更小的预测模型。为了在不同的视频帧预测模型之间进行公平的比较，我们也提出了一个新的评估协议。我们使用生成的帧作为输入到用地面真实序列训练的分类器。这个标准保证得分高的模型是那些产生保留区分特征的序列的模型，而不仅仅是惩罚任何偏离，合理与否，离开事实真相。我们提出的方法与UCF-101数据集上更复杂的方法相比，在参数数量和计算成本方面更为有效。

##### URL
[https://arxiv.org/abs/1701.08435](https://arxiv.org/abs/1701.08435)

##### PDF
[https://arxiv.org/pdf/1701.08435](https://arxiv.org/pdf/1701.08435)


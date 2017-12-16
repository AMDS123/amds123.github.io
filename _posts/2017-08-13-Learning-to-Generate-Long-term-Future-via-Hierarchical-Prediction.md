---
layout: post
title: "Learning to Generate Long-term Future via Hierarchical Prediction"
date: 2017-08-13 03:31:18
categories: arXiv_CV
tags: arXiv_CV CNN RNN Prediction
author: Ruben Villegas, Jimei Yang, Yuliang Zou, Sungryull Sohn, Xunyu Lin, Honglak Lee
mathjax: true
---

* content
{:toc}

##### Abstract
We propose a hierarchical approach for making long-term predictions of future frames. To avoid inherent compounding errors in recursive pixel-level prediction, we propose to first estimate high-level structure in the input frames, then predict how that structure evolves in the future, and finally by observing a single frame from the past and the predicted high-level structure, we construct the future frames without having to observe any of the pixel-level predictions. Long-term video prediction is difficult to perform by recurrently observing the predicted frames because the small errors in pixel space exponentially amplify as predictions are made deeper into the future. Our approach prevents pixel-level error propagation from happening by removing the need to observe the predicted frames. Our model is built with a combination of LSTM and analogy based encoder-decoder convolutional neural networks, which independently predict the video structure and generate the future frames, respectively. In experiments, our model is evaluated on the Human3.6M and Penn Action datasets on the task of long-term pixel-level video prediction of humans performing actions and demonstrate significantly better results than the state-of-the-art.

##### Abstract (translated by Google)
我们提出了一个分层的方法来做出对未来帧的长期预测。为了避免递归像素级预测中固有的混合误差，我们建议首先估计输入帧中的高层结构，然后预测未来结构的演变，最后通过观察过去的单帧和预测的高我们构造未来的帧，而不必观察任何像素级的预测。长时间视频预测难以通过反复观察预测帧来执行，因为像素空间中的小误差随着预测深入到未来而指数地放大。我们的方法通过消除观察预测帧的需要来防止发生像素级错误传播。我们的模型是用LSTM和基于类比的编码器 - 解码器卷积神经网络的组合来构建的，分别独立地预测视频结构和生成未来的帧。在实验中，我们的模型是在Human3.6M和Penn Action数据集上评估人类长期执行像素级视频预测的行为，并且显示比现有技术更好的结果。

##### URL
[https://arxiv.org/abs/1704.05831](https://arxiv.org/abs/1704.05831)

##### PDF
[https://arxiv.org/pdf/1704.05831](https://arxiv.org/pdf/1704.05831)


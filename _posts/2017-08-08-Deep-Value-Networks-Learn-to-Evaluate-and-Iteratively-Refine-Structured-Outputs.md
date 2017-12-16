---
layout: post
title: "Deep Value Networks Learn to Evaluate and Iteratively Refine Structured Outputs"
date: 2017-08-08 08:10:34
categories: arXiv_CV
tags: arXiv_CV Segmentation Inference Classification Prediction Gradient_Descent
author: Michael Gygli, Mohammad Norouzi, Anelia Angelova
mathjax: true
---

* content
{:toc}

##### Abstract
We approach structured output prediction by optimizing a deep value network (DVN) to precisely estimate the task loss on different output configurations for a given input. Once the model is trained, we perform inference by gradient descent on the continuous relaxations of the output variables to find outputs with promising scores from the value network. When applied to image segmentation, the value network takes an image and a segmentation mask as inputs and predicts a scalar estimating the intersection over union between the input and ground truth masks. For multi-label classification, the DVN's objective is to correctly predict the F1 score for any potential label configuration. The DVN framework achieves the state-of-the-art results on multi-label prediction and image segmentation benchmarks.

##### Abstract (translated by Google)
我们通过优化深度网络（DVN）来处理结构化的输出预测，以精确估计给定输入的不同输出配置上的任务损失。一旦模型被训练，我们通过梯度下降对输出变量的连续松弛进行推理，从价值网络中找到具有可观分数的输出。当应用于图像分割时，值网络将图像和分割掩模作为输入，并预测标量，以估计输入和地面真实蒙版之间的交集。对于多标签分类，DVN的目标是正确预测任何潜在标签配置的F1分数。 DVN框架实现了多标签预测和图像分割基准的最新成果。

##### URL
[https://arxiv.org/abs/1703.04363](https://arxiv.org/abs/1703.04363)

##### PDF
[https://arxiv.org/pdf/1703.04363](https://arxiv.org/pdf/1703.04363)


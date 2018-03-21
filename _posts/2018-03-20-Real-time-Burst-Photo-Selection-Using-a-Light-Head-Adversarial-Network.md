---
layout: post
title: "Real-time Burst Photo Selection Using a Light-Head Adversarial Network"
date: 2018-03-20 01:26:33
categories: arXiv_CV
tags: arXiv_CV Adversarial CNN Prediction
author: Baoyuan Wang, Noranart Vesdapunt, Utkarsh Sinha, Lei Zhang
mathjax: true
---

* content
{:toc}

##### Abstract
We present an automatic moment capture system that runs in real-time on mobile cameras. The system is designed to run in the viewfinder mode and capture a burst sequence of frames before and after the shutter is pressed. For each frame, the system predicts in real-time a "goodness" score, based on which the best moment in the burst can be selected immediately after the shutter is released, without any user interference. To solve the problem, we develop a highly efficient deep neural network ranking model, which implicitly learns a "latent relative attribute" space to capture subtle visual differences within a sequence of burst images. Then the overall goodness is computed as a linear aggregation of the goodnesses of all the latent attributes. The latent relative attributes and the aggregation function can be seamlessly integrated in one fully convolutional network and trained in an end-to-end fashion. To obtain a compact model which can run on mobile devices in real-time, we have explored and evaluated a wide range of network design choices, taking into account the constraints of model size, computational cost, and accuracy. Extensive studies show that the best frame predicted by our model hit users' top-1 (out of 11 on average) choice for $64.1\%$ cases and top-3 choices for $86.2\%$ cases. Moreover, the model(only 0.47M Bytes) can run in real time on mobile devices, e.g. only 13ms on iPhone 7 for one frame prediction.

##### Abstract (translated by Google)
我们提供了一个在移动摄像机上实时运行的自动时刻捕捉系统。该系统设计为在取景器模式下运行，并在快门按下之前和之后拍摄连拍帧。对于每一帧，系统都会实时预测“善良”分数，根据这个分数，可以在释放快门后立即选择突发中的最佳时刻，而不会有任何用户干扰。为了解决这个问题，我们开发了一个高效的深度神经网络排名模型，它隐式地学习了一个“潜在的相对属性”空间，以捕捉一连串突发图像中的细微视觉差异。然后整体善良被计算为所有潜在属性的善的线性聚合。潜在的相对属性和聚合函数可以无缝集成到一个完全卷积网络中，并以端到端的方式进行训练。为了获得可以在移动设备上实时运行的紧凑型模型，我们已经考虑了模型大小，计算成本和准确性的限制，探索并评估了各种网络设计选择。大量的研究表明，我们模型预测的最佳框架在用于$ 64.1 \％$案例的用户排名前1位（平均值为11）中选择，而$ 86.2 \％$案例则排名前三。而且，该模型（仅0.47M字节）可以在移动设备上实时运行，例如，对于一帧预测，iPhone 7只有13ms。

##### URL
[http://arxiv.org/abs/1803.07212](http://arxiv.org/abs/1803.07212)

##### PDF
[http://arxiv.org/pdf/1803.07212](http://arxiv.org/pdf/1803.07212)


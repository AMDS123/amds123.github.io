---
layout: post
title: "VisualBackProp: efficient visualization of CNNs"
date: 2017-05-19 23:50:46
categories: arXiv_CV
tags: arXiv_CV CNN Inference Prediction
author: Mariusz Bojarski, Anna Choromanska, Krzysztof Choromanski, Bernhard Firner, Larry Jackel, Urs Muller, Karol Zieba
mathjax: true
---

* content
{:toc}

##### Abstract
This paper proposes a new method, that we call VisualBackProp, for visualizing which sets of pixels of the input image contribute most to the predictions made by the convolutional neural network (CNN). The method heavily hinges on exploring the intuition that the feature maps contain less and less irrelevant information to the prediction decision when moving deeper into the network. The technique we propose was developed as a debugging tool for CNN-based systems for steering self-driving cars and is therefore required to run in real-time, i.e. it was designed to require less computations than a forward propagation. This makes the presented visualization method a valuable debugging tool which can be easily used during both training and inference. We furthermore justify our approach with theoretical arguments and theoretically confirm that the proposed method identifies sets of input pixels, rather than individual pixels, that collaboratively contribute to the prediction. Our theoretical findings stand in agreement with the experimental results. The empirical evaluation shows the plausibility of the proposed approach on the road video data as well as in other applications and reveals that it compares favorably to the layer-wise relevance propagation approach, i.e. it obtains similar visualization results and simultaneously achieves order of magnitude speed-ups.

##### Abstract (translated by Google)
本文提出了一种新的方法，我们称之为VisualBackProp，用于可视化输入图像的哪些像素集合对卷积神经网络（CNN）所做的预测的贡献最大。该方法在很大程度上取决于探索直觉，即当深入网络时，特征地图包含的预测决策越来越不相关的信息越来越少。我们提出的技术是作为基于CNN的系统的调试工具开发的，用于转向自驾车，因此需要实时运行，即它被设计为比向前传播需要更少的计算。这使得提出的可视化方法成为一个有价值的调试工具，可以在训练和推理过程中轻松使用。我们进一步用理论论证来证明我们的方法，并从理论上证实所提出的方法识别输入像素的集合，而不是个别像素，这些输入像素协作地对预测作出贡献。我们的理论研究结果与实验结果是一致的。实证评估显示了所提出的方法在道路视频数据以及其他应用中的合理性，并且揭示出其与层级相关性传播方法相比是有利的，即它获得相似的可视化结果并同时达到数量级的速度 - UPS。

##### URL
[https://arxiv.org/abs/1611.05418](https://arxiv.org/abs/1611.05418)

##### PDF
[https://arxiv.org/pdf/1611.05418](https://arxiv.org/pdf/1611.05418)


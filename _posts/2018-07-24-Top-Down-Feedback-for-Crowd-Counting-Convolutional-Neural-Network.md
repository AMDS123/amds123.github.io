---
layout: post
title: "Top-Down Feedback for Crowd Counting Convolutional Neural Network"
date: 2018-07-24 02:16:14
categories: arXiv_CV
tags: arXiv_CV CNN Prediction
author: Deepak Babu Sam, R. Venkatesh Babu
mathjax: true
---

* content
{:toc}

##### Abstract
Counting people in dense crowds is a demanding task even for humans. This is primarily due to the large variability in appearance of people. Often people are only seen as a bunch of blobs. Occlusions, pose variations and background clutter further compound the difficulty. In this scenario, identifying a person requires larger spatial context and semantics of the scene. But the current state-of-the-art CNN regressors for crowd counting are feedforward and use only limited spatial context to detect people. They look for local crowd patterns to regress the crowd density map, resulting in false predictions. Hence, we propose top-down feedback to correct the initial prediction of the CNN. Our architecture consists of a bottom-up CNN along with a separate top-down CNN to generate feedback. The bottom-up network, which regresses the crowd density map, has two columns of CNN with different receptive fields. Features from various layers of the bottom-up CNN are fed to the top-down network. The feedback, thus generated, is applied on the lower layers of the bottom-up network in the form of multiplicative gating. This masking weighs activations of the bottom-up network at spatial as well as feature levels to correct the density prediction. We evaluate the performance of our model on all major crowd datasets and show the effectiveness of top-down feedback.

##### Abstract (translated by Google)
即使是人类，在密集的人群中计算人数也是一项艰巨的任务。这主要是由于人的外观变化很大。通常人们只被视为一堆斑点。闭塞，姿势变化和背景杂乱进一步加剧了难度。在这种情况下，识别人需要更大的空间背景和场景的语义。但是目前用于人群计数的最先进的CNN回归器是前馈的，并且仅使用有限的空间背景来检测人。他们寻找当地的人群模式来回归人群密度图，导致错误的预测。因此，我们建议自上而下的反馈来纠正CNN的初始预测。我们的架构包括一个自下而上的CNN以及一个单独的自上而下的CNN来产生反馈。回归人群密度图的自下而上网络有两列CNN，具有不同的感受域。来自自下而上CNN的各层的特征被馈送到自上而下的网络。由此产生的反馈以乘法门控的形式应用于自下而上网络的较低层。这种掩蔽在空间和特征级别上对自下而上网络的激活进行加权，以校正密度预测。我们评估模型在所有主要人群数据集上的表现，并显示自上而下反馈的有效性。

##### URL
[https://arxiv.org/abs/1807.08881](https://arxiv.org/abs/1807.08881)

##### PDF
[https://arxiv.org/pdf/1807.08881](https://arxiv.org/pdf/1807.08881)


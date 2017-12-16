---
layout: post
title: "CAR-Net: Clairvoyant Attentive Recurrent Network"
date: 2017-11-28 00:22:09
categories: arXiv_CV
tags: arXiv_CV Prediction
author: Amir Sadeghian, Ferdinand Legros, Maxime Voisin, Ricky Vesel, Alexandre Alahi, Silvio Savarese
mathjax: true
---

* content
{:toc}

##### Abstract
We present an interpretable framework for path prediction that learns scene-specific causations behind agents' behaviors. We exploit two sources of information: the past motion trajectory of the agent of interest and a wide top-down view of the scene. We propose a Clairvoyant Attentive Recurrent Network (CAR-Net) that learns "where to look" in the large image when solving the path prediction task. While previous works on trajectory prediction are constrained to either use semantic information or hand-crafted regions centered around the agent, our method has the capacity to select any region within the image, e.g., a far-away curve when predicting the change of speed of vehicles. To study our goal towards learning observable causality behind agents' behaviors, we have built a new dataset made of top view images of hundreds of scenes (e.g., F1 racing circuits) where the vehicles are governed by known specific regions within the images (e.g., upcoming curves). Our algorithm successfully selects these regions, learns navigation patterns that generalize to unseen maps, outperforms previous works in terms of prediction accuracy on publicly available datasets, and provides human-interpretable static scene-specific dependencies.

##### Abstract (translated by Google)
我们提出了一个可解释的路径预测框架，用于了解代理行为背后的特定场景因果关系。我们利用两个信息来源：感兴趣的代理人过去的运动轨迹和广泛的自上而下的景象。我们提出了一种在解决路径预测任务时，在大图像中学习“在哪里看”的透视关注周期性网络（CAR-Net）。虽然之前关于轨迹预测的研究被限制为使用语义信息或以代理为中心的手工区域，但是我们的方法有能力选择图像内的任何区域，例如，预测速度变化时的远距离曲线汽车。为了研究我们研究代理人行为背后的可观察因果关系的目标，我们建立了一个由数百个场景（例如F1赛车场）的顶视图图像组成的新数据集，其中车辆由图像内的已知特定区域（例如，即将到来的曲线）我们的算法成功地选择这些区域，学习导航模式，推广到不可见的地图，在公开可用数据集的预测准确性方面胜过以前的作品，并提供人类可解释的静态特定场景依赖性。

##### URL
[https://arxiv.org/abs/1711.10061](https://arxiv.org/abs/1711.10061)

##### PDF
[https://arxiv.org/pdf/1711.10061](https://arxiv.org/pdf/1711.10061)


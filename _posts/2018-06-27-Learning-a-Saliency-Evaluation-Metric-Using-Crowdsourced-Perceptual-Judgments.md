---
layout: post
title: "Learning a Saliency Evaluation Metric Using Crowdsourced Perceptual Judgments"
date: 2018-06-27 00:45:33
categories: arXiv_CV
tags: arXiv_CV Salient CNN Prediction
author: Changqun Xia, Jia Li, Jinming Su, Ali Borji
mathjax: true
---

* content
{:toc}

##### Abstract
In the area of human fixation prediction, dozens of computational saliency models are proposed to reveal certain saliency characteristics under different assumptions and definitions. As a result, saliency model benchmarking often requires several evaluation metrics to simultaneously assess saliency models from multiple perspectives. However, most computational metrics are not designed to directly measure the perceptual similarity of saliency maps so that the evaluation results may be sometimes inconsistent with the subjective impression. To address this problem, this paper first conducts extensive subjective tests to find out how the visual similarities between saliency maps are perceived by humans. Based on the crowdsourced data collected in these tests, we conclude several key factors in assessing saliency maps and quantize the performance of existing metrics. Inspired by these factors, we propose to learn a saliency evaluation metric based on a two-stream convolutional neural network using crowdsourced perceptual judgements. Specifically, the relative saliency score of each pair from the crowdsourced data is utilized to regularize the network during the training process. By capturing the key factors shared by various subjects in comparing saliency maps, the learned metric better aligns with human perception of saliency maps, making it a good complement to the existing metrics. Experimental results validate that the learned metric can be generalized to the comparisons of saliency maps from new images, new datasets, new models and synthetic data. Due to the effectiveness of the learned metric, it also can be used to facilitate the development of new models for fixation prediction.

##### Abstract (translated by Google)
在人体固定预测领域，提出了许多计算显着性模型来揭示不同假设和定义下的某些显着特征。因此，显着性模型基准测试通常需要多个评估指标来从多个角度同时评估显着性模型。然而，大多数计算度量不是直接测量显着性图的感知相似度，因此评估结果可能有时与主观印象不一致。为了解决这个问题，本文首先进行了广泛的主观测试，以了解人类如何感知显着性地图之间的视觉相似性。基于这些测试中收集的众包数据，我们总结了评估显着图的几个关键因素，并量化了现有指标的性能。受这些因素的启发，我们建议基于使用众包的感知判断的双流卷积神经网络来学习显着性评估度量。具体而言，来自众包数据的每对的相对显着性分数被用来在训练过程中调整网络。通过捕捉各主题在显着性地图上的共享关键因素，学习指标更好地符合人类对显着性地图的感知，使其成为对现有指标的很好补充。实验结果验证了学习的度量可以推广到新图像，新数据集，新模型和合成数据的显着图的比较。由于学习度量的有效性，它也可以用来促进固定预测的新模型的开发。

##### URL
[http://arxiv.org/abs/1806.10257](http://arxiv.org/abs/1806.10257)

##### PDF
[http://arxiv.org/pdf/1806.10257](http://arxiv.org/pdf/1806.10257)


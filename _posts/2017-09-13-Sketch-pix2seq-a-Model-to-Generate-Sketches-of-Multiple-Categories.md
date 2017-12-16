---
layout: post
title: "Sketch-pix2seq: a Model to Generate Sketches of Multiple Categories"
date: 2017-09-13 03:22:27
categories: arXiv_CV
tags: arXiv_CV CNN RNN Classification Recognition
author: Yajing Chen, Shikui Tu, Yuqi Yi, Lei Xu
mathjax: true
---

* content
{:toc}

##### Abstract
Sketch is an important media for human to communicate ideas, which reflects the superiority of human intelligence. Studies on sketch can be roughly summarized into recognition and generation. Existing models on image recognition failed to obtain satisfying performance on sketch classification. But for sketch generation, a recent study proposed a sequence-to-sequence variational-auto-encoder (VAE) model called sketch-rnn which was able to generate sketches based on human inputs. The model achieved amazing results when asked to learn one category of object, such as an animal or a vehicle. However, the performance dropped when multiple categories were fed into the model. Here, we proposed a model called sketch-pix2seq which could learn and draw multiple categories of sketches. Two modifications were made to improve the sketch-rnn model: one is to replace the bidirectional recurrent neural network (BRNN) encoder with a convolutional neural network(CNN); the other is to remove the Kullback-Leibler divergence from the objective function of VAE. Experimental results showed that models with CNN encoders outperformed those with RNN encoders in generating human-style sketches. Visualization of the latent space illustrated that the removal of KL-divergence made the encoder learn a posterior of latent space that reflected the features of different categories. Moreover, the combination of CNN encoder and removal of KL-divergence, i.e., the sketch-pix2seq model, had better performance in learning and generating sketches of multiple categories and showed promising results in creativity tasks.

##### Abstract (translated by Google)
素描是人类交流思想的重要媒介，体现了人类智慧的优越性。素描的研究大致可以归纳为认识和产生。现有的图像识别模型未能在草图分类上取得令人满意的效果。但是为了生成草图，最近的一项研究提出了一个名为sketch-rnn的序列 - 序列变分自编码（VAE）模型，该模型能够生成基于人类输入的草图。当被要求学习一类物体时，例如动物或车辆，模型取得了惊人的效果。然而，当多个类别被输入模型时，性能下降。在这里，我们提出了一个名为sketch-pix2seq的模型，可以学习和绘制多个类别的草图。为了改进sketch-rnn模型，作了两项修改：一种是用卷积神经网络（CNN）代替双向递归神经网络（BRNN）编码器。另一个是从VAE的目标函数中去除Kullback-Leibler散度。实验结果表明，使用CNN编码器的模型比使用RNN编码器的模型在生成人类草图方面表现出色。潜在空间的可视化表明，KL散度的消除使得编码器学习了反映不同类别的特征的潜在空间的后部。此外，CNN编码器和KL散度的去除（即，sketch-pix2seq模型）的组合在学习和生成多个类别的草图中具有更好的性能，并且在创造性任务中显示出有希望的结果。

##### URL
[https://arxiv.org/abs/1709.04121](https://arxiv.org/abs/1709.04121)

##### PDF
[https://arxiv.org/pdf/1709.04121](https://arxiv.org/pdf/1709.04121)


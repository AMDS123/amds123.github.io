---
layout: post
title: "Hierarchical Long-term Video Prediction without Supervision"
date: 2018-06-12 21:11:07
categories: arXiv_CV
tags: arXiv_CV Adversarial Prediction
author: Nevan Wichers, Ruben Villegas, Dumitru Erhan, Honglak Lee
mathjax: true
---

* content
{:toc}

##### Abstract
Much of recent research has been devoted to video prediction and generation, yet most of the previous works have demonstrated only limited success in generating videos on short-term horizons. The hierarchical video prediction method by Villegas et al. (2017) is an example of a state-of-the-art method for long-term video prediction, but their method is limited because it requires ground truth annotation of high-level structures (e.g., human joint landmarks) at training time. Our network encodes the input frame, predicts a high-level encoding into the future, and then a decoder with access to the first frame produces the predicted image from the predicted encoding. The decoder also produces a mask that outlines the predicted foreground object (e.g., person) as a by-product. Unlike Villegas et al. (2017), we develop a novel training method that jointly trains the encoder, the predictor, and the decoder together without highlevel supervision; we further improve upon this by using an adversarial loss in the feature space to train the predictor. Our method can predict about 20 seconds into the future and provides better results compared to Denton and Fergus (2018) and Finn et al. (2016) on the Human 3.6M dataset.

##### Abstract (translated by Google)
最近的许多研究都致力于视频预测和生成，但以前的大部分作品在短期视频生成视频方面的成效都很有限。 Villegas等人的分层视频预测方法（2017）是用于长期视频预测的最先进方法的一个例子，但是它们的方法是有限的，因为它需要在训练时间对高层结构（例如人类联合地标）进行地面真实注释。我们的网络对输入帧进行编码，预测未来的高级编码，然后访问第一帧的解码器根据预测的编码产生预测图像。解码器还产生将预测的前景对象（例如，人）概述为副产品的掩码。与维勒加斯等人不同。 （2017年），我们开发了一种新的训练方法，无需高级监督就可以共同训练编码器，预测器和解码器。我们通过在特征空间中使用对抗性损失来训练预测变量来进一步改进。与Denton和Fergus（2018）和Finn等人相比，我们的方法可以预测未来约20秒，并提供更好的结果。 （2016）关于人类3.6M数据集。

##### URL
[http://arxiv.org/abs/1806.04768](http://arxiv.org/abs/1806.04768)

##### PDF
[http://arxiv.org/pdf/1806.04768](http://arxiv.org/pdf/1806.04768)


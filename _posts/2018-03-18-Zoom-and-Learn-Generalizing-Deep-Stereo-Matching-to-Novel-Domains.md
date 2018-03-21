---
layout: post
title: "Zoom and Learn: Generalizing Deep Stereo Matching to Novel Domains"
date: 2018-03-18 11:11:10
categories: arXiv_CV
tags: arXiv_CV Regularization CNN Optimization
author: Jiahao Pang, Wenxiu Sun, Chengxi Yang, Jimmy Ren, Ruichao Xiao, Jin Zeng, Liang Lin
mathjax: true
---

* content
{:toc}

##### Abstract
Despite the recent success of stereo matching with convolutional neural networks (CNNs), it remains arduous to generalize a pre-trained deep stereo model to a novel domain. A major difficulty is to collect accurate ground-truth disparities for stereo pairs in the target domain. In this work, we propose a self-adaptation approach for CNN training, utilizing both synthetic training data (with ground-truth disparities) and stereo pairs in the new domain (without ground-truths). Our method is driven by two empirical observations. By feeding real stereo pairs of different domains to stereo models pre-trained with synthetic data, we see that: i) a pre-trained model does not generalize well to the new domain, producing artifacts at boundaries and ill-posed regions; however, ii) feeding an up-sampled stereo pair leads to a disparity map with extra details. To avoid i) while exploiting ii), we formulate an iterative optimization problem with graph Laplacian regularization. At each iteration, the CNN adapts itself better to the new domain: we let the CNN learn its own higher-resolution output; at the meanwhile, a graph Laplacian regularization is imposed to discriminatively keep the desired edges while smoothing out the artifacts. We demonstrate the effectiveness of our method in two domains: daily scenes collected by smartphone cameras, and street views captured in a driving car.

##### Abstract (translated by Google)
尽管最近与卷积神经网络（CNN）进行立体匹配取得了成功，但将预先训练的深层立体模型推广到一个新领域仍然很艰巨。一个主要困难是收集目标域中立体声对的准确地面真实差异。在这项工作中，我们提出了一种自适应CNN训练方法，利用合成训练数据（具有地面真实差异）和立体对在新领域（没有地面真值）。我们的方法由两个经验观察驱动。通过将真正的立体声对的不同区域提供给用合成数据预先训练的立体模型，我们看到：i）预先训练的模型不能很好地推广到新的领域，在边界和不适合的区域产生伪影;然而，ii）馈送上采样的立体声对导致具有额外细节的视差图。为了避免i）在利用ii）时，我们用图拉普拉斯正则化来制定迭代优化问题。在每一次迭代中，CNN都更好地适应新的领域：我们让CNN学习它自己的更高分辨率的输出;与此同时，图形拉普拉斯正则化被用来区分地保持期望的边缘，同时平滑伪像。我们在两个领域展示了我们方法的有效性：智能手机相机收集的日常场景以及驾驶汽车中捕获的街景。

##### URL
[https://arxiv.org/abs/1803.06641](https://arxiv.org/abs/1803.06641)

##### PDF
[https://arxiv.org/pdf/1803.06641](https://arxiv.org/pdf/1803.06641)


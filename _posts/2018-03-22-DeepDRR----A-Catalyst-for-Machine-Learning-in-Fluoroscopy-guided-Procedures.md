---
layout: post
title: "DeepDRR -- A Catalyst for Machine Learning in Fluoroscopy-guided Procedures"
date: 2018-03-22 23:04:16
categories: arXiv_CV
tags: arXiv_CV Deep_Learning Detection
author: Mathias Unberath, Jan-Nico Zaech, Sing Chun Lee, Bastian Bier, Javad Fotouhi, Mehran Armand, Nassir Navab
mathjax: true
---

* content
{:toc}

##### Abstract
Machine learning-based approaches outperform competing methods in most disciplines relevant to diagnostic radiology. Interventional radiology, however, has not yet benefited substantially from the advent of deep learning, in particular because of two reasons: 1) Most images acquired during the procedure are never archived and are thus not available for learning, and 2) even if they were available, annotations would be a severe challenge due to the vast amounts of data. When considering fluoroscopy-guided procedures, an interesting alternative to true interventional fluoroscopy is in silico simulation of the procedure from 3D diagnostic CT. In this case, labeling is comparably easy and potentially readily available, yet, the appropriateness of resulting synthetic data is dependent on the forward model. In this work, we propose DeepDRR, a framework for fast and realistic simulation of fluoroscopy and digital radiography from CT scans, tightly integrated with the software platforms native to deep learning. We use machine learning for material decomposition and scatter estimation in 3D and 2D, respectively, combined with analytic forward projection and noise injection to achieve the required performance. On the example of anatomical landmark detection in X-ray images of the pelvis, we demonstrate that machine learning models trained on DeepDRRs generalize to unseen clinically acquired data without the need for re-training or domain adaptation. Our results are promising and promote the establishment of machine learning in fluoroscopy-guided procedures.

##### Abstract (translated by Google)
基于机器学习的方法优于大多数与诊断放射学有关的学科中的竞争方法。然而，介入放射学尚未从深度学习的出现中获益，特别是由于两个原因：1）手术过程中获得的大多数图像从未存档，因此无法用于学习; 2）即使它们是由于海量数据的存在，注释将是一个严峻的挑战。在考虑透视引导的手术时，真正的介入性荧光检查的一个有趣的替代方法是通过3D诊断性CT的计算机模拟来进行。在这种情况下，标签比较容易并且可能很容易获得，但所得到的合成数据的适当性取决于正向模型。在这项工作中，我们提出了DeepDRR，这是一种快速，逼真的CT扫描和CT扫描数字射线照相模拟框架，与深入学习的软件平台紧密结合。我们使用机器学习分别在3D和2D中进行材料分解和散射估计，并结合分析正向投影和噪声注入来实现所需的性能。关于骨盆X射线图像中解剖标志检测的例子，我们证明在DeepDRR上训练的机器学习模型推广到看不见临床采集的数据，而不需要重新训练或域适应。我们的结果很有希望，并促进了透视引导程序中机器学习的建立。

##### URL
[https://arxiv.org/abs/1803.08606](https://arxiv.org/abs/1803.08606)

##### PDF
[https://arxiv.org/pdf/1803.08606](https://arxiv.org/pdf/1803.08606)


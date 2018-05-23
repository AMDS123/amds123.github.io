---
layout: post
title: "Deep Learning with Cinematic Rendering - Fine-Tuning Deep Neural Networks Using Photorealistic Medical Images"
date: 2018-05-22 05:24:41
categories: arXiv_CV
tags: arXiv_CV CNN Deep_Learning
author: Faisal Mahmood, Richard Chen, Sandra Sudarsky, Daphne Yu, Nicholas J. Durr
mathjax: true
---

* content
{:toc}

##### Abstract
Deep learning has emerged as a powerful artificial intelligence tool to interpret medical images for a growing variety of applications. However, the paucity of medical imaging data with high-quality annotations that is necessary for training such methods ultimately limits their performance. Medical data is challenging to acquire due to privacy issues, shortage of experts available for annotation, limited representation of rare conditions and cost. This problem has previously been addressed by using synthetically generated data. However, networks trained on synthetic data often fail to generalize to real data. Cinematic rendering simulates the propagation and interaction of light passing through tissue models reconstructed from CT data, enabling the generation of photorealistic images. In this paper, we present one of the first applications of cinematic rendering in deep learning, in which we propose to fine-tune synthetic data-driven networks using cinematically rendered CT data for the task of monocular depth estimation in endoscopy. Our experiments demonstrate that: (a) Convolutional Neural Networks (CNNs) trained on synthetic data and fine-tuned on photorealistic cinematically rendered data adapt better to real medical images and demonstrate more robust performance when compared to networks with no fine-tuning, (b) these fine-tuned networks require less training data to converge to an optimal solution, and (c) fine-tuning with data from a variety of photorealistic rendering conditions of the same scene prevents the network from learning patient-specific information and aids in generalizability of the model. Our empirical evaluation demonstrates that networks fine-tuned with cinematically rendered data predict depth with 56.87% less error for rendered endoscopy images and 27.49% less error for real porcine colon endoscopy images.

##### Abstract (translated by Google)
深度学习已经成为一种功能强大的人工智能工具，用于解释越来越多种应用的医学图像。但是，缺乏训练这些方法所需的高质量注释的医学成像数据最终限制了其性能。由于隐私问题，可用于注释的专家短缺，罕见条件和成本的代表性有限，医疗数据难以获得。以前通过使用综合生成的数据解决了这个问题。然而，使用合成数据进行培训的网络常常无法推广到真实数据。电影渲染模拟通过CT数据重建的组织模型的光的传播和相互作用，从而生成逼真的图像。在本文中，我们介绍了电影渲染在深度学习中的第一个应用之一，其中我们建议使用电影渲染的CT数据对内窥镜中单眼深度估计任务的合成数据驱动网络进行微调。我们的实验证明：（a）卷积神经网络（CNNs）训练合成数据，并对照片真实感的电影渲染数据进行微调，以更好地适应真实的医学图像，并且与没有微调的网络相比，展现出更强大的性能，（b ）这些微调网络需要较少的训练数据来收敛到最佳解决方案，以及（c）利用来自同一场景的各种照片真实感渲染条件的数据进行微调，防止网络学习患者特定信息并且有助于普遍性的模型。我们的经验性评估表明，使用电影渲染数据进行微调的网络可预测深度，对于实际内窥镜检查图像，误差减少56.87％，对真正的猪结肠内窥镜检查图像误差减少27.49％。

##### URL
[https://arxiv.org/abs/1805.08400](https://arxiv.org/abs/1805.08400)

##### PDF
[https://arxiv.org/pdf/1805.08400](https://arxiv.org/pdf/1805.08400)


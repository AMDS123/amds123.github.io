---
layout: post
title: "Predicting Foreground Object Ambiguity and Efficiently Crowdsourcing the Segmentation"
date: 2017-04-30 19:27:30
categories: arXiv_CV
tags: arXiv_CV Salient Segmentation Prediction
author: Danna Gurari, Kun He, Bo Xiong, Jianming Zhang, Mehrnoosh Sameki, Suyog Dutt Jain, Stan Sclaroff, Margrit Betke, Kristen Grauman
mathjax: true
---

* content
{:toc}

##### Abstract
We propose the ambiguity problem for the foreground object segmentation task and motivate the importance of estimating and accounting for this ambiguity when designing vision systems. Specifically, we distinguish between images which lead multiple annotators to segment different foreground objects (ambiguous) versus minor inter-annotator differences of the same object. Taking images from eight widely used datasets, we crowdsource labeling the images as "ambiguous" or "not ambiguous" to segment in order to construct a new dataset we call STATIC. Using STATIC, we develop a system that automatically predicts which images are ambiguous. Experiments demonstrate the advantage of our prediction system over existing saliency-based methods on images from vision benchmarks and images taken by blind people who are trying to recognize objects in their environment. Finally, we introduce a crowdsourcing system to achieve cost savings for collecting the diversity of all valid "ground truth" foreground object segmentations by collecting extra segmentations only when ambiguity is expected. Experiments show our system eliminates up to 47% of human effort compared to existing crowdsourcing methods with no loss in capturing the diversity of ground truths.

##### Abstract (translated by Google)
我们提出了前景物体分割任务的模糊性问题，并激发了在设计视觉系统时对这种模糊性进行估计和计算的重要性。具体而言，我们区分引导多个注释器的图像，以分割不同的前景对象（不明确的）与同一对象的较小的注释器间差异。从八个广泛使用的数据集中获取图像，我们将图像标记为“模棱两可”或“不模糊”来分割，以构建我们称为静态的新数据集。使用STATIC，我们开发了一个能够自动预测哪些图像不明确的系统。实验证明了我们的预测系统相对于现有基于显着性的方法对视觉基准的图像和试图识别其环境中的物体的盲人所拍摄的图像的优点。最后，我们引入一个众包系统来节省成本，以便在所有有效的“地面实况”前景物体分割的多样性收集额外的分割，只有当预期的歧义性。实验表明，与现有的众包方法相比，我们的系统消除了高达47％的人力投入，并且毫不失于捕捉地面事实的多样性。

##### URL
[https://arxiv.org/abs/1705.00366](https://arxiv.org/abs/1705.00366)

##### PDF
[https://arxiv.org/pdf/1705.00366](https://arxiv.org/pdf/1705.00366)


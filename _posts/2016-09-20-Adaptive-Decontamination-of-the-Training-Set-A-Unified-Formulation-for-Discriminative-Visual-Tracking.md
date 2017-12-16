---
layout: post
title: "Adaptive Decontamination of the Training Set: A Unified Formulation for Discriminative Visual Tracking"
date: 2016-09-20 11:46:17
categories: arXiv_CV
tags: arXiv_CV Tracking Detection
author: Martin Danelljan, Gustav Häger, Fahad Shahbaz Khan, Michael Felsberg
mathjax: true
---

* content
{:toc}

##### Abstract
Tracking-by-detection methods have demonstrated competitive performance in recent years. In these approaches, the tracking model heavily relies on the quality of the training set. Due to the limited amount of labeled training data, additional samples need to be extracted and labeled by the tracker itself. This often leads to the inclusion of corrupted training samples, due to occlusions, misalignments and other perturbations. Existing tracking-by-detection methods either ignore this problem, or employ a separate component for managing the training set. We propose a novel generic approach for alleviating the problem of corrupted training samples in tracking-by-detection frameworks. Our approach dynamically manages the training set by estimating the quality of the samples. Contrary to existing approaches, we propose a unified formulation by minimizing a single loss over both the target appearance model and the sample quality weights. The joint formulation enables corrupted samples to be down-weighted while increasing the impact of correct ones. Experiments are performed on three benchmarks: OTB-2015 with 100 videos, VOT-2015 with 60 videos, and Temple-Color with 128 videos. On the OTB-2015, our unified formulation significantly improves the baseline, with a gain of 3.8% in mean overlap precision. Finally, our method achieves state-of-the-art results on all three datasets. Code and supplementary material are available at this http URL .

##### Abstract (translated by Google)
跟踪检测方法近年来已经显示出有竞争力的表现。在这些方法中，跟踪模型严重依赖于训练集的质量。由于标记的训练数据量有限，追踪器本身需要提取和标记附加的样本。这通常会导致包含损坏的训练样本，由于堵塞，失调和其他扰动。现有的逐行检测方法要么忽略这个问题，要么采用单独的组件来管理训练集。我们提出了一种新颖的通用方法来缓解跟踪检测框架中受损训练样本的问题。我们的方法通过估计样本的质量来动态管理训练集。与现有的方法相反，我们提出了一个统一的公式，通过最小化目标外观模型和样本质量权重的单一损失。联合公式可以使损坏的样本降低权重，同时增加正确的影响。实验在三个基准上进行：OTB-2015有100个视频，VOT-2015有60个视频，Temple-Color有128个视频。在OTB-2015中，我们的统一公式显着提高了基准，平均重叠精度提高了3.8％。最后，我们的方法在所有三个数据集上都达到了最新的结果。代码和补充材料可在此http URL中找到。

##### URL
[https://arxiv.org/abs/1609.06118](https://arxiv.org/abs/1609.06118)

##### PDF
[https://arxiv.org/pdf/1609.06118](https://arxiv.org/pdf/1609.06118)


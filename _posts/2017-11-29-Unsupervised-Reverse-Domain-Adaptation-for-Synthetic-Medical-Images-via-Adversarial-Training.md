---
layout: post
title: "Unsupervised Reverse Domain Adaptation for Synthetic Medical Images via Adversarial Training"
date: 2017-11-29 01:32:42
categories: arXiv_CV
tags: arXiv_CV Regularization Adversarial Deep_Learning
author: Faisal Mahmood, Richard Chen, Nicholas J. Durr
mathjax: true
---

* content
{:toc}

##### Abstract
To realize the full potential of deep learning for medical imaging, large annotated datasets are required for training. Such datasets are difficult to acquire because labeled medical images are not usually available due to privacy issues, lack of experts available for annotation, underrepresentation of rare conditions and poor standardization. Lack of annotated data has been addressed in conventional vision applications using synthetic images refined via unsupervised adversarial training to look like real images. However, this approach is difficult to extend to general medical imaging because of the complex and diverse set of features found in real human tissues. We propose an alternative framework that uses a reverse flow, where adversarial training is used to make real medical images more like synthetic images, and hypothesize that clinically-relevant features can be preserved via self-regularization. These domain-adapted images can then be accurately interpreted by networks trained on large datasets of synthetic medical images. We test this approach for the notoriously difficult task of depth-estimation from endoscopy. We train a depth estimator on a large dataset of synthetic images generated using an accurate forward model of an endoscope and an anatomically-realistic colon. This network predicts significantly better depths when using synthetic-like domain-adapted images compared to the real images, confirming that the clinically-relevant features of depth are preserved.

##### Abstract (translated by Google)
为了实现医学成像深度学习的全部潜力，需要大量的注释数据集进行训练。这样的数据集很难获得，因为由于隐私问题，缺少可用于注释的专家，罕见情况代表性不足和标准化差，通常不能获得标记的医学图像。在传统的视觉应用中，使用通过无监督对抗训练精炼的合成图像看起来像真实图像，缺少注释数据。然而，由于在真人组织中发现的复杂和多样的特征，这种方法难以扩展到一般的医学成像。我们提出了一个使用反向流动的替代框架，其中使用对抗训练使得真实的医学图像更像合成图像，并且推测临床相关特征可以通过自我正规化保存。然后可以通过在合成医学图像的大数据集上训练的网络准确地解释这些领域适应的图像。我们测试这种方法是从内窥镜深度估计的臭名昭着的艰巨任务。我们使用精确的内窥镜正向模型和解剖学上逼真的结肠，对合成图像的大型数据集进行深度估计。这个网络预测显着更好的深度，当使用合成像领域适应的图像相比，真实的图像，确认临床相关的深度特征保存。

##### URL
[https://arxiv.org/abs/1711.06606](https://arxiv.org/abs/1711.06606)

##### PDF
[https://arxiv.org/pdf/1711.06606](https://arxiv.org/pdf/1711.06606)


---
layout: post
title: "Conditional Infilling GANs for Data Augmentation in Mammogram Classification"
date: 2018-07-21 06:29:10
categories: arXiv_CV
tags: arXiv_CV Adversarial GAN Classification Deep_Learning Detection
author: Eric Wu, Kevin Wu, David Cox, William Lotter
mathjax: true
---

* content
{:toc}

##### Abstract
Deep learning approaches to breast cancer detection in mammograms have recently shown promising results. However, such models are constrained by the limited size of publicly available mammography datasets, in large part due to privacy concerns and the high cost of generating expert annotations. Limited dataset size is further exacerbated by substantial class imbalance since "normal" images dramatically outnumber those with findings. Given the rapid progress of generative models in synthesizing realistic images, and the known effectiveness of simple data augmentation techniques (e.g. horizontal flipping), we ask if it is possible to synthetically augment mammogram datasets using generative adversarial networks (GANs). We train a class-conditional GAN to perform contextual in-filling, which we then use to synthesize lesions onto healthy screening mammograms. First, we show that GANs are capable of generating high-resolution synthetic mammogram patches. Next, we experimentally evaluate using the augmented dataset to improve breast cancer classification performance. We observe that a ResNet-50 classifier trained with GAN-augmented training data produces a higher AUROC compared to the same model trained only on traditionally augmented data, demonstrating the potential of our approach.

##### Abstract (translated by Google)
乳房X线照片中乳腺癌检测的深度学习方法最近显示出有希望的结果。然而，这些模型受到公开可用的乳腺摄影数据集的有限尺寸的限制，这在很大程度上是由于隐私问题和产生专家注释的高成本。有限的数据集大小因实质级别不平衡而进一步恶化，因为“正常”图像的数量远远超过那些有发现的图像。鉴于生成模型在合成逼真图像方面的快速进展，以及简单数据增强技术（例如水平翻转）的已知有效性，我们询问是否有可能使用生成性对抗网络（GAN）合成增强乳房X线照片数据集。我们训练一个类条件GAN来执行上下文填充，然后我们使用它来将病变合成到健康的筛查乳房X线照片上。首先，我们展示了GAN能够生成高分辨率合成乳房X线照片。接下来，我们通过实验评估使用增强数据集来改善乳腺癌分类表现。我们观察到，与仅使用传统增强数据训练的相同模型相比，使用GAN增强训练数据训练的ResNet-50分类器产生更高的AUROC，证明了我们的方法的潜力。

##### URL
[http://arxiv.org/abs/1807.08093](http://arxiv.org/abs/1807.08093)

##### PDF
[http://arxiv.org/pdf/1807.08093](http://arxiv.org/pdf/1807.08093)


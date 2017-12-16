---
layout: post
title: "Fine-grained Discriminative Localization via Saliency-guided Faster R-CNN"
date: 2017-09-25 02:43:49
categories: arXiv_CV
tags: arXiv_CV Salient Image_Classification Classification
author: Xiangteng He, Yuxin Peng, Junjie Zhao
mathjax: true
---

* content
{:toc}

##### Abstract
Discriminative localization is essential for fine-grained image classification task, which devotes to recognizing hundreds of subcategories in the same basic-level category. Reflecting on discriminative regions of objects, key differences among different subcategories are subtle and local. Existing methods generally adopt a two-stage learning framework: The first stage is to localize the discriminative regions of objects, and the second is to encode the discriminative features for training classifiers. However, these methods generally have two limitations: (1) Separation of the two-stage learning is time-consuming. (2) Dependence on object and parts annotations for discriminative localization learning leads to heavily labor-consuming labeling. It is highly challenging to address these two important limitations simultaneously. Existing methods only focus on one of them. Therefore, this paper proposes the discriminative localization approach via saliency-guided Faster R-CNN to address the above two limitations at the same time, and our main novelties and advantages are: (1) End-to-end network based on Faster R-CNN is designed to simultaneously localize discriminative regions and encode discriminative features, which accelerates classification speed. (2) Saliency-guided localization learning is proposed to localize the discriminative region automatically, avoiding labor-consuming labeling. Both are jointly employed to simultaneously accelerate classification speed and eliminate dependence on object and parts annotations. Comparing with the state-of-the-art methods on the widely-used CUB-200-2011 dataset, our approach achieves both the best classification accuracy and efficiency.

##### Abstract (translated by Google)
对于细粒度的图像分类任务来说，区分性定位是必不可少的，该任务致力于识别同一基本类别中的数百个子类别。反映在对象的区别性区域，不同子类别之间的关键差异是微妙的和局部的。现有方法一般采用两阶段学习框架：第一阶段是对目标的判别区域进行局部化，第二阶段是对训练分类器的判别特征进行编码。但是，这些方法一般有两个局限性：（1）两阶段学习的分离是耗时的。 （2）对于区分性定位学习的对象和部分注释的依赖导致耗费大量劳动力的标签。同时解决这两个重要的限制是非常具有挑战性的。现有的方法只关注其中的一个。因此，本文提出了一种基于显着指导的快速R-CNN的区分性定位方法，同时解决了上述两个局限性，主要的新颖性和优点是：（1）基于R-RNC的端到端网络， CNN旨在同时定位区分区域和编码区分特征，从而加快分类速度。 （2）提出了显着性引导下的定位学习，实现对判别区域的自动定位，避免了耗费劳力的标注。两者共同用于同时加快分类速度并消除对对象和零件注释的依赖。与广泛使用的CUB-200-2011数据集中最先进的方法相比，我们的方法实现了最佳的分类精度和效率。

##### URL
[https://arxiv.org/abs/1709.08295](https://arxiv.org/abs/1709.08295)

##### PDF
[https://arxiv.org/pdf/1709.08295](https://arxiv.org/pdf/1709.08295)


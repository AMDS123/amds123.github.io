---
layout: post
title: "SLAC: A Sparsely Labeled Dataset for Action Classification and Localization"
date: 2017-12-26 19:09:11
categories: arXiv_AI
tags: arXiv_AI Sparse Action_Recognition Classification Prediction Recognition
author: Hang Zhao, Zhicheng Yan, Heng Wang, Lorenzo Torresani, Antonio Torralba
mathjax: true
---

* content
{:toc}

##### Abstract
This paper describes a procedure for the creation of large-scale video datasets for action classification and localization from unconstrained, realistic web data. The scalability of the proposed procedure is demonstrated by building a novel video benchmark, named SLAC (Sparsely Labeled ACtions), consisting of over 520K untrimmed videos and 1.75M clip annotations spanning 200 action categories. Using our proposed framework, annotating a clip takes merely 8.8 seconds on average. This represents a saving in labeling time of over 95% compared to the traditional procedure of manual trimming and localization of actions. Our approach dramatically reduces the amount of human labeling by automatically identifying hard clips, i.e., clips that contain coherent actions but lead to prediction disagreement between action classifiers. A human annotator can disambiguate whether such a clip truly contains the hypothesized action in a handful of seconds, thus generating labels for highly informative samples at little cost. We show that our large-scale dataset can be used to effectively pre-train action recognition models, significantly improving final metrics on smaller-scale benchmarks after fine-tuning. On Kinetics, UCF-101 and HMDB-51, models pre-trained on SLAC outperform baselines trained from scratch, by 2.0%, 20.1% and 35.4% in top-1 accuracy, respectively when RGB input is used. Furthermore, we introduce a simple procedure that leverages the sparse labels in SLAC to pre-train action localization models. On THUMOS14 and ActivityNet-v1.3, our localization model improves the mAP of baseline model by 8.6% and 2.5%, respectively.

##### Abstract (translated by Google)
本文描述了一个创建大规模的视频数据集的行动分类和本地化从无约束，现实的网络数据的程序。通过构建一个名为SLAC（Sparsely Labeled ACtions）的新颖视频基准，演示了所提议的过程的可扩展性，该基准包括520K未修剪的视频和跨越200个动作类别的1.75M剪辑注释。使用我们提出的框架，注释剪辑平均只需8.8秒。与传统的手动修剪和动作定位相比，这样可以节省超过95％的贴标时间。我们的方法通过自动识别硬剪辑，即包含相干动作但导致动作分类器之间的预测不一致的剪辑，显着减少了人类标记的数量。人类注释者可以消除这样一个片段在几秒钟内是否真的包含假设的动作，从而以很少的成本为高度信息化的样本生成标签。我们表明，我们的大规模数据集可以用来有效地预训练动作识别模型，在微调之后显着改善小规模基准测试的最终指标。在动力学方面，当使用RGB输入时，UCF-101和HMDB-51在SLAC上预训练的模型性能优于从头开始训练的基线，分别达到前1精度的2.0％，20.1％和35.4％。此外，我们介绍一个简单的过程，利用SLAC中的稀疏标签来预先训练动作定位模型。在THUMOS14和ActivityNet-v1.3中，我们的定位模型分别将基线模型的mAP分别提高了8.6％和2.5％。

##### URL
[http://arxiv.org/abs/1712.09374](http://arxiv.org/abs/1712.09374)

##### PDF
[http://arxiv.org/pdf/1712.09374](http://arxiv.org/pdf/1712.09374)


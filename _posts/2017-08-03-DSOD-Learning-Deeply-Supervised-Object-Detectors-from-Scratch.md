---
layout: post
title: "DSOD: Learning Deeply Supervised Object Detectors from Scratch"
date: 2017-08-03 17:33:05
categories: arXiv_CV
tags: arXiv_CV Object_Detection Classification Detection
author: Zhiqiang Shen, Zhuang Liu, Jianguo Li, Yu-Gang Jiang, Yurong Chen, Xiangyang Xue
mathjax: true
---

* content
{:toc}

##### Abstract
We present Deeply Supervised Object Detector (DSOD), a framework that can learn object detectors from scratch. State-of-the-art object objectors rely heavily on the off-the-shelf networks pre-trained on large-scale classification datasets like ImageNet, which incurs learning bias due to the difference on both the loss functions and the category distributions between classification and detection tasks. Model fine-tuning for the detection task could alleviate this bias to some extent but not fundamentally. Besides, transferring pre-trained models from classification to detection between discrepant domains is even more difficult (e.g. RGB to depth images). A better solution to tackle these two critical problems is to train object detectors from scratch, which motivates our proposed DSOD. Previous efforts in this direction mostly failed due to much more complicated loss functions and limited training data in object detection. In DSOD, we contribute a set of design principles for training object detectors from scratch. One of the key findings is that deep supervision, enabled by dense layer-wise connections, plays a critical role in learning a good detector. Combining with several other principles, we develop DSOD following the single-shot detection (SSD) framework. Experiments on PASCAL VOC 2007, 2012 and MS COCO datasets demonstrate that DSOD can achieve better results than the state-of-the-art solutions with much more compact models. For instance, DSOD outperforms SSD on all three benchmarks with real-time detection speed, while requires only 1/2 parameters to SSD and 1/10 parameters to Faster RCNN. Our code and models are available at: this https URL .

##### Abstract (translated by Google)
我们提出深度监督对象探测器（DSOD），一个可以从头学习对象探测器的框架。最先进的对象反对者在很大程度上依赖于像ImageNet这样的大规模分类数据集预先训练的现成网络，由于丢失函数和分类之间的类别分布上的差异而导致学习偏差和检测任务。模型微调检测任务可以在一定程度上缓解这种偏见，但不是根本的。此外，将预先训练的模型从分类转移到差异域之间的检测甚至更加困难（例如RGB到深度图像）。解决这两个关键问题的一个更好的解决方案是从零开始培训物体探测器，这激励了我们提出的DSOD。以往在这方面的努力大都失败了，因为损失函数更为复杂，而且对象检测中的训练数据有限。在DSOD中，我们从零开始提供了一套用于培训物体检测器的设计原则。其中一个关键的发现是，通过密集的分层连接实现的深度监督在学习一个好的探测器方面起着至关重要的作用。结合其他几个原则，我们开发DSOD，遵循单次检测（SSD）框架。在PASCAL VOC 2007,2012和MS COCO数据集上进行的实验表明，DSOD比拥有更紧凑型号的最新解决方案能够取得更好的结果。例如，DSOD在所有三个基准测试中的表现均优于SSD，具有实时的检测速度，而只需要SSD的1/2参数和更快的RCNN的1/10参数。我们的代码和模型可在此https网址获得。

##### URL
[https://arxiv.org/abs/1708.01241](https://arxiv.org/abs/1708.01241)

##### PDF
[https://arxiv.org/pdf/1708.01241](https://arxiv.org/pdf/1708.01241)


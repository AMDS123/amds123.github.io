---
layout: post
title: "CutMix: Regularization Strategy to Train Strong Classifiers with Localizable Features"
date: 2019-05-13 08:10:22
categories: arXiv_CV
tags: arXiv_CV Image_Caption Regularization Caption CNN Classification Detection
author: Sangdoo Yun, Dongyoon Han, Seong Joon Oh, Sanghyuk Chun, Junsuk Choe, Youngjoon Yoo
mathjax: true
---

* content
{:toc}

##### Abstract
Regional dropout strategies have been proposed to enhance the performance of convolutional neural network classifiers. They have proved to be effective for guiding the model to attend on less discriminative parts of objects (\eg leg as opposed to head of a person), thereby letting the network generalize better and have better object localization capabilities. On the other hand, current methods for regional dropout removes informative pixels on training images by overlaying a patch of either black pixels or random noise. {Such removal is not desirable because it leads to information loss and inefficiency during training.} We therefore propose the CutMix augmentation strategy: patches are cut and pasted among training images where the ground truth labels are also mixed proportionally to the area of the patches. By making efficient use of training pixels and \mbox{retaining} the regularization effect of regional dropout, CutMix consistently outperforms the state-of-the-art augmentation strategies on CIFAR and ImageNet classification tasks, as well as on the ImageNet weakly-supervised localization task. Moreover, unlike previous augmentation methods, our CutMix-trained ImageNet classifier, when used as a pretrained model, results in consistent performance gains in Pascal detection and MS-COCO image captioning benchmarks. We also show that CutMix improves the model robustness against input corruptions and its out-of-distribution detection performances.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1905.04899](http://arxiv.org/abs/1905.04899)

##### PDF
[http://arxiv.org/pdf/1905.04899](http://arxiv.org/pdf/1905.04899)


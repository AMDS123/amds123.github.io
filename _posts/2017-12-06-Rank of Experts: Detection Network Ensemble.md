---
layout: post
title: 'Rank of Experts: Detection Network Ensemble'
date: 2017-12-06 02:05:30
categories: arXiv_CV
tags: arXiv_CV Detection
author: Seung-Hwan Bae, Youngwan Lee, Youngjoo Jo, Yuseok Bae, Joong-won Hwang
---

* content
{:toc}

##### Abstract
The recent advances of convolutional detectors show impressive performance improvement for large scale object detection. However, in general, the detection performance usually decreases as the object classes to be detected increases, and it is a practically challenging problem to train a dominant model for all classes due to the limitations of detection models and datasets. In most cases, therefore, there are distinct performance differences of the modern convolutional detectors for each object class detection. In this paper, in order to build an ensemble detector for large scale object detection, we present a conceptually simple but very effective class-wise ensemble detection which is named as Rank of Experts. We first decompose an intractable problem of finding the best detections for all object classes into small subproblems of finding the best ones for each object class. We then solve the detection problem by ranking detectors in order of the average precision rate for each class, and then aggregate the responses of the top ranked detectors (i.e. experts) for class-wise ensemble detection. The main benefit of our method is easy to implement and does not require any joint training of experts for ensemble. Based on the proposed Rank of Experts, we won the 2nd place in the ILSVRC 2017 object detection competition.

##### Abstract (translated by Google)
卷积检测器的最新进展显示出大规模物体检测性能的显着提高。然而，一般来说，检测性能通常随着待检测对象类别的增加而降低，并且由于检测模型和数据集的局限性，训练所有类别的主导模型是实际上具有挑战性的问题。因此，在大多数情况下，现代卷积检测器对于每个对象类别检测具有明显的性能差异。为了构建大规模目标检测的集成检测器，本文提出了一个概念上简单但非常有效的分类集成检测方法，称为秩专家。我们首先将所有对象类的最佳检测分解为寻找每个对象类的最佳子问题的小子问题。然后，我们通过按照每个类别的平均精确率的顺序排列检测器来解决检测问题，然后汇总排名最高的检测器（即专家）的响应以进行分类集合检测。我们的方法的主要优点是易于实施，不需要联合专家的联合培训。基于提出的专家级别，我们在ILSVRC 2017对象检测竞赛中获得了第二名。

##### URL
[https://arxiv.org/abs/1712.00185](https://arxiv.org/abs/1712.00185)


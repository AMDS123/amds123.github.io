---
layout: post
title: "Revisiting knowledge transfer for training object class detectors"
date: 2017-12-14 09:53:53
categories: arXiv_CV
tags: arXiv_CV Object_Detection Knowledge Weakly_Supervised GAN Transfer_Learning Detection
author: Jasper Uijlings, Stefan Popov, Vittorio Ferrari
mathjax: true
---

* content
{:toc}

##### Abstract
We propose to revisit knowledge transfer for training object detectors on target classes from weakly supervised training images, helped by a set of source classes with bounding-box annotations. We present a unified knowledge transfer framework based on training a single neural network multi-class object detector over all source classes, organized in a semantic hierarchy. This generates proposals with scores at multiple levels in the hierarchy, which we use to explore knowledge transfer over a broad range of generality, ranging from class-specific (bicycle to motorbike) to class-generic (objectness to any class). Experiments on the 200 object classes in the ILSVRC 2013 detection dataset show that our technique (1) leads to much better performance on the target classes (70.3% CorLoc, 36.9% mAP) than a weakly supervised baseline which uses manually engineered objectness [10] (50.5% CorLoc, 25.4% mAP). (2) delivers target object detectors reaching 80% of the mAP of their fully supervised counterparts. (3) outperforms the best reported transfer learning results [17, 42] on this dataset (+41% CorLoc, +3% mAP). Moreover, we also carry out several across-dataset knowledge transfer experiments [25, 22, 32] and find that (4) our technique outperforms the weakly supervised baseline in all dataset pairs by 1.5x - 1.9x, establishing its general applicability.

##### Abstract (translated by Google)
我们建议从弱监督训练图像重新审视目标类别上的训练目标检测器的知识转移，并通过一组带有包围盒注释的源类来帮助。我们提出了一个统一的知识转移框架的基础上，训练一个单一的神经网络多类对象检测器在所有源类，组织在一个语义层次。这就产生了分层次上的多个分数的提案，我们用这个分数来探索广泛的知识转移，从特定类别（自行车到摩托车）到类别通用（对象到任何类别）。对ILSVRC 2013检测数据库中的200个对象类进行的实验表明，我们的技术（1）在目标类别（70.3％CorLoc，36.9％mAP）上导致比使用手动工程目标性的弱监督基线更好的性能[10] （50.5％CorLoc，25.4％mAP）。 （2）提供目标物体探测器达到他们完全监督对手的mAP的80％。 （3）胜过这个数据集（+ 41％CorLoc，+ 3％mAP）最好的报告转移学习结果[17,42]。此外，我们还进行了几个跨数据集的知识转移实验[25,22,32]，发现（4）我们的技术比所有数据集对的弱监督基线高出1.5倍--1.9倍，确立了它的一般适用性。

##### URL
[http://arxiv.org/abs/1708.06128](http://arxiv.org/abs/1708.06128)

##### PDF
[http://arxiv.org/pdf/1708.06128](http://arxiv.org/pdf/1708.06128)


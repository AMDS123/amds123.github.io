---
layout: post
title: "DPatch: Attacking Object Detectors with Adversarial Patches"
date: 2018-06-12 01:25:05
categories: arXiv_CV
tags: arXiv_CV Adversarial Object_Detection Face Classification Detection Recognition Face_Recognition
author: Xin Liu, Huanrui Yang, Linghao Song, Hai Li, Yiran Chen
mathjax: true
---

* content
{:toc}

##### Abstract
Object detectors have witnessed great progress in recent years and have been widely deployed in various important real-world scenarios, such as autonomous driving and face recognition. Therefore, it is increasingly vital to investigate the vulnerability of modern object detectors to different types of attacks. In this work, we demonstrate that actually many mainstream detectors (e.g. Faster R-CNN) can be hacked by a tiny adversarial patch. It is a non-trivial task since the original adversarial patch method can only be applied to image-level classifiers and is not capable to deal with the region proposals involved in modern detectors. Instead, here we iteratively evolve a tiny patch inside the input image so that it invalidates both proposal generation and the subsequent region classification of Faster R-CNN, resulting in a successful attack. Specifically, the proposed adversarial patch (namely, DPatch) can be trained toward any targeted class so that all the objects in any region of the scene will be classified as that targeted class. One interesting observation is that the efficiency of DPatch is not influenced by its location: no matter where it resides, the patch can always invalidate RCNN after the same amount of iterations. Furthermore, we find that different target classes have different degrees of vulnerability; and an DPatch with a larger size can perform the attack more effectively. Extensive experiments show that our DPatch can reduce the mAP of a state-of-the-art detector on PASCAL VOC 2012 from 71% to 25% and below.

##### Abstract (translated by Google)
近年来，物体探测器取得了长足的进步，并已广泛应用于各种重要的现实场景，如自动驾驶和人脸识别。因此，研究现代物体探测器对不同类型攻击的脆弱性越来越重要。在这项工作中，我们证明实际上很多主流探测器（例如更快的R-CNN）可能会被微小的敌对补丁破解。这是一个不平凡的任务，因为原始的敌对修补方法只能应用于图像级分类器，并且不能处理现代检测器涉及的区域提案。相反，我们在这里迭代地在输入图像内部发展出一个小小的修补程序，这样它可以使建议生成和随后的R-CNN区域分类无效，从而成功实施攻击。具体而言，建议的敌对补丁（即DPatch）可以针对任何目标类别进行训练，以便场景任何区域中的所有对象都将被分类为该目标类别。一个有趣的现象是DPatch的效率不受其位置的影响：无论它位于何处，修补程序都会在相同的迭代次数后使RCNN失效。此外，我们发现不同的目标类别具有不同程度的脆弱性;而更大尺寸的DPatch可以更有效地执行攻击。大量实验表明，我们的DPatch可以将PASCAL VOC 2012上一流的检测器的mAP从71％降低到25％及以下。

##### URL
[https://arxiv.org/abs/1806.02299](https://arxiv.org/abs/1806.02299)

##### PDF
[https://arxiv.org/pdf/1806.02299](https://arxiv.org/pdf/1806.02299)


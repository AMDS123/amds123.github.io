---
layout: post
title: "Discovering Class-Specific Pixels for Weakly-Supervised Semantic Segmentation"
date: 2017-07-18 19:03:22
categories: arXiv_CV
tags: arXiv_CV Salient Object_Detection Segmentation Attention Weakly_Supervised CNN Semantic_Segmentation Classification Detection
author: Arslan Chaudhry, Puneet K. Dokania, Philip H.S. Torr
mathjax: true
---

* content
{:toc}

##### Abstract
We propose an approach to discover class-specific pixels for the weakly-supervised semantic segmentation task. We show that properly combining saliency and attention maps allows us to obtain reliable cues capable of significantly boosting the performance. First, we propose a simple yet powerful hierarchical approach to discover the class-agnostic salient regions, obtained using a salient object detector, which otherwise would be ignored. Second, we use fully convolutional attention maps to reliably localize the class-specific regions in a given image. We combine these two cues to discover class-specific pixels which are then used as an approximate ground truth for training a CNN. While solving the weakly supervised semantic segmentation task, we ensure that the image-level classification task is also solved in order to enforce the CNN to assign at least one pixel to each object present in the image. Experimentally, on the PASCAL VOC12 val and test sets, we obtain the mIoU of 60.8% and 61.9%, achieving the performance gains of 5.1% and 5.2% compared to the published state-of-the-art results. The code is made publicly available.

##### Abstract (translated by Google)
我们提出一种方法来发现弱监督语义分割任务的类特定像素。我们表明，适当组合显着性和注意力映射使我们能够获得可靠的提示，从而显着提升性能。首先，我们提出了一个简单而强大的分层方法来发现类别不可知的显着区域，使用显着物体检测器获得，否则将被忽略。其次，我们使用完全卷积关注映射来可靠地定位给定图像中的类特定区域。我们结合这两个线索来发现特定于类的像素，然后将其用作训练CNN的近似的基本事实。在解决弱监督的语义分割任务的同时，我们确保图像级分类任务也被解决，以便强制CNN为图像中存在的每个对象分配至少一个像素。在实验上，在PASCAL VOC12 val和测试台上，我们获得了60.8％和61.9％的mIoU，与公布的最新成果相比，性能提高了5.1％和5.2％。该代码是公开的。

##### URL
[https://arxiv.org/abs/1707.05821](https://arxiv.org/abs/1707.05821)

##### PDF
[https://arxiv.org/pdf/1707.05821](https://arxiv.org/pdf/1707.05821)


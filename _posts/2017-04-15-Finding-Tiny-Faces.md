---
layout: post
title: "Finding Tiny Faces"
date: 2017-04-15 06:18:08
categories: arXiv_CV
tags: arXiv_CV Object_Detection Face Detection Recognition
author: Peiyun Hu, Deva Ramanan
mathjax: true
---

* content
{:toc}

##### Abstract
Though tremendous strides have been made in object recognition, one of the remaining open challenges is detecting small objects. We explore three aspects of the problem in the context of finding small faces: the role of scale invariance, image resolution, and contextual reasoning. While most recognition approaches aim to be scale-invariant, the cues for recognizing a 3px tall face are fundamentally different than those for recognizing a 300px tall face. We take a different approach and train separate detectors for different scales. To maintain efficiency, detectors are trained in a multi-task fashion: they make use of features extracted from multiple layers of single (deep) feature hierarchy. While training detectors for large objects is straightforward, the crucial challenge remains training detectors for small objects. We show that context is crucial, and define templates that make use of massively-large receptive fields (where 99% of the template extends beyond the object of interest). Finally, we explore the role of scale in pre-trained deep networks, providing ways to extrapolate networks tuned for limited scales to rather extreme ranges. We demonstrate state-of-the-art results on massively-benchmarked face datasets (FDDB and WIDER FACE). In particular, when compared to prior art on WIDER FACE, our results reduce error by a factor of 2 (our models produce an AP of 82% while prior art ranges from 29-64%).

##### Abstract (translated by Google)
尽管在物体识别方面取得了巨大的进步，但剩下的一个公开挑战是检测小物体。我们从寻找小脸的角度探讨问题的三个方面：尺度不变性，图像分辨率和情境推理的作用。虽然大多数识别方法的目标是不变尺度，但识别3px高的脸部的提示与识别300px高的脸部的提示根本不同。我们采取不同的方法，并针对不同的尺度训练单独的探测器为了保持效率，探测器以多任务方式进行培训：他们利用从单层（深层）特征层次结构中提取的特征。尽管训练大型物体的探测器非常简单，但是关键的挑战仍然是训练小型物体的探测器。我们显示上下文是至关重要的，并定义使用大量接受字段（其中99％的模板超出了感兴趣的对象）的模板。最后，我们探讨了预先训练的深度网络中规模的作用，提供了将有限范围的网络外推到极端范围的方法。我们在大量基准的人脸数据集（FDDB和WIDER FACE）上展示了最先进的结果。尤其是与WIDER FACE的现有技术相比，我们的结果将误差减少了2倍（我们的模型产生82％的AP，而现有技术的范围从29-64％）。

##### URL
[https://arxiv.org/abs/1612.04402](https://arxiv.org/abs/1612.04402)

##### PDF
[https://arxiv.org/pdf/1612.04402](https://arxiv.org/pdf/1612.04402)


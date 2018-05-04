---
layout: post
title: "Transferring Common-Sense Knowledge for Object Detection"
date: 2018-04-03 17:41:53
categories: arXiv_CV
tags: arXiv_CV Object_Detection Knowledge Detection
author: Krishna Kumar Singh, Santosh Divvala, Ali Farhadi, Yong Jae Lee
mathjax: true
---

* content
{:toc}

##### Abstract
We propose the idea of transferring common-sense knowledge from source categories to target categories for scalable object detection. In our setting, the training data for the source categories have bounding box annotations, while those for the target categories only have image-level annotations. Current state-of-the-art approaches focus on image-level visual or semantic similarity to adapt a detector trained on the source categories to the new target categories. In contrast, our key idea is to (i) use similarity not at image-level, but rather at region-level, as well as (ii) leverage richer common-sense (based on attribute, spatial, etc.,) to guide the algorithm towards learning the correct detections. We acquire such common-sense cues automatically from readily-available knowledge bases without any extra human effort. On the challenging MS COCO dataset, we find that using common-sense knowledge substantially improves detection performance over existing transfer-learning baselines.

##### Abstract (translated by Google)
我们提出将源类别中的常识知识转换为可扩展对象检测的目标类别的想法。在我们的设置中，源类别的训练数据具有边界框注释，而针对目标类别的训练数据仅具有图像级注释。目前最先进的方法着重于图像级视觉或语义相似性，以将在源类别上训练的检测器适应新的目标类别。相反，我们的关键思想是（i）不是在图像层面使用相似性，而是在区域层面使用相似性，以及（ii）利用更丰富的常识（基于属性，空间等）来指导该算法用于学习正确的检测。我们从现成的知识库中自动获取这些常识提示，无需额外的人力。在具有挑战性的MS COCO数据集上，我们发现使用常识知识可以大大提高现有传输学习基线的检测性能。

##### URL
[https://arxiv.org/abs/1804.01077](https://arxiv.org/abs/1804.01077)

##### PDF
[https://arxiv.org/pdf/1804.01077](https://arxiv.org/pdf/1804.01077)


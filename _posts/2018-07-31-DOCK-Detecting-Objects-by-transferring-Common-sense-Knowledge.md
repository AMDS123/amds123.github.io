---
layout: post
title: "DOCK: Detecting Objects by transferring Common-sense Knowledge"
date: 2018-07-31 06:42:30
categories: arXiv_AI
tags: arXiv_AI Object_Detection Knowledge Detection
author: Krishna Kumar Singh, Santosh Divvala, Ali Farhadi, Yong Jae Lee
mathjax: true
---

* content
{:toc}

##### Abstract
We present a scalable approach for Detecting Objects by transferring Common-sense Knowledge (DOCK) from source to target categories. In our setting, the training data for the source categories have bounding box annotations, while those for the target categories only have image-level annotations. Current state-of-the-art approaches focus on image-level visual or semantic similarity to adapt a detector trained on the source categories to the new target categories. In contrast, our key idea is to (i) use similarity not at the image-level, but rather at the region-level, and (ii) leverage richer common-sense (based on attribute, spatial, etc.) to guide the algorithm towards learning the correct detections. We acquire such common-sense cues automatically from readily-available knowledge bases without any extra human effort. On the challenging MS COCO dataset, we find that common-sense knowledge can substantially improve detection performance over existing transfer-learning baselines.

##### Abstract (translated by Google)
我们通过将常识知识（DOCK）从源类别转移到目标类别，提出了一种可扩展的检测对象方法。在我们的设置中，源类别的训练数据具有边界框注释，而目标类别的训练数据仅具有图像级注释。当前最先进的方法关注于图像级视觉或语义相似性，以使在源类别上训练的检测器适应新的目标类别。相比之下，我们的主要思想是（i）不是在图像层面使用相似性，而是在区域层面使用相似性，以及（ii）利用更丰富的常识（基于属性，空间等）来指导相似性。学习正确检测的算法。我们从容易获得的知识库中自动获取这些常识线索，而无需任何额外的人力。在具有挑战性的MS COCO数据集中，我们发现常识知识可以显着提高现有转移学习基线的检测性能。

##### URL
[http://arxiv.org/abs/1804.01077](http://arxiv.org/abs/1804.01077)

##### PDF
[http://arxiv.org/pdf/1804.01077](http://arxiv.org/pdf/1804.01077)


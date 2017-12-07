---
layout: post
title: "Inner-Scene Similarities as a Contextual Cue for Object Detection"
date: 2017-07-14 07:37:21
categories: arXiv_CV
tags: arXiv_CV Object_Detection Classification Detection
author: Noa Arbel, Tamar Avraham, Michael Lindenbaum
mathjax: true
---

* content
{:toc}

##### Abstract
Using image context is an effective approach for improving object detection. Previously proposed methods used contextual cues that rely on semantic or spatial information. In this work, we explore a different kind of contextual information: inner-scene similarity. We present the CISS (Context by Inner Scene Similarity) algorithm, which is based on the observation that two visually similar sub-image patches are likely to share semantic identities, especially when both appear in the same image. CISS uses base-scores provided by a base detector and performs as a post-detection stage. For each candidate sub-image (denoted anchor), the CISS algorithm finds a few similar sub-images (denoted supporters), and, using them, calculates a new enhanced score for the anchor. This is done by utilizing the base-scores of the supporters and a pre-trained dependency model. The new scores are modeled as a linear function of the base scores of the anchor and the supporters and is estimated using a minimum mean square error optimization. This approach results in: (a) improved detection of partly occluded objects (when there are similar non-occluded objects in the scene), and (b) fewer false alarms (when the base detector mistakenly classifies a background patch as an object). This work relates to Duncan and Humphreys' "similarity theory," a psychophysical study. which suggested that the human visual system perceptually groups similar image regions and that the classification of one region is affected by the estimated identity of the other. Experimental results demonstrate the enhancement of a base detector's scores on the PASCAL VOC dataset.

##### Abstract (translated by Google)
使用图像上下文是改善对象检测的有效方法。以前提出的方法使用依赖于语义或空间信息的上下文线索。在这项工作中，我们探索了一种不同的情境信息：内心相似。基于两个视觉上相似的子图像块可能共享语义特征的观察结果，特别是当两个子图像出现在同一图像中时，我们提出了CISS（Context by Inner Scene Similarity）算法。 CISS使用由基本检测器提供的基础分数并作为检测后阶段执行。对于每个候选子图像（表示为锚点），CISS算法找到一些相似的子图像（表示为支持者），并使用它们计算锚点的新增强分数。这是通过利用支持者的基础分数和预先训练的依赖模型来完成的。新的分数被建模为锚和支持者的基本分数的线性函数，并且使用最小均方误差优化来估计。这种方法的结果是：（a）改进了对部分遮挡物体的检测（当场景中存在类似的非遮挡物体时）和（b）更少的假警报（当基本检测器错误地将背景区块分类为物体时）。这项工作涉及邓肯和汉弗莱斯的“相似理论”，一项心理学研究。这表明人类视觉系统在感知上对相似图像区域进行分组，并且一个区域的分类受到另一个区域的估计身份的影响。实验结果证明PASCAL VOC数据集上的基本检测器得分的增强。

##### URL
[https://arxiv.org/abs/1707.04406](https://arxiv.org/abs/1707.04406)

##### PDF
[https://arxiv.org/pdf/1707.04406](https://arxiv.org/pdf/1707.04406)


---
layout: post
title: "Cardiac Motion Scoring with Segment- and Subject-level Non-Local Modeling"
date: 2018-06-14 14:20:59
categories: arXiv_CV
tags: arXiv_CV CNN Detection Relation
author: Wufeng Xue, Gary Brahm, Stephanie Leung, Ogla Shmuilovich, Shuo Li
mathjax: true
---

* content
{:toc}

##### Abstract
Motion scoring of cardiac myocardium is of paramount importance for early detection and diagnosis of various cardiac disease. It aims at identifying regional wall motions into one of the four types including normal, hypokinetic, akinetic, and dyskinetic, and is extremely challenging due to the complex myocardium deformation and subtle inter-class difference of motion patterns. All existing work on automated motion analysis are focused on binary abnormality detection to avoid the much more demanding motion scoring, which is urgently required in real clinical practice yet has never been investigated before. In this work, we propose Cardiac-MOS, the first powerful method for cardiac motion scoring from cardiac MR sequences based on deep convolution neural network. Due to the locality of convolution, the relationship between distant non-local responses of the feature map cannot be explored, which is closely related to motion difference between segments. In Cardiac-MOS, such non-local relationship is modeled with non-local neural network within each segment and across all segments of one subject, i.e., segment- and subject-level non-local modeling, and lead to obvious performance improvement. Besides, Cardiac-MOS can effectively extract motion information from MR sequences of various lengths by interpolating the convolution kernel along the temporal dimension, therefore can be applied to MR sequences of multiple sources. Experiments on 1440 myocardium segments of 90 subjects from short axis MR sequences of multiple lengths prove that Cardiac-MOS achieves reliable performance, with correlation of 0.926 for motion score index estimation and accuracy of 77.4\% for motion scoring. Cardiac-MOS also outperforms all existing work for binary abnormality detection. As the first automatic motion scoring solution, Cardiac-MOS demonstrates great potential in future clinical application.

##### Abstract (translated by Google)
心肌运动评分对于早期发现和诊断各种心脏疾病非常重要。它旨在将区域性运动分为四种类型之一，包括正常运动，运动减弱运动，运动不能运动和运动障碍运动，并且由于复杂的心肌变形和运动模式之间的细微差异，极具挑战性。所有关于自动运动分析的工作都集中在二进制异常检测上，以避免更为苛刻的运动评分，这是临床实践中迫切需要的，但从未被调查过。在这项工作中，我们提出Cardiac-MOS，这是第一个基于深度卷积神经网络的强大的心脏运动评分方法。由于卷积的局部性，特征图的远距离非局部响应之间的关系无法探索，这与段之间的运动差异密切相关。在Cardiac-MOS中，这样的非局部关系在每个片段内以及一个主题的所有片段（即片段和主体层面的非局部建模）中与非局部神经网络建模，并导致明显的性能改进。此外，Cardiac-MOS可以通过沿时间维插值卷积核来有效地从各种长度的MR序列中提取运动信息，因此可以应用于多源MR序列。对90例不同长度短轴MR序列患者的1440个心肌节段进行实验，证明Cardiac-MOS实现了可靠的性能，运动评分指数估计的相关性为0.926，运动评分的准确性为77.4％。 Cardiac-MOS也优于所有现有的二进制异常检测工作。作为第一个自动运动计分解决方案，Cardiac-MOS在未来的临床应用中显示出巨大的潜力。

##### URL
[http://arxiv.org/abs/1806.05569](http://arxiv.org/abs/1806.05569)

##### PDF
[http://arxiv.org/pdf/1806.05569](http://arxiv.org/pdf/1806.05569)


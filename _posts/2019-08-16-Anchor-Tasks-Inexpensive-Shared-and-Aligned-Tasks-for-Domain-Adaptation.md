---
layout: post
title: "Anchor Tasks: Inexpensive, Shared, and Aligned Tasks for Domain Adaptation"
date: 2019-08-16 17:59:18
categories: arXiv_CV
tags: arXiv_CV Segmentation Face Semantic_Segmentation Prediction Relation
author: Zhizhong Li, Linjie Luo, Sergey Tulyakov, Qieyun Dai, Derek Hoiem
mathjax: true
---

* content
{:toc}

##### Abstract
We introduce a novel domain adaptation formulation from synthetic dataset (source domain) to real dataset (target domain) for the category of tasks with per-pixel predictions. The annotations of these tasks are relatively hard to acquire in the real world, such as single-view depth estimation or surface normal estimation. Our key idea is to introduce anchor tasks, whose annotations are (1) less expensive to acquire than the main task, such as facial landmarks and semantic segmentations; and (2) shared in availability for both synthetic and real datasets so that it serves as "anchor" between tasks; and finally (3) aligned spatially with main task annotations on a per-pixel basis so that it also serves as spatial anchor between tasks' outputs. To further utilize spatial alignment between the anchor and main tasks, we introduce a novel freeze approach that freezes the final layers of our network after training on the source domain so that spatial and contextual relationship between tasks are maintained when adapting on the target domain. We evaluate our methods on two pairs of datasets, performing surface normal estimation in indoor scenes and faces, using semantic segmentation and facial landmarks as anchor tasks separately. We show the importance of using anchor tasks in both synthetic and real domains, and that the freeze approach outperforms competing approaches, reaching results in facial images on par with the state-of-the-art system that leverages detailed facial appearance model.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1908.06079](https://arxiv.org/abs/1908.06079)

##### PDF
[https://arxiv.org/pdf/1908.06079](https://arxiv.org/pdf/1908.06079)


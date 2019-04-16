---
layout: post
title: "PatchFCN for Intracranial Hemorrhage Detection"
date: 2019-04-14 23:09:29
categories: arXiv_CV
tags: arXiv_CV Object_Detection Segmentation CNN Semantic_Segmentation Classification Detection
author: Weicheng Kuo, Christian H&#xe4;ne, Esther Yuh, Pratik Mukherjee, Jitendra Malik
mathjax: true
---

* content
{:toc}

##### Abstract
This paper studies the problem of detecting and segmenting acute intracranial hemorrhage on head computed tomography (CT) scans. We propose to solve both tasks as a semantic segmentation problem using a patch-based fully convolutional network (PatchFCN). This formulation allows us to accurately localize hemorrhages while bypassing the complexity of object detection. Our system demonstrates competitive performance with a human expert and the state-of-the-art on classification tasks (0.976, 0.966 AUC of ROC on retrospective and prospective test sets) and on segmentation tasks (0.785 pixel AP, 0.766 Dice score), while using much less data and a simpler system. In addition, we conduct a series of controlled experiments to understand "why" PatchFCN outperforms standard FCN. Our studies show that PatchFCN finds a good trade-off between batch diversity and the amount of context during training. These findings may also apply to other medical segmentation tasks.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1806.03265](http://arxiv.org/abs/1806.03265)

##### PDF
[http://arxiv.org/pdf/1806.03265](http://arxiv.org/pdf/1806.03265)


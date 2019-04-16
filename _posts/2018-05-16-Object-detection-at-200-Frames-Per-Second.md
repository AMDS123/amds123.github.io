---
layout: post
title: "Object detection at 200 Frames Per Second"
date: 2018-05-16 15:07:09
categories: arXiv_CV
tags: arXiv_CV Object_Detection Knowledge Detection
author: Rakesh Mehta, Cemalettin Ozturk
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper, we propose an efficient and fast object detector which can process hundreds of frames per second. To achieve this goal we investigate three main aspects of the object detection framework: network architecture, loss function and training data (labeled and unlabeled). In order to obtain compact network architecture, we introduce various improvements, based on recent work, to develop an architecture which is computationally light-weight and achieves a reasonable performance. To further improve the performance, while keeping the complexity same, we utilize distillation loss function. Using distillation loss we transfer the knowledge of a more accurate teacher network to proposed light-weight student network. We propose various innovations to make distillation efficient for the proposed one stage detector pipeline: objectness scaled distillation loss, feature map non-maximal suppression and a single unified distillation loss function for detection. Finally, building upon the distillation loss, we explore how much can we push the performance by utilizing the unlabeled data. We train our model with unlabeled data using the soft labels of the teacher network. Our final network consists of 10x fewer parameters than the VGG based object detection network and it achieves a speed of more than 200 FPS and proposed changes improve the detection accuracy by 14 mAP over the baseline on Pascal dataset.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1805.06361](https://arxiv.org/abs/1805.06361)

##### PDF
[https://arxiv.org/pdf/1805.06361](https://arxiv.org/pdf/1805.06361)


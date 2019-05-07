---
layout: post
title: "A-Fast-RCNN: Hard Positive Generation via Adversary for Object Detection"
date: 2017-04-11 16:57:52
categories: arXiv_CV
tags: arXiv_CV Adversarial Object_Detection Detection
author: Xiaolong Wang, Abhinav Shrivastava, Abhinav Gupta
mathjax: true
---

* content
{:toc}

##### Abstract
How do we learn an object detector that is invariant to occlusions and deformations? Our current solution is to use a data-driven strategy -- collect large-scale datasets which have object instances under different conditions. The hope is that the final classifier can use these examples to learn invariances. But is it really possible to see all the occlusions in a dataset? We argue that like categories, occlusions and object deformations also follow a long-tail. Some occlusions and deformations are so rare that they hardly happen; yet we want to learn a model invariant to such occurrences. In this paper, we propose an alternative solution. We propose to learn an adversarial network that generates examples with occlusions and deformations. The goal of the adversary is to generate examples that are difficult for the object detector to classify. In our framework both the original detector and adversary are learned in a joint manner. Our experimental results indicate a 2.3% mAP boost on VOC07 and a 2.6% mAP boost on VOC2012 object detection challenge compared to the Fast-RCNN pipeline. We also release the code for this paper.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1704.03414](https://arxiv.org/abs/1704.03414)

##### PDF
[https://arxiv.org/pdf/1704.03414](https://arxiv.org/pdf/1704.03414)


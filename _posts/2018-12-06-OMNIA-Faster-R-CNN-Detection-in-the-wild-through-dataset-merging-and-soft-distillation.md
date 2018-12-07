---
layout: post
title: "OMNIA Faster R-CNN: Detection in the wild through dataset merging and soft distillation"
date: 2018-12-06 15:38:43
categories: arXiv_CV
tags: arXiv_CV Object_Detection Transfer_Learning Classification Prediction Detection
author: Alexandre Rame, Emilien Garreau, Hedi Ben-Younes, Charles Ollion
mathjax: true
---

* content
{:toc}

##### Abstract
Object detectors tend to perform poorly in new or open domains, and require exhaustive yet costly annotations from fully labeled datasets. We aim at benefiting from several datasets with different categories but without additional labelling, not only to increase the number of categories detected, but also to take advantage from transfer learning and to enhance domain independence. 
 Our dataset merging procedure starts with training several initial Faster R-CNN on the different datasets while considering the complementary datasets' images for domain adaptation. Similarly to self-training methods, the predictions of these initial detectors mitigate the missing annotations on the complementary datasets. The final OMNIA Faster R-CNN is trained with all categories on the union of the datasets enriched by predictions. The joint training handles unsafe targets with a new classification loss called SoftSig in a softly supervised way. 
 Experimental results show that in the case of fashion detection for images in the wild, merging Modanet with COCO increases the final performance from 45.5% to 57.4%. Applying our soft distillation to the task of detection with domain shift on Cityscapes enables to beat the state-of-the-art by 5.3 points. We hope that our methodology could unlock object detection for real-world applications without immense datasets.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1812.02611](http://arxiv.org/abs/1812.02611)

##### PDF
[http://arxiv.org/pdf/1812.02611](http://arxiv.org/pdf/1812.02611)


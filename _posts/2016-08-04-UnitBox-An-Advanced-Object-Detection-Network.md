---
layout: post
title: "UnitBox: An Advanced Object Detection Network"
date: 2016-08-04 09:06:15
categories: arXiv_CV
tags: arXiv_CV Object_Detection Face CNN Prediction Detection Face_Detection
author: Jiahui Yu, Yuning Jiang, Zhangyang Wang, Zhimin Cao, Thomas Huang
mathjax: true
---

* content
{:toc}

##### Abstract
In present object detection systems, the deep convolutional neural networks (CNNs) are utilized to predict bounding boxes of object candidates, and have gained performance advantages over the traditional region proposal methods. However, existing deep CNN methods assume the object bounds to be four independent variables, which could be regressed by the $\ell_2$ loss separately. Such an oversimplified assumption is contrary to the well-received observation, that those variables are correlated, resulting to less accurate localization. To address the issue, we firstly introduce a novel Intersection over Union ($IoU$) loss function for bounding box prediction, which regresses the four bounds of a predicted box as a whole unit. By taking the advantages of $IoU$ loss and deep fully convolutional networks, the UnitBox is introduced, which performs accurate and efficient localization, shows robust to objects of varied shapes and scales, and converges fast. We apply UnitBox on face detection task and achieve the best performance among all published methods on the FDDB benchmark.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1608.01471](https://arxiv.org/abs/1608.01471)

##### PDF
[https://arxiv.org/pdf/1608.01471](https://arxiv.org/pdf/1608.01471)


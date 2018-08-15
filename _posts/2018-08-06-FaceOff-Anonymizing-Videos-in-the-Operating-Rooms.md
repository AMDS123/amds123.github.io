---
layout: post
title: "FaceOff: Anonymizing Videos in the Operating Rooms"
date: 2018-08-06 09:36:08
categories: arXiv_AI
tags: arXiv_AI Face Deep_Learning Detection Face_Detection
author: Evangello Flouty, Odysseas Zisimopoulos, Danail Stoyanov
mathjax: true
---

* content
{:toc}

##### Abstract
Video capture in the surgical operating room (OR) is increasingly possible and has potential for use with computer assisted interventions (CAI), surgical data science and within smart OR integration. Captured video innately carries sensitive information that should not be completely visible in order to preserve the patient's and the clinical teams' identities. When surgical video streams are stored on a server, the videos must be anonymized prior to storage if taken outside of the hospital. In this article, we describe how a deep learning model, Faster R-CNN, can be used for this purpose and help to anonymize video data captured in the OR. The model detects and blurs faces in an effort to preserve anonymity. After testing an existing face detection trained model, a new dataset tailored to the surgical environment, with faces obstructed by surgical masks and caps, was collected for fine-tuning to achieve higher face-detection rates in the OR. We also propose a temporal regularisation kernel to improve recall rates. The fine-tuned model achieves a face detection recall of 88.05 % and 93.45 % before and after applying temporal-smoothing respectively.

##### Abstract (translated by Google)
外科手术室（OR）中的视频捕获越来越可能，并且有可能与计算机辅助干预（CAI），外科数据科学和智能OR集成一起使用。捕获的视频天生地携带不应完全可见的敏感信息，以保护患者和临床团队的身份。当外科视频流存储在服务器上时，如果在医院外拍摄，则必须在存储之前对视频进行匿名处理。在本文中，我们将描述深度学习模型（快速R-CNN）如何用于此目的，并帮助匿名化OR中捕获的视频数据。该模型检测并模糊面孔以努力保持匿名。在测试现有的面部检测训练模型之后，收集针对手术环境定制的新数据集，其具有被手术口罩和帽盖住的面部，以进行微调以在OR中实现更高的面部检测率。我们还提出了一个时间正则化内核来提高召回率。经过微调的模型分别在应用时间平滑之前和之后实现了88.05％和93.45％的面部检测召回。

##### URL
[http://arxiv.org/abs/1808.04440](http://arxiv.org/abs/1808.04440)

##### PDF
[http://arxiv.org/pdf/1808.04440](http://arxiv.org/pdf/1808.04440)


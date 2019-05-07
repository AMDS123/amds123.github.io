---
layout: post
title: "Object Detection in Videos by High Quality Object Linking"
date: 2019-04-08 07:56:01
categories: arXiv_CV
tags: arXiv_CV Object_Detection Classification Detection
author: Peng Tang, Chunyu Wang, Xinggang Wang, Wenyu Liu, Wenjun Zeng, Jingdong Wang
mathjax: true
---

* content
{:toc}

##### Abstract
Compared with object detection in static images, object detection in videos is more challenging due to degraded image qualities. An effective way to address this problem is to exploit temporal contexts by linking the same object across video to form tubelets and aggregating classification scores in the tubelets. In this paper, we focus on obtaining high quality object linking results for better classification. Unlike previous methods that link objects by checking boxes between neighboring frames, we propose to link in the same frame. To achieve this goal, we extend prior methods in following aspects: (1) a cuboid proposal network that extracts spatio-temporal candidate cuboids which bound the movement of objects; (2) a short tubelet detection network that detects short tubelets in short video segments; (3) a short tubelet linking algorithm that links temporally-overlapping short tubelets to form long tubelets. Experiments on the ImageNet VID dataset show that our method outperforms both the static image detector and the previous state of the art. In particular, our method improves results by 8.8% over the static image detector for fast moving objects.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1801.09823](https://arxiv.org/abs/1801.09823)

##### PDF
[https://arxiv.org/pdf/1801.09823](https://arxiv.org/pdf/1801.09823)


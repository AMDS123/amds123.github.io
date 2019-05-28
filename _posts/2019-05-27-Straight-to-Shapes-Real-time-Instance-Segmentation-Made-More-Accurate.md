---
layout: post
title: "Straight to Shapes++: Real-time Instance Segmentation Made More Accurate"
date: 2019-05-27 17:35:19
categories: arXiv_AI
tags: arXiv_AI Segmentation Drone Embedding Prediction
author: Laurynas Miksys, Saumya Jetley, Michael Sapienza, Stuart Golodetz, Philip H.S. Torr
mathjax: true
---

* content
{:toc}

##### Abstract
Instance segmentation is an important problem in computer vision, with applications in autonomous driving, drone navigation and robotic manipulation. However, most existing methods are not real-time, complicating their deployment in time-sensitive contexts. In this work, we extend an existing approach to real-time instance segmentation, called `Straight to Shapes' (STS), which makes use of low-dimensional shape embedding spaces to directly regress to object shape masks. The STS model can run at 35 FPS on a high-end desktop, but its accuracy is significantly worse than that of offline state-of-the-art methods. We leverage recent advances in the design and training of deep instance segmentation models to improve the performance accuracy of the STS model whilst keeping its real-time capabilities intact. In particular, we find that parameter sharing, more aggressive data augmentation and the use of structured loss for shape mask prediction all provide a useful boost to the network performance. Our proposed approach, `Straight to Shapes++', achieves a remarkable 19.7 point improvement in mAP (at IOU of 0.5) over the original method as evaluated on the PASCAL VOC dataset, thus redefining the accuracy frontier at real-time speeds. Since the accuracy of instance segmentation is closely tied to that of object bounding box prediction, we also study the error profile of the latter and examine the failure modes of our method for future improvements.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1905.11358](https://arxiv.org/abs/1905.11358)

##### PDF
[https://arxiv.org/pdf/1905.11358](https://arxiv.org/pdf/1905.11358)


---
layout: post
title: "3-D/2-D Registration of Cardiac Structures by 3-D Contrast Agent Distribution Estimation"
date: 2016-01-22 16:23:25
categories: arXiv_CV
tags: arXiv_CV
author: Matthias Hoffmann, Christopher Kowalewski, Andreas Maier, Klaus Kurzidim, Norbert Strobel, Joachim Hornegger
mathjax: true
---

* content
{:toc}

##### Abstract
For augmented fluoroscopy during cardiac catheter ablation procedures, a preoperatively acquired 3-D model of the left atrium of the patient can be registered to X-ray images. Therefore the 3D-model is matched with the contrast agent based appearance of the left atrium. Commonly, only small amounts of contrast agent (CA) are used to locate the left atrium. This is why we focus on robust registration methods that work also if the structure of interest is only partially contrasted. In particular, we propose two similarity measures for CA-based registration: The first similarity measure, explicit apparent edges, focuses on edges of the patient anatomy made visible by contrast agent and can be computed quickly on the GPU. The second novel similarity measure computes a contrast agent distribution estimate (CADE) inside the 3-D model and rates its consistency with the CA seen in biplane fluoroscopic images. As the CADE computation involves a reconstruction of CA in 3-D using the CA within the fluoroscopic images, it is slower. Using a combination of both methods, our evaluation on 11 well-contrasted clinical datasets yielded an error of 7.9+/-6.3 mm over all frames. For 10 datasets with little CA, we obtained an error of 8.8+/-6.7 mm. Our new methods outperform a registration based on the projected shadow significantly (p<0.05).

##### Abstract (translated by Google)
对于在心脏导管消融手术期间的增强透视，可以将术前采集的患者左心房的3-D模型配准到X射线图像。因此，3D模型与左心房的基于造影剂的外观相匹配。通常，只有少量造影剂（CA）用于定位左心房。这就是为什么我们关注强大的注册方法，如果感兴趣的结构只是部分对比的话也是有用的。具体而言，我们提出了两种基于CA的注册的相似性度量：第一个相似性度量，明确的边缘，侧重于病人解剖结构的边缘，使其可以在GPU上快速计算。第二种新颖的相似性测量计算三维模型内的造影剂分布估计（CADE），并评估其与在双翼透视图像中看到的CA的一致性。由于CADE计算涉及在透视图像中使用CA重建CA三维，所以其速度较慢。使用这两种方法的组合，我们对11个对比良好的临床数据集的评估在所有帧中产生了7.9 +/- 6.3mm的误差。对于CA少的10个数据集，我们得到了8.8 +/- 6.7mm的误差。我们的新方法比基于预计阴影的登记显着优于（p <0.05）。

##### URL
[https://arxiv.org/abs/1601.06062](https://arxiv.org/abs/1601.06062)

##### PDF
[https://arxiv.org/pdf/1601.06062](https://arxiv.org/pdf/1601.06062)


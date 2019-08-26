---
layout: post
title: "In-bed Pressure-based Pose Estimation using Image Space Representation Learning"
date: 2019-08-21 01:52:54
categories: arXiv_CV
tags: arXiv_CV Pose_Estimation CNN Represenation_Learning Detection
author: Vandad Davoodnia, Saeed Ghorbani, Ali Etemad
mathjax: true
---

* content
{:toc}

##### Abstract
In-bed pose estimation has shown value in fields such as hospital patient monitoring, sleep studies, and smart homes. In this paper, we present a novel in-bed pressure-based pose estimation approach capable of accurately detecting body parts from highly ambiguous pressure data. We exploit the idea of using a learnable pre-processing step, which transforms the vague pressure maps to a representation close to the expected input space of common purpose pose identification modules, which fail if solely used on the pressure data. To this end, a fully convolutional network with multiple scales is used as the learnable pre-processing step to provide the pose-specific characteristics of the pressure maps to the pre-trained pose identification module. A combination of loss functions is used to model the constraints, ensuring that unclear body parts are reconstructed correctly while preventing the pre-processing block from generating arbitrary images. The evaluation results show high visual fidelity in the generated pre-processed images as well as high detection rates in pose estimation. Furthermore, we show that the trained pre-processing block can be effective for pose identification models for which it has not been trained as well.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1908.08919](http://arxiv.org/abs/1908.08919)

##### PDF
[http://arxiv.org/pdf/1908.08919](http://arxiv.org/pdf/1908.08919)


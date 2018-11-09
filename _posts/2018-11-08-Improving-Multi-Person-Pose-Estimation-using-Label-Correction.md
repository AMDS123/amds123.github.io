---
layout: post
title: "Improving Multi-Person Pose Estimation using Label Correction"
date: 2018-11-08 09:38:38
categories: arXiv_CV
tags: arXiv_CV Attention Pose_Estimation CNN Prediction
author: Naoki Kato, Tianqi Li, Kohei Nishino, Yusuke Uchida
mathjax: true
---

* content
{:toc}

##### Abstract
Significant attention is being paid to multi-person pose estimation methods recently, as there has been rapid progress in the field owing to convolutional neural networks. Especially, recent method which exploits part confidence maps and Part Affinity Fields (PAFs) has achieved accurate real-time prediction of multi-person keypoints. However, human annotated labels are sometimes inappropriate for learning models. For example, if there is a limb that extends outside an image, a keypoint for the limb may not have annotations because it exists outside of the image, and thus the labels for the limb can not be generated. If a model is trained with data including such missing labels, the output of the model for the location, even though it is correct, is penalized as a false positive, which is likely to cause negative effects on the performance of the model. In this paper, we point out the existence of some patterns of inappropriate labels, and propose a novel method for correcting such labels with a teacher model trained on such incomplete data. Experiments on the COCO dataset show that training with the corrected labels improves the performance of the model and also speeds up training.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1811.03331](http://arxiv.org/abs/1811.03331)

##### PDF
[http://arxiv.org/pdf/1811.03331](http://arxiv.org/pdf/1811.03331)


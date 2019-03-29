---
layout: post
title: "High Fidelity Face Manipulation with Extreme Pose and Expression"
date: 2019-03-28 14:25:04
categories: arXiv_CV
tags: arXiv_CV Adversarial GAN Face Prediction Quantitative Recognition Face_Recognition
author: Chaoyou Fu, Yibo Hu, Xiang Wu, Guoli Wang, Qian Zhang, Ran He
mathjax: true
---

* content
{:toc}

##### Abstract
Face manipulation has shown remarkable advances with the flourish of Generative Adversarial Networks. However, due to the difficulties of controlling the structure and texture in high-resolution, it is challenging to simultaneously model pose and expression during manipulation. In this paper, we propose a novel framework that simplifies face manipulation with extreme pose and expression into two correlated stages: a boundary prediction stage and a disentangled face synthesis stage. In the first stage, we propose to use a boundary image for joint pose and expression modeling. An encoder-decoder network is employed to predict the boundary image of the target face in a semi-supervised way. Pose and expression estimators are used to improve the prediction accuracy. In the second stage, the predicted boundary image and the original face are encoded into the structure and texture latent space by two encoder networks respectively. A proxy network and a feature threshold loss are further imposed as constraints to disentangle the latent space. In addition, we build up a new high quality Multi-View Face (MVF-HQ) database that contains 120K high-resolution face images of 479 identities with pose and expression variations, which will be released soon. Qualitative and quantitative experiments on four databases show that our method pushes forward the advance of extreme face manipulation from 128 $\times$ 128 resolution to 1024 $\times$ 1024 resolution, and significantly improves the face recognition performance under large poses.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1903.12003](http://arxiv.org/abs/1903.12003)

##### PDF
[http://arxiv.org/pdf/1903.12003](http://arxiv.org/pdf/1903.12003)


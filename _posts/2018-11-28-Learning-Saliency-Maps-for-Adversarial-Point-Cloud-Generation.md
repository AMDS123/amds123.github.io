---
layout: post
title: "Learning Saliency Maps for Adversarial Point-Cloud Generation"
date: 2018-11-28 21:50:49
categories: arXiv_AI
tags: arXiv_AI Salient Adversarial Classification Recognition
author: Tianhang Zheng, Changyou Chen, Junsong yuan, Kui Ren
mathjax: true
---

* content
{:toc}

##### Abstract
3D point-cloud recognition with deep neural network (DNN) has received remarkable progress on obtaining both high-accuracy recognition and robustness to random point missing (or dropping). However, the robustness of DNNs to maliciously-manipulated point missing is still unclear. In this paper, we show that point-missing can be a critical security concern by proposing a {\em malicious point-dropping method} to generate adversarial point clouds to fool DNNs. Our method is based on learning a saliency map for a whole point cloud, which assigns each point a score reflecting its contribution to the model-recognition loss, i.e., the difference between the losses with and without the specific point respectively. The saliency map is learnt by approximating the nondifferentiable point-dropping process with a differentiable procedure of shifting points towards the cloud center. In this way, the loss difference, i.e., the saliency score for each point in the map, can be measured by the corresponding gradient of the loss w.r.t the point under the spherical coordinates. Based on the learned saliency map, maliciously point-dropping attack can be achieved by dropping points with the highest scores, leading to significant increase of model loss and thus inferior classification performance. Extensive evaluations on several state-of-the-art point-cloud recognition models, including PointNet, PointNet++ and DGCNN, demonstrate the efficacy and generality of our proposed saliency-map-based point-dropping scheme. Code for experiments is released on \url{https://github.com/tianzheng4/Learning-PointCloud-Saliency-Maps}.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1812.01687](http://arxiv.org/abs/1812.01687)

##### PDF
[http://arxiv.org/pdf/1812.01687](http://arxiv.org/pdf/1812.01687)


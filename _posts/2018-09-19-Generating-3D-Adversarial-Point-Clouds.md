---
layout: post
title: "Generating 3D Adversarial Point Clouds"
date: 2018-09-19 05:01:06
categories: arXiv_CV
tags: arXiv_CV Adversarial Prediction
author: Chong Xiang (1), Charles R. Qi (2), Bo Li (3) ((1) Shanghai Jiao Tong Univerisity, (2) Stanford University, (3) University of Illinois at Urbana-Champaign)
mathjax: true
---

* content
{:toc}

##### Abstract
Machine learning models especially deep neural networks (DNNs) have been successfully applied to a variety of applications. However, DNNs are known to be vulnerable to adversarial examples which are carefully crafted instances aiming to cause learning models to make incorrect predictions. Recently, adversarial examples have been extensively studied for 2D image, natural language and audio datasets, while the robustness of 3D models has not yet been explored. Given the wide safety-critical applications of 3D models, such as PointNet for Lidar data in autonomous driving, it is important to understand the vulnerability of 3D models under various adversarial attacks. Due to the special format of point cloud data, it is challenging to generate adversarial examples in the point cloud space. In this work, we propose novel algorithms to generate adversarial point clouds against PointNet, which is the most widely used model dealing with point cloud data. We mainly propose two types of attacks on point clouds: unnoticeable adversarial point clouds, and manufacturable adversarial point clusters for physical attacks. For unnoticeable point clouds, we propose to either shift existing or add new points negligibly to craft "unnoticeable" perturbation. For adversarial point clusters, we propose to generate a small number of explicit "manufacturable adversarial point clusters" which are noticeable but of meaningful clusters. The goal of these adversarial point clusters is to realize "physical attacks" by 3D printing the synthesized objects and sticking them to the original object. In addition, we propose 7 perturbation measurement metrics tailored to different attacks and conduct extensive experiments to evaluate the proposed algorithms on the ModelNet40 dataset. Overall, our attack algorithms achieve about 100% attack success rate for all targeted attacks.

##### Abstract (translated by Google)
机器学习模型尤其是深度神经网络（DNN）已成功应用于各种应用。然而，众所周知，DNN容易受到对抗性例子的攻击，这些例子是精心设计的实例，旨在使学习模型做出错误的预测。最近，对于2D图像，自然语言和音频数据集已经广泛研究了对抗性示例，而3D模型的稳健性尚未被探索。鉴于3D模型的广泛安全关键应用，例如PointNet用于自动驾驶中的激光雷达数据，了解3D模型在各种对抗性攻击下的脆弱性非常重要。由于点云数据的特殊格式，在点云空间中生成对抗性示例具有挑战性。在这项工作中，我们提出了新的算法，以针对PointNet生成对抗点云，PointNet是处理点云数据的最广泛使用的模型。我们主要针对点云提出两种类型的攻击：不明显的对抗点云，以及用于物理攻击的可制造的对抗点集群。对于不明显的点云，我们建议转移现有或添加新点，可以忽略不计地制造“不明显的”扰动。对于对抗点集群，我们建议生成少量明确的“可制造的对抗点集群”，这些集群是明显但有意义的集群。这些对抗点集群的目标是通过3D打印合成对象并将它们粘贴到原始对象来实现“物理攻击”。此外，我们提出针对不同攻击量身定制的7个扰动测量指标，并进行大量实验以评估ModelNet40数据集上的算法。总的来说，我们的攻击算法可以为所有目标攻击实现大约100％的攻击成功率。

##### URL
[http://arxiv.org/abs/1809.07016](http://arxiv.org/abs/1809.07016)

##### PDF
[http://arxiv.org/pdf/1809.07016](http://arxiv.org/pdf/1809.07016)


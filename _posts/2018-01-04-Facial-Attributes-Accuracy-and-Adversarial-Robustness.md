---
layout: post
title: "Facial Attributes: Accuracy and Adversarial Robustness"
date: 2018-01-04 00:53:16
categories: arXiv_CV
tags: arXiv_CV Adversarial Classification Prediction Relation
author: Andras Rozsa, Manuel G&#xfc;nther, Ethan M. Rudd, Terrance E. Boult
mathjax: true
---

* content
{:toc}

##### Abstract
Facial attributes, emerging soft biometrics, must be automatically and reliably extracted from images in order to be usable in stand-alone systems. While recent methods extract facial attributes using deep neural networks (DNNs) trained on labeled facial attribute data, the robustness of deep attribute representations has not been evaluated. In this paper, we examine the representational stability of several approaches that recently advanced the state of the art on the CelebA benchmark by generating adversarial examples formed by adding small, non-random perturbations to inputs yielding altered classifications. We show that our fast flipping attribute (FFA) technique generates more adversarial examples than traditional algorithms, and that the adversarial robustness of DNNs varies highly between facial attributes. We also test the correlation of facial attributes and find that only for related attributes do the formed adversarial perturbations change the classification of others. Finally, we introduce the concept of natural adversarial samples, i.e., misclassified images where predictions can be corrected via small perturbations. We demonstrate that natural adversarial samples commonly occur and show that many of these images remain misclassified even with additional training epochs, even though their correct classification may require only a small adjustment to network parameters.

##### Abstract (translated by Google)
面部属性，新兴的软生物测量学，必须自动和可靠地从图像中提取，以便可以在独立系统中使用。尽管最近的方法使用在标记的面部属性数据上训练的深度神经网络（DNN）来提取面部属性，但是深度属性表示的鲁棒性尚未被评估。在本文中，我们通过产生对立的例子，通过在输入中添加小的非随机扰动，从而产生改变的分类，来检查在CelebA基准中最近推进的技术的几种方法的表示稳定性。我们表明，我们的快速翻转属性（FFA）技术比传统算法产生更多的对抗性的例子，DNN的对抗鲁棒性在面部属性之间变化很大。我们还测试了面部属性的相关性，发现只有相关属性才会形成对抗性的扰动，改变他人的分类。最后，我们介绍自然对抗样本的概念，即错误分类的图像，其中预测可以通过小的扰动来纠正。我们证明，自然敌对样本通常会发生，并表明，即使有更多的训练时期，这些图像中的许多图像仍然被错误分类，尽管它们的正确分类可能只需要对网络参数进行微小的调整。

##### URL
[http://arxiv.org/abs/1801.02480](http://arxiv.org/abs/1801.02480)

##### PDF
[http://arxiv.org/pdf/1801.02480](http://arxiv.org/pdf/1801.02480)


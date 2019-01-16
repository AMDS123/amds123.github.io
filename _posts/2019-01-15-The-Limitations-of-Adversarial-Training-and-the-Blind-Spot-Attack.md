---
layout: post
title: "The Limitations of Adversarial Training and the Blind-Spot Attack"
date: 2019-01-15 07:21:44
categories: arXiv_CV
tags: arXiv_CV Adversarial Relation
author: Huan Zhang, Hongge Chen, Zhao Song, Duane Boning, Inderjit S. Dhillon, Cho-Jui Hsieh
mathjax: true
---

* content
{:toc}

##### Abstract
The adversarial training procedure proposed by Madry et al. (2018) is one of the most effective methods to defend against adversarial examples in deep neural networks (DNNs). In our paper, we shed some lights on the practicality and the hardness of adversarial training by showing that the effectiveness (robustness on test set) of adversarial training has a strong correlation with the distance between a test point and the manifold of training data embedded by the network. Test examples that are relatively far away from this manifold are more likely to be vulnerable to adversarial attacks. Consequentially, an adversarial training based defense is susceptible to a new class of attacks, the "blind-spot attack", where the input images reside in "blind-spots" (low density regions) of the empirical distribution of training data but is still on the ground-truth data manifold. For MNIST, we found that these blind-spots can be easily found by simply scaling and shifting image pixel values. Most importantly, for large datasets with high dimensional and complex data manifold (CIFAR, ImageNet, etc), the existence of blind-spots in adversarial training makes defending on any valid test examples difficult due to the curse of dimensionality and the scarcity of training data. Additionally, we find that blind-spots also exist on provable defenses including (Wong & Kolter, 2018) and (Sinha et al., 2018) because these trainable robustness certificates can only be practically optimized on a limited set of training data.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1901.04684](https://arxiv.org/abs/1901.04684)

##### PDF
[https://arxiv.org/pdf/1901.04684](https://arxiv.org/pdf/1901.04684)


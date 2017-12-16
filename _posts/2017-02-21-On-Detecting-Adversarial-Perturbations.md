---
layout: post
title: "On Detecting Adversarial Perturbations"
date: 2017-02-21 06:53:38
categories: arXiv_CV
tags: arXiv_CV Adversarial Object_Detection Classification Deep_Learning Detection
author: Jan Hendrik Metzen, Tim Genewein, Volker Fischer, Bastian Bischoff
mathjax: true
---

* content
{:toc}

##### Abstract
Machine learning and deep learning in particular has advanced tremendously on perceptual tasks in recent years. However, it remains vulnerable against adversarial perturbations of the input that have been crafted specifically to fool the system while being quasi-imperceptible to a human. In this work, we propose to augment deep neural networks with a small "detector" subnetwork which is trained on the binary classification task of distinguishing genuine data from data containing adversarial perturbations. Our method is orthogonal to prior work on addressing adversarial perturbations, which has mostly focused on making the classification network itself more robust. We show empirically that adversarial perturbations can be detected surprisingly well even though they are quasi-imperceptible to humans. Moreover, while the detectors have been trained to detect only a specific adversary, they generalize to similar and weaker adversaries. In addition, we propose an adversarial attack that fools both the classifier and the detector and a novel training procedure for the detector that counteracts this attack.

##### Abstract (translated by Google)
特别是机器学习和深度学习近年来在​​感性工作方面取得了巨大的进步。然而，它仍然是脆弱的，因为这种投入是专门用来欺骗系统，而对人类来说是不可察觉的。在这项工作中，我们建议用一个小的“检测器”子网络来加深深度神经网络，这个子网络是在二元分类任务上进行训练的，这个分类任务是将真实数据与含有对抗性扰动的数据进行区分。我们的方法正交于解决敌对扰动，其中主要集中在使分类网络本身更强大的工作。我们经验地显示，对抗性扰动可以被​​惊人地发现，即使它们对于人类是不可察觉的。而且，虽然探测器已经被训练成只探测特定的对手，但是它们推广到相似和较弱的对手。另外，我们提出了一种欺骗分类器和检测器的对抗性攻击，以及用于检测器的新型训练过程，以抵消这种攻击。

##### URL
[https://arxiv.org/abs/1702.04267](https://arxiv.org/abs/1702.04267)

##### PDF
[https://arxiv.org/pdf/1702.04267](https://arxiv.org/pdf/1702.04267)


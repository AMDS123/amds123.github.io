---
layout: post
title: "Cloud-based Image Classification Service Is Not Robust To Simple Transformations: A Forgotten Battlefield"
date: 2019-06-19 09:36:17
categories: arXiv_CV
tags: arXiv_CV Adversarial Image_Classification Classification Deep_Learning
author: Dou Goodman, Tao Wei
mathjax: true
---

* content
{:toc}

##### Abstract
Many recent works demonstrated that Deep Learning models are vulnerable to adversarial examples.Fortunately, generating adversarial examples usually requires white-box access to the victim model, and the attacker can only access the APIs opened by cloud platforms. Thus, keeping models in the cloud can usually give a (false) sense of security.Unfortunately, cloud-based image classification service is not robust to simple transformations such as Gaussian Noise, Salt-and-Pepper Noise, Rotation and Monochromatization. In this paper,(1) we propose one novel attack method called Image Fusion(IF) attack, which achieve a high bypass rate,can be implemented only with OpenCV and is difficult to defend; and (2) we make the first attempt to conduct an extensive empirical study of Simple Transformation (ST) attacks against real-world cloud-based classification services. Through evaluations on four popular cloud platforms including Amazon, Google, Microsoft, Clarifai, we demonstrate that ST attack has a success rate of approximately 100% except Amazon approximately 50%, IF attack have a success rate over 98% among different classification services. (3) We discuss the possible defenses to address these security challenges.Experiments show that our defense technology can effectively defend known ST attacks.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1906.07997](http://arxiv.org/abs/1906.07997)

##### PDF
[http://arxiv.org/pdf/1906.07997](http://arxiv.org/pdf/1906.07997)


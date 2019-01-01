---
layout: post
title: "Learning Continuous Face Age Progression: A Pyramid of GANs"
date: 2018-12-29 05:41:36
categories: arXiv_CV
tags: arXiv_CV Adversarial GAN Face Quantitative Recognition Face_Recognition
author: Hongyu Yang, Di Huang, Yunhong Wang, Anil K. Jain
mathjax: true
---

* content
{:toc}

##### Abstract
The two underlying requirements of face age progression, i.e. aging accuracy and identity permanence, are not well studied in the literature. This paper presents a novel generative adversarial network based approach to address the issues in a coupled manner. It separately models the constraints for the intrinsic subject-specific characteristics and the age-specific facial changes with respect to the elapsed time, ensuring that the generated faces present desired aging effects while simultaneously keeping personalized properties stable. To ensure photo-realistic facial details, high-level age-specific features conveyed by the synthesized face are estimated by a pyramidal adversarial discriminator at multiple scales, which simulates the aging effects with finer details. Further, an adversarial learning scheme is introduced to simultaneously train a single generator and multiple parallel discriminators, resulting in smooth continuous face aging sequences. The proposed method is applicable even in the presence of variations in pose, expression, makeup, etc., achieving remarkably vivid aging effects. Quantitative evaluations by a COTS face recognition system demonstrate that the target age distributions are accurately recovered, and 99.88% and 99.98% age progressed faces can be correctly verified at 0.001% FAR after age transformations of approximately 28 and 23 years elapsed time on the MORPH and CACD databases, respectively. Both visual and quantitative assessments show that the approach advances the state-of-the-art.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1711.10352](http://arxiv.org/abs/1711.10352)

##### PDF
[http://arxiv.org/pdf/1711.10352](http://arxiv.org/pdf/1711.10352)


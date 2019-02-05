---
layout: post
title: "The Efficacy of SHIELD under Different Threat Models"
date: 2019-02-01 20:10:12
categories: arXiv_AI
tags: arXiv_AI Adversarial Face Prediction
author: Cory Cornelius
mathjax: true
---

* content
{:toc}

##### Abstract
We study the efficacy of SHIELD in the face of alternative threat models. We find that SHIELD's robustness decreases by 65% (accuracy drops from 63% to 22%) against an adaptive adversary (one who knows JPEG compression is being used as a pre-processing step but not necessarily the compression level) in the gray-box threat model (adversary is aware of the model architecture but not necessarily the weights of that model). However, these adversarial examples are, so far, unable to force a targeted prediction. We also find that the robustness of the JPEG-trained models used in SHIELD decreases by 67% (accuracy drops from 57% to 19% on average) against an adaptive adversary in the gray-box threat model. The addition of SLQ pre-processing to these JPEG-trained models is also not a robust defense (accuracy drops to 0.1%) against an adaptive adversary in the gray-box threat model, and an adversary can create adversarial perturbations that force a chosen prediction. We find that neither JPEG-trained models with SLQ pre-processing nor SHIELD are robust against an adaptive adversary in the white-box threat model (accuracy is 0.1%) and the adversary can control the predicted output of their adversarial images. Finally, ensemble-based attacks transfer better (29.8% targeted accuracy) than non-ensemble based attacks (1.4%) against the JPEG-trained models in SHIELD.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1902.00541](http://arxiv.org/abs/1902.00541)

##### PDF
[http://arxiv.org/pdf/1902.00541](http://arxiv.org/pdf/1902.00541)


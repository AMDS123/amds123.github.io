---
layout: post
title: "On the Effectiveness of Low Frequency Perturbations"
date: 2019-02-28 21:25:45
categories: arXiv_CV
tags: arXiv_CV Adversarial Optimization
author: Yash Sharma, Gavin Weiguang Ding, Marcus Brubaker
mathjax: true
---

* content
{:toc}

##### Abstract
Carefully crafted, often imperceptible, adversarial perturbations have been shown to cause state-of-the-art models to yield extremely inaccurate outputs, rendering them unsuitable for safety-critical application domains. In addition, recent work has shown that constraining the attack space to a low frequency regime is particularly effective. Yet, it remains unclear whether this is due to generally constraining the attack search space or specifically removing high frequency components from consideration. By systematically controlling the frequency components of the perturbation, evaluating against the top-placing defense submissions in the NeurIPS 2017 competition, we empirically show that performance improvements in both optimization and generalization are yielded only when low frequency components are preserved. In fact, the defended models based on (ensemble) adversarial training are roughly as vulnerable to low frequency perturbations as undefended models, suggesting that the purported robustness of proposed defenses is reliant upon adversarial perturbations being high frequency in nature. We do find that under $\ell_\infty$ $\epsilon=16/255$, a commonly used distortion bound, low frequency perturbations are indeed perceptible. This questions the use of the $\ell_\infty$-norm, in particular, as a distortion metric, and suggests that explicitly considering the frequency space is promising for learning robust models which better align with human perception.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1903.00073](http://arxiv.org/abs/1903.00073)

##### PDF
[http://arxiv.org/pdf/1903.00073](http://arxiv.org/pdf/1903.00073)


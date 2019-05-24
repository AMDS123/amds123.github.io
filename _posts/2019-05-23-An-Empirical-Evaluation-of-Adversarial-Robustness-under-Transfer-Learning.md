---
layout: post
title: "An Empirical Evaluation of Adversarial Robustness under Transfer Learning"
date: 2019-05-23 09:37:44
categories: arXiv_CV
tags: arXiv_CV Adversarial Transfer_Learning
author: Todor Davchev, Timos Korres, Stathi Fotiadis, Nick Antonopoulos, Subramanian Ramamoorthy
mathjax: true
---

* content
{:toc}

##### Abstract
In this work, we evaluate adversarial robustness in the context of transfer learning from a source trained on CIFAR 100 to a target network trained on CIFAR 10. Specifically, we study the effects of using robust optimisation in the source and target networks. This allows us to identify transfer learning strategies under which adversarial defences are successfully retained, in addition to revealing potential vulnerabilities. We study the extent to which features learnt by a fast gradient sign method (FGSM) and its iterative alternative (PGD) can preserve their defence properties against black and white-box attacks under three different transfer learning strategies. We find that using PGD examples during training on the source task leads to more general robust features that are easier to transfer. Furthermore, under successful transfer, it achieves 5.2% more accuracy against white-box PGD attacks than suitable baselines. Overall, our empirical evaluations give insights on how well adversarial robustness under transfer learning can generalise.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1905.02675](http://arxiv.org/abs/1905.02675)

##### PDF
[http://arxiv.org/pdf/1905.02675](http://arxiv.org/pdf/1905.02675)


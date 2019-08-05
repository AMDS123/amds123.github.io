---
layout: post
title: "Robustifying deep networks for image segmentation"
date: 2019-08-01 23:05:19
categories: arXiv_CV
tags: arXiv_CV Adversarial Segmentation CNN Deep_Learning
author: Zheng Liu, Jinnian Zhang, Varun Jog, Po-Ling Loh, Alan B McMillan
mathjax: true
---

* content
{:toc}

##### Abstract
Purpose: The purpose of this study is to investigate the robustness of a commonly-used convolutional neural network for image segmentation with respect to visually-subtle adversarial perturbations, and suggest new methods to make these networks more robust to such perturbations. Materials and Methods: In this retrospective study, the accuracy of brain tumor segmentation was studied in subjects with low- and high-grade gliomas. A three-dimensional UNet model was implemented to segment four different MR series (T1-weighted, post-contrast T1-weighted, T2- weighted, and T2-weighted FLAIR) into four pixelwise labels (Gd-enhancing tumor, peritumoral edema, necrotic and non-enhancing tumor, and background). We developed attack strategies based on the Fast Gradient Sign Method (FGSM), iterative FGSM (i-FGSM), and targeted iterative FGSM (ti-FGSM) to produce effective attacks. Additionally, we explored the effectiveness of distillation and adversarial training via data augmentation to counteract adversarial attacks. Robustness was measured by comparing the Dice coefficient for each attack method using Wilcoxon signed-rank tests. Results: Attacks based on FGSM, i-FGSM, and ti-FGSM were effective in significantly reducing the quality of image segmentation with reductions in Dice coefficient by up to 65%. For attack defenses, distillation performed significantly better than adversarial training approaches. However, all defense approaches performed worse compared to unperturbed test images. Conclusion: Segmentation networks can be adversely affected by targeted attacks that introduce visually minor (and potentially undetectable) modifications to existing images. With an increasing interest in applying deep learning techniques to medical imaging data, it is important to quantify the ramifications of adversarial inputs (either intentional or unintentional).

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1908.00656](http://arxiv.org/abs/1908.00656)

##### PDF
[http://arxiv.org/pdf/1908.00656](http://arxiv.org/pdf/1908.00656)


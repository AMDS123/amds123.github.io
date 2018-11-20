---
layout: post
title: "Injecting and removing malignant features in mammography with CycleGAN: Investigation of an automated adversarial attack using neural networks"
date: 2018-11-19 16:08:11
categories: arXiv_CV
tags: arXiv_CV Adversarial GAN Detection
author: Anton S. Becker, Lukas Jendele, Ondrej Skopek, Nicole Berger, Soleen Ghafoor, Magda Marcon, Ender Konukoglu
mathjax: true
---

* content
{:toc}

##### Abstract
$\textbf{Purpose}$ To train a cycle-consistent generative adversarial network (CycleGAN) on mammographic data to inject or remove features of malignancy, and to determine whether these AI-mediated attacks can be detected by radiologists. $\textbf{Material and Methods}$ From the two publicly available datasets, BCDR and INbreast, we selected images from cancer patients and healthy controls. An internal dataset served as test data, withheld during training. We ran two experiments training CycleGAN on low and higher resolution images ($256 \times 256$ px and $512 \times 408$ px). Three radiologists read the images and rated the likelihood of malignancy on a scale from 1-5 and the likelihood of the image being manipulated. The readout was evaluated by ROC analysis (Area under the ROC curve = AUC). $\textbf{Results}$ At the lower resolution, only one radiologist exhibited markedly lower detection of cancer (AUC=0.85 vs 0.63, p=0.06), while the other two were unaffected (0.67 vs. 0.69 and 0.75 vs. 0.77, p=0.55). Only one radiologist could discriminate between original and modified images slightly better than guessing/chance (0.66, p=0.008). At the higher resolution, all radiologists showed significantly lower detection rate of cancer in the modified images (0.77-0.84 vs. 0.59-0.69, p=0.008), however, they were now able to reliably detect modified images due to better visibility of artifacts (0.92, 0.92 and 0.97). $\textbf{Conclusion}$ A CycleGAN can implicitly learn malignant features and inject or remove them so that a substantial proportion of small mammographic images would consequently be misdiagnosed. At higher resolutions, however, the method is currently limited and has a clear trade-off between manipulation of images and introduction of artifacts.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1811.07767](http://arxiv.org/abs/1811.07767)

##### PDF
[http://arxiv.org/pdf/1811.07767](http://arxiv.org/pdf/1811.07767)


---
layout: post
title: "FusionNet: Incorporating Shape and Texture for Abnormality Detection in 3D Abdominal CT Scans"
date: 2019-08-21 00:11:36
categories: arXiv_CV
tags: arXiv_CV Classification Detection
author: Fengze Liu, Yuyin Zhou, Elliot Fishman, Alan Yuille
mathjax: true
---

* content
{:toc}

##### Abstract
Automatic abnormality detection in abdominal CT scans can help doctors improve the accuracy and efficiency in diagnosis. In this paper we aim at detecting pancreatic ductal adenocarcinoma (PDAC), the most common pancreatic cancer. Taking the fact that the existence of tumor can affect both the shape and the texture of pancreas, we design a system to extract the shape and texture feature at the same time for detecting PDAC. In this paper we propose a two-stage method for this 3D classification task. First, we segment the pancreas into a binary mask. Second, a FusionNet is proposed to take both the binary mask and CT image as input and perform a binary classification. The optimal architecture of the FusionNet is obtained by searching a pre-defined functional space. We show that the classification results using either shape or texture information are complementary, and by fusing them with the optimized architecture, the performance improves by a large margin. Our method achieves a specificity of 97% and a sensitivity of 92% on 200 normal scans and 136 scans with PDAC.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1908.07654](http://arxiv.org/abs/1908.07654)

##### PDF
[http://arxiv.org/pdf/1908.07654](http://arxiv.org/pdf/1908.07654)


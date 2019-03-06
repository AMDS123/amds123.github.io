---
layout: post
title: "Hue Modification Localization By Pair Matching"
date: 2019-03-05 09:08:21
categories: arXiv_CV
tags: arXiv_CV
author: Quoc-Tin Phan, Michele Vascotto, Giulia Boato
mathjax: true
---

* content
{:toc}

##### Abstract
Hue modification is the adjustment of hue property on color images. Conducting hue modification on an image is trivial, and it can be abused to falsify opinions of viewers. Since shapes, edges or textural information remains unchanged after hue modification, this type of manipulation is relatively hard to be detected and localized. Since small patches inherit the same Color Filter Array (CFA) configuration and demosaicing, any distortion made by local hue modification can be detected by patch matching within the same image. In this paper, we propose to localize hue modification by means of a Siamese neural network specifically designed for matching two inputs. By crafting the network outputs, we are able to form a heatmap which potentially highlights malicious regions. Our proposed method deals well not only with uncompressed images but also with the presence of JPEG compression, an operation usually hindering the exploitation of CFA and demosaicing artifacts. Experimental evidences corroborate the effectiveness of the proposed method.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1903.01735](https://arxiv.org/abs/1903.01735)

##### PDF
[https://arxiv.org/pdf/1903.01735](https://arxiv.org/pdf/1903.01735)


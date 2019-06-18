---
layout: post
title: "STAR: A Structure and Texture Aware Retinex Model"
date: 2019-06-16 13:58:52
categories: arXiv_CV
tags: arXiv_CV Image_Enhancement Quantitative
author: Jun Xu, Mengyang Yu, Li Liu, Fan Zhu, Dongwei Ren, Yingkun Hou, Haoqian Wang, Ling Shao
mathjax: true
---

* content
{:toc}

##### Abstract
Retinex theory is developed mainly to decompose an image into the illumination and reflectance components by analyzing local image derivatives. In this theory, larger derivatives are attributed to the changes in piece-wise constant reflectance, while smaller derivatives are emerged in the smooth illumination. In this paper, we propose to utilize the exponentiated derivatives (with an exponent $\gamma$) of an observed image to generate a structure map when being amplified with $\gamma&gt;1$ and a texture map when being shrank with $\gamma&lt;1$. To this end, we design exponential filters for the local derivatives, and present their capability on extracting accurate structure and texture maps, influenced by the choices of exponents $\gamma$ on the local derivatives. The extracted structure and texture maps are employed to regularize the illumination and reflectance components in Retinex decomposition. A novel Structure and Texture Aware Retinex (STAR) model is further proposed for illumination and reflectance decomposition of a single image. We solve the STAR model in an alternating minimization manner. Each sub-problem is transformed into a vectorized least squares regression with closed-form solution. Comprehensive experiments demonstrate that, the proposed STAR model produce better quantitative and qualitative performance than previous competing methods, on illumination and reflectance estimation, low-light image enhancement, and color correction. The code will be publicly released.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1906.06690](http://arxiv.org/abs/1906.06690)

##### PDF
[http://arxiv.org/pdf/1906.06690](http://arxiv.org/pdf/1906.06690)


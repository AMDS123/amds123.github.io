---
layout: post
title: "Underwater Single Image Color Restoration Using Haze-Lines and a New Quantitative Dataset"
date: 2018-11-04 09:16:38
categories: arXiv_CV
tags: arXiv_CV Image_Enhancement Quantitative
author: Dana Berman, Deborah Levy, Shai Avidan, Tali Treibitz
mathjax: true
---

* content
{:toc}

##### Abstract
Underwater images suffer from color distortion and low contrast, because light is attenuated while it propagates through water. Attenuation under water varies with wavelength, unlike terrestrial images where attenuation is assumed to be spectrally uniform. The attenuation depends both on the water body and the 3D structure of the scene, making color restoration difficult. 
 Unlike existing single underwater image enhancement techniques, our method takes into account multiple spectral profiles of different water types. By estimating just two additional global parameters: the attenuation ratios of the blue-red and blue-green color channels, the problem is reduced to single image dehazing, where all color channels have the same attenuation coefficients. Since the water type is unknown, we evaluate different parameters out of an existing library of water types. Each type leads to a different restored image and the best result is automatically chosen based on color distribution. 
 We collected a dataset of images taken in different locations with varying water properties, showing color charts in the scenes. Moreover, to obtain ground truth, the 3D structure of the scene was calculated based on stereo imaging. This dataset enables a quantitative evaluation of restoration algorithms on natural images and shows the advantage of our method.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1811.01343](http://arxiv.org/abs/1811.01343)

##### PDF
[http://arxiv.org/pdf/1811.01343](http://arxiv.org/pdf/1811.01343)


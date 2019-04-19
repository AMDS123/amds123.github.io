---
layout: post
title: "Machine Vision for Natural Gas Methane Emissions Detection Using an Infrared Camera"
date: 2019-04-01 05:38:59
categories: arXiv_CV
tags: arXiv_CV Survey CNN Detection
author: Jingfan Wang, Lyne P. Tchapmi, Arvind P. Ravikumara, Mike McGuire, Clay S. Bell, Daniel Zimmerle, Silvio Savarese, Adam R. Brandt
mathjax: true
---

* content
{:toc}

##### Abstract
It is crucial to reduce natural gas methane emissions, which can potentially offset the climate benefits of replacing coal with gas. Optical gas imaging (OGI) is a widely-used method to detect methane leaks, but is labor-intensive and cannot provide leak detection results without operators' judgment. In this paper, we develop a computer vision approach to OGI-based leak detection using convolutional neural networks (CNN) trained on methane leak images to enable automatic detection. First, we collect ~1 M frames of labeled video of methane leaks from different leaking equipment for building CNN model, covering a wide range of leak sizes (5.3-2051.6 gCH4/h) and imaging distances (4.6-15.6 m). Second, we examine different background subtraction methods to extract the methane plume in the foreground. Third, we then test three CNN model variants, collectively called GasNet, to detect plumes in videos taken at other pieces of leaking equipment. We assess the ability of GasNet to perform leak detection by comparing it to a baseline method that uses optical-flow based change detection algorithm. We explore the sensitivity of results to the CNN structure, with a moderate-complexity variant performing best across distances. We find that the detection accuracy can reach as high as 99%, the overall detection accuracy can exceed 95% for a case across all leak sizes and imaging distances. Binary detection accuracy exceeds 97% for large leaks (~710 gCH4/h) imaged closely (~5-7 m). At closer imaging distances (~5-10 m), CNN-based models have greater than 94% accuracy across all leak sizes. At farthest distances (~13-16 m), performance degrades rapidly, but it can achieve above 95% accuracy to detect large leaks (&gt;950 gCH4/h). The GasNet-based computer vision approach could be deployed in OGI surveys to allow automatic vigilance of methane leak detection with high detection accuracy in the real world.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1904.08500](http://arxiv.org/abs/1904.08500)

##### PDF
[http://arxiv.org/pdf/1904.08500](http://arxiv.org/pdf/1904.08500)


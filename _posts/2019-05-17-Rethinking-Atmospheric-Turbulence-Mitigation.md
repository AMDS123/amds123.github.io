---
layout: post
title: "Rethinking Atmospheric Turbulence Mitigation"
date: 2019-05-17 22:59:11
categories: arXiv_CV
tags: arXiv_CV
author: Nicholas Chimitt, Zhiyuan Mao, Guanzhe Hong, Stanley H. Chan
mathjax: true
---

* content
{:toc}

##### Abstract
State-of-the-art atmospheric turbulence image restoration methods utilize standard image processing tools such as optical flow, lucky region and blind deconvolution to restore the images. While promising results have been reported over the past decade, many of the methods are agnostic to the physical model that generates the distortion. In this paper, we revisit the turbulence restoration problem by analyzing the reference frame generation and the blind deconvolution steps in a typical restoration pipeline. By leveraging tools in large deviation theory, we rigorously prove the minimum number of frames required to generate a reliable reference for both static and dynamic scenes. We discuss how a turbulence agnostic model can lead to potential flaws, and how to configure a simple spatial-temporal non-local weighted averaging method to generate references. For blind deconvolution, we present a new data-driven prior by analyzing the distributions of the point spread functions. We demonstrate how a simple prior can outperform state-of-the-art blind deconvolution methods.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1905.07498](http://arxiv.org/abs/1905.07498)

##### PDF
[http://arxiv.org/pdf/1905.07498](http://arxiv.org/pdf/1905.07498)


---
layout: post
title: "Multichannel Semantic Segmentation with Unsupervised Domain Adaptation"
date: 2018-12-11 12:26:38
categories: arXiv_CV
tags: arXiv_CV Segmentation Semantic_Segmentation
author: Kohei Watanabe, Kuniaki Saito, Yoshitaka Ushiku, Tatsuya Harada
mathjax: true
---

* content
{:toc}

##### Abstract
Most contemporary robots have depth sensors, and research on semantic segmentation with RGBD images has shown that depth images boost the accuracy of segmentation. Since it is time-consuming to annotate images with semantic labels per pixel, it would be ideal if we could avoid this laborious work by utilizing an existing dataset or a synthetic dataset which we can generate on our own. Robot motions are often tested in a synthetic environment, where multichannel (eg, RGB + depth + instance boundary) images plus their pixel-level semantic labels are available. However, models trained simply on synthetic images tend to demonstrate poor performance on real images. In order to address this, we propose two approaches that can efficiently exploit multichannel inputs combined with an unsupervised domain adaptation (UDA) algorithm. One is a fusion-based approach that uses depth images as inputs. The other is a multitask learning approach that uses depth images as outputs. We demonstrated that the segmentation results were improved by using a multitask learning approach with a post-process and created a benchmark for this task.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1812.04351](http://arxiv.org/abs/1812.04351)

##### PDF
[http://arxiv.org/pdf/1812.04351](http://arxiv.org/pdf/1812.04351)


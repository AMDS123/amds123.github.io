---
layout: post
title: "Single Pixel Reconstruction for One-stage Instance Segmentation"
date: 2019-04-16 03:11:13
categories: arXiv_CV
tags: arXiv_CV Image_Caption Object_Detection Segmentation Inference Prediction Detection
author: Jinghan Yao, Zhou Yu, Jun Yu, Dacheng Tao
mathjax: true
---

* content
{:toc}

##### Abstract
Object instance segmentation is one of the most fundamental but challenging tasks in computer vision, and it requires the pixel-level image understanding. Most existing approaches address this problem by adding a mask prediction branch to a two-stage object detector with the Region Proposal Network (RPN). Although producing good segmentation results, the efficiency of these two-stage approaches is far from satisfactory, restricting their applicability in practice. In this paper, we propose a one-stage framework, SPRNet, which performs efficient instance segmentation by introducing a single pixel reconstruction (SPR) branch to off-the-shelf one-stage detectors. The added SPR branch reconstructs the pixel-level mask from every single pixel in the convolution feature map directly. Using the same ResNet-50 backbone, SPRNet achieves comparable mask AP to Mask R-CNN at a higher inference speed, and gains all-round improvements on box AP at every scale comparing to RetinaNet.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1904.07426](http://arxiv.org/abs/1904.07426)

##### PDF
[http://arxiv.org/pdf/1904.07426](http://arxiv.org/pdf/1904.07426)


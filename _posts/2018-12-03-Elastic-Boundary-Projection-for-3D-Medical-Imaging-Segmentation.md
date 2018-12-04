---
layout: post
title: "Elastic Boundary Projection for 3D Medical Imaging Segmentation"
date: 2018-12-03 02:05:57
categories: arXiv_CV
tags: arXiv_CV Segmentation GAN Face
author: Tianwei Ni, Lingxi Xie, Huangjie Zheng, Elliot K. Fishman, Alan L. Yuille
mathjax: true
---

* content
{:toc}

##### Abstract
We focus on an important yet challenging problem: using a 2D deep network to deal with 3D segmentation for medical imaging analysis. Existing approaches either applied multi-view planar (2D) networks or directly used volumetric (3D) networks for this purpose, but both of them are not ideal: 2D networks cannot capture 3D contexts effectively, and 3D networks are both memory-consuming and less stable arguably due to the lack of pre-trained models. 
 In this paper, we bridge the gap between 2D and 3D using a novel approach named Elastic Boundary Projection (EBP). The key observation is that, although the object is a 3D volume, what we really need in segmentation is to find its boundary which is a 2D surface. Therefore, we place a number of pivot points in the 3D space, and for each pivot, we determine its distance to the object boundary along a dense set of directions. This creates an elastic shell around each pivot which is initialized as a perfect sphere. We train a 2D deep network to determine whether each ending point falls within the object, and gradually adjust the shell so that it gradually converges to the actual shape of the boundary and thus achieves the goal of segmentation. EBP allows 3D segmentation without cutting the volume into slices or small patches, which stands out from conventional 2D and 3D approaches. EBP achieves promising accuracy in segmenting several abdominal organs from CT scans.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1812.00518](http://arxiv.org/abs/1812.00518)

##### PDF
[http://arxiv.org/pdf/1812.00518](http://arxiv.org/pdf/1812.00518)


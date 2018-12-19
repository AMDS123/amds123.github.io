---
layout: post
title: "3D-SIS: 3D Semantic Instance Segmentation of RGB-D Scans"
date: 2018-12-17 19:04:31
categories: arXiv_CV
tags: arXiv_CV Semantic_Instance_Segmentation Object_Detection Segmentation Prediction Detection
author: Ji Hou, Angela Dai, Matthias Nie&#xdf;ner
mathjax: true
---

* content
{:toc}

##### Abstract
We introduce 3D-SIS, a novel neural network architecture for 3D semantic instance segmentation in commodity RGB-D scans. The core idea of our method is to jointly learn from both geometric and color signal, thus enabling accurate instance predictions. Rather than operate solely on 2D frames, we observe that most computer vision applications have multi-view RGB-D input available, which we leverage to construct an approach for 3D instance segmentation that effectively fuses together these multi-modal inputs. Our network leverages high-resolution RGB input by associating 2D images with the volumetric grid based on the pose alignment of the 3D reconstruction. For each image, we first extract 2D features for each pixel with a series of 2D convolutions; we then backproject the resulting feature vector to the associated voxel in the 3D grid. This combination of 2D and 3D feature learning allows significantly higher accuracy object detection and instance segmentation than state-of-the-art alternatives. We show results on both synthetic and real-world public benchmarks, achieving an improvement in mAP of over 13 on real-world data.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1812.07003](http://arxiv.org/abs/1812.07003)

##### PDF
[http://arxiv.org/pdf/1812.07003](http://arxiv.org/pdf/1812.07003)


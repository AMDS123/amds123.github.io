---
layout: post
title: "Multimodal 3D Object Detection from Simulated Pretraining"
date: 2019-05-19 15:13:41
categories: arXiv_CV
tags: arXiv_CV Object_Detection Detection
author: &#xc5;smund Brekke, Fredrik Vatsendvik, Frank Lindseth
mathjax: true
---

* content
{:toc}

##### Abstract
The need for simulated data in autonomous driving applications has become increasingly important, both for validation of pretrained models and for training new models. In order for these models to generalize to real-world applications, it is critical that the underlying dataset contains a variety of driving scenarios and that simulated sensor readings closely mimics real-world sensors. We present the Carla Automated Dataset Extraction Tool (CADET), a novel tool for generating training data from the CARLA simulator to be used in autonomous driving research. The tool is able to export high-quality, synchronized LIDAR and camera data with object annotations, and offers configuration to accurately reflect a real-life sensor array. Furthermore, we use this tool to generate a dataset consisting of 10 000 samples and use this dataset in order to train the 3D object detection network AVOD-FPN, with finetuning on the KITTI dataset in order to evaluate the potential for effective pretraining. We also present two novel LIDAR feature map configurations in Bird's Eye View for use with AVOD-FPN that can be easily modified. These configurations are tested on the KITTI and CADET datasets in order to evaluate their performance as well as the usability of the simulated dataset for pretraining. Although insufficient to fully replace the use of real world data, and generally not able to exceed the performance of systems fully trained on real data, our results indicate that simulated data can considerably reduce the amount of training on real data required to achieve satisfactory levels of accuracy.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1905.07754](http://arxiv.org/abs/1905.07754)

##### PDF
[http://arxiv.org/pdf/1905.07754](http://arxiv.org/pdf/1905.07754)


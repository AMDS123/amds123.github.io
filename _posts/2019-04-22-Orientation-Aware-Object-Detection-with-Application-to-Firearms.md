---
layout: post
title: "Orientation Aware Object Detection with Application to Firearms"
date: 2019-04-22 18:56:43
categories: arXiv_CV
tags: arXiv_CV Object_Detection Detection
author: Javed Iqbal, Muhammad Akhtar Munir, Arif Mahmood, Afsheen Rafaqat Ali, Mohsen Ali
mathjax: true
---

* content
{:toc}

##### Abstract
Automatic detection of firearms is important for enhancing security and safety of people, however, it is a challenging task owing to the wide variations in shape, size and appearance of firearms. To handle these challenges we propose an Orientation Aware Object Detector (OAOD) which has achieved improved firearm detection and localization performance. The proposed detector has two phases. In the Phase-1 it predicts orientation of the object which is used to rotate the object proposal. Maximum area rectangles are cropped from the rotated object proposals which are again classified and localized in the Phase-2 of the algorithm. The oriented object proposals are mapped back to the original coordinates resulting in oriented bounding boxes which localize the weapons much better than the axis aligned bounding boxes. Being orientation aware, our non-maximum suppression is able to avoid multiple detection of the same object and it can better resolve objects which lie in close proximity to each other. This two phase system leverages OAOD to predict object oriented bounding boxes while being trained only on the axis aligned boxes in the ground-truth. In order to train object detectors for firearm detection, a dataset consisting of around eleven thousand firearm images is collected from the internet and manually annotated. The proposed ITU Firearm (ITUF) dataset contains wide range of guns and rifles. The OAOD algorithm is evaluated on the ITUF dataset and compared with current state of the art object detectors. Our experiments demonstrate the excellent performance of the proposed detector for the task of firearm detection.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1904.10032](http://arxiv.org/abs/1904.10032)

##### PDF
[http://arxiv.org/pdf/1904.10032](http://arxiv.org/pdf/1904.10032)


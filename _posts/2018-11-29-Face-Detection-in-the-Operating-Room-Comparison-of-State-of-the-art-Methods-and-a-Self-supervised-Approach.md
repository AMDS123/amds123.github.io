---
layout: post
title: "Face Detection in the Operating Room: Comparison of State-of-the-art Methods and a Self-supervised Approach"
date: 2018-11-29 16:38:16
categories: arXiv_CV
tags: arXiv_CV Object_Detection Face Detection Face_Detection
author: Thibaut Issenhuth, Vinkle Srivastav, Afshin Gangi, Nicolas Padoy
mathjax: true
---

* content
{:toc}

##### Abstract
Purpose: Face detection is a needed component for the automatic analysis and assistance of human activities during surgical procedures. Efficient face detection algorithms can indeed help to detect and identify the persons present in the room, and also be used to automatically anonymize the data. However, current algorithms trained on natural images do not generalize well to the operating room (OR) images. In this work, we provide a comparison of state-of-the-art face detectors on OR data and also present an approach to train a face detector for the OR by exploiting non-annotated OR images. Methods: We propose a comparison of 6 state-of-the-art face detectors on clinical data using Multi-View Operating Room Faces (MVOR-Faces), a dataset of operating room images capturing real surgical activities. We then propose to use self-supervision, a domain adaptation method, for the task of face detection in the OR. The approach makes use of non-annotated images to fine-tune a state-of-the-art detector for the OR without using any human supervision. Results: The results show that the best model, namely the tiny face detector, yields an average precision of 0.536 at Intersection over Union (IoU) of 0.5. Our self-supervised model using non-annotated clinical data outperforms this result by 9.2%. Conclusion: We present the first comparison of state-of-the-art face detectors on operating room images and show that results can be significantly improved by using self-supervision on non-annotated data.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1811.12296](http://arxiv.org/abs/1811.12296)

##### PDF
[http://arxiv.org/pdf/1811.12296](http://arxiv.org/pdf/1811.12296)


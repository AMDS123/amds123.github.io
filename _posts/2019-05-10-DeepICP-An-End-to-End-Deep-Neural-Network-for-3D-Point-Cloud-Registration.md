---
layout: post
title: "DeepICP: An End-to-End Deep Neural Network for 3D Point Cloud Registration"
date: 2019-05-10 13:08:28
categories: arXiv_CV
tags: arXiv_CV Salient Object_Detection Inference Detection
author: Weixin Lu, Guowei Wan, Yao Zhou, Xiangyu Fu, Pengfei Yuan, Shiyu Song
mathjax: true
---

* content
{:toc}

##### Abstract
We present DeepICP - a novel end-to-end learning-based 3D point cloud registration framework that achieves comparable registration accuracy to prior state-of-the-art geometric methods. Different from other keypoint based methods where a RANSAC procedure is usually needed, we implement the use of various deep neural network structures to establish an end-to-end trainable network. Our keypoint detector is trained through this end-to-end structure and enables the system to avoid the inference of dynamic objects, leverages the help of sufficiently salient features on stationary objects, and as a result, achieves high robustness. Rather than searching the corresponding points among existing points, the key contribution is that we innovatively generate them based on learned matching probabilities among a group of candidates, which can boost the registration accuracy. Our loss function incorporates both the local similarity and the global geometric constraints to ensure all above network designs can converge towards the right direction. We comprehensively validate the effectiveness of our approach using both the KITTI dataset and the Apollo-SouthBay dataset. Results demonstrate that our method achieves comparable or better performance than the state-of-the-art geometry-based methods. Detailed ablation and visualization analysis are included to further illustrate the behavior and insights of our network. The low registration error and high robustness of our method makes it attractive for substantial applications relying on the point cloud registration task.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1905.04153](http://arxiv.org/abs/1905.04153)

##### PDF
[http://arxiv.org/pdf/1905.04153](http://arxiv.org/pdf/1905.04153)


---
layout: post
title: "Inertial-Based Scale Estimation for Structure from Motion on Mobile Devices"
date: 2017-08-11 09:44:42
categories: arXiv_CV
tags: arXiv_CV Tracking
author: Janne Mustaniemi, Juho Kannala, Simo Särkkä, Jiri Matas, Janne Heikkilä
mathjax: true
---

* content
{:toc}

##### Abstract
Structure from motion algorithms have an inherent limitation that the reconstruction can only be determined up to the unknown scale factor. Modern mobile devices are equipped with an inertial measurement unit (IMU), which can be used for estimating the scale of the reconstruction. We propose a method that recovers the metric scale given inertial measurements and camera poses. In the process, we also perform a temporal and spatial alignment of the camera and the IMU. Therefore, our solution can be easily combined with any existing visual reconstruction software. The method can cope with noisy camera pose estimates, typically caused by motion blur or rolling shutter artifacts, via utilizing a Rauch-Tung-Striebel (RTS) smoother. Furthermore, the scale estimation is performed in the frequency domain, which provides more robustness to inaccurate sensor time stamps and noisy IMU samples than the previously used time domain representation. In contrast to previous methods, our approach has no parameters that need to be tuned for achieving a good performance. In the experiments, we show that the algorithm outperforms the state-of-the-art in both accuracy and convergence speed of the scale estimate. The accuracy of the scale is around $1\%$ from the ground truth depending on the recording. We also demonstrate that our method can improve the scale accuracy of the Project Tango's build-in motion tracking.

##### Abstract (translated by Google)
来自运动算法的结构具有固有的限制，即重建只能被确定到未知的比例因子。现代移动设备配有惯性测量单元（IMU），可用于估计重建的规模。我们提出了一种方法，恢复惯性测量和相机姿态的公制尺度。在这个过程中，我们也执行相机和IMU的时间和空间对齐。因此，我们的解决方案可以轻松与任何现有的视觉重建软件相结合。该方法可以通过使用Rauch-Tung-Striebel（RTS）平滑器来处理噪声相机姿态估计，典型地由运动模糊或滚动快门伪像引起。此外，尺度估计在频域中执行，这比以前使用的时域表示对不准确的传感器时间戳和噪声IMU样本提供了更强的鲁棒性。与以前的方法相比，我们的方法没有需要调整的参数来实现良好的性能。在实验中，我们表明，该算法在规模估计的准确性和收敛速度方面优于现有技术。从实际情况来看，音阶的准确性大约是$ 1 / $ $，取决于录音。我们还证明，我们的方法可以提高Project Tango内置运动跟踪的精度。

##### URL
[https://arxiv.org/abs/1611.09498](https://arxiv.org/abs/1611.09498)

##### PDF
[https://arxiv.org/pdf/1611.09498](https://arxiv.org/pdf/1611.09498)


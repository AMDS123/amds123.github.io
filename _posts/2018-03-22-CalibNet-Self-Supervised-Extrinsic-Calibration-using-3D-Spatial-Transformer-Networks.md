---
layout: post
title: "CalibNet: Self-Supervised Extrinsic Calibration using 3D Spatial Transformer Networks"
date: 2018-03-22 00:24:04
categories: arXiv_RO
tags: arXiv_RO
author: Ganesh Iyer, Karnik Ram R., J. Krishna Murthy, K. Madhava Krishna
mathjax: true
---

* content
{:toc}

##### Abstract
3D LiDARs and 2D cameras are increasingly being used alongside each other in sensor rigs for perception tasks. Before these sensors can be used to gather meaningful data, however, their extrinsics (and intrinsics) need to be accurately calibrated, as the performance of the sensor rig is extremely sensitive to these calibration parameters. A vast majority of existing calibration techniques require significant amounts of data and/or calibration targets and human effort, severely impacting their applicability in large-scale production systems. We address this gap with CalibNet: a self-supervised deep network capable of automatically estimating the 6-DoF rigid body transformation between a 3D LiDAR and a 2D camera in real-time. CalibNet alleviates the need for calibration targets, thereby resulting in significant savings in calibration efforts. During training, the network only takes as input a LiDAR point cloud, the corresponding monocular image, and the camera calibration matrix K. At train time, we do not impose direct supervision (i.e., we do not directly regress to the calibration parameters, for example). Instead, we train the network to predict calibration parameters that maximize the geometric and photometric consistency of the input images and point clouds. CalibNet learns to iteratively solve the underlying geometric problem and accurately predicts extrinsic calibration parameters for a wide range of mis-calibrations, without requiring retraining or domain adaptation. The project page is hosted at this https URL

##### Abstract (translated by Google)
三维激光雷达和二维相机越来越多地被用于感知任务的传感器装置中。然而，在这些传感器可用于收集有意义的数据之前，它们的外部因素（和内在因素）需要进行精确校准，因为传感器的性能对这些校准参数非常敏感。绝大多数现有的校准技术都需要大量的数据和/或校准目标以及人力，严重影响其在大规模生产系统中的适用性。我们利用CalibNet解决了这个差距：一个自我监控的深度网络，能够实时自动估算3D LiDAR和2D相机之间的6-DoF刚体变换。 CalibNet减轻了对校准目标的需求，从而大大节省了校准工作量。在训练期间，网络仅将LiDAR点云，相应的单眼图像和相机校准矩阵K作为输入。在训练时，我们不施加直接监督（即，我们不直接回归到校准参数，例）。相反，我们训练网络来预测校准参数，以最大限度地提高输入图像和点云的几何和光度一致性。 CalibNet学习迭代地解决潜在的几何问题，并准确预测各种误校准的外部校准参数，而无需再培训或域适应。项目页面托管在此https网址上

##### URL
[https://arxiv.org/abs/1803.08181](https://arxiv.org/abs/1803.08181)

##### PDF
[https://arxiv.org/pdf/1803.08181](https://arxiv.org/pdf/1803.08181)


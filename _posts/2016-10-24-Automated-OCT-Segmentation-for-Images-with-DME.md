---
layout: post
title: "Automated OCT Segmentation for Images with DME"
date: 2016-10-24 19:24:38
categories: arXiv_CV
tags: arXiv_CV Segmentation Face Tracking
author: Sohini Roychowdhury, Dara D. Koozekanani, Michael Reinsbach, Keshab K. Parhi
mathjax: true
---

* content
{:toc}

##### Abstract
This paper presents a novel automated system that segments six sub-retinal layers from optical coherence tomography (OCT) image stacks of healthy patients and patients with diabetic macular edema (DME). First, each image in the OCT stack is denoised using a Wiener deconvolution algorithm that estimates the additive speckle noise variance using a novel Fourier-domain based structural error. This denoising method enhances the image SNR by an average of 12dB. Next, the denoised images are subjected to an iterative multi-resolution high-pass filtering algorithm that detects seven sub-retinal surfaces in six iterative steps. The thicknesses of each sub-retinal layer for all scans from a particular OCT stack are then compared to the manually marked groundtruth. The proposed system uses adaptive thresholds for denoising and segmenting each image and hence it is robust to disruptions in the retinal micro-structure due to DME. The proposed denoising and segmentation system has an average error of 1.2-5.8 $\mu m$ and 3.5-26$\mu m$ for segmenting sub-retinal surfaces in normal and abnormal images with DME, respectively. For estimating the sub-retinal layer thicknesses, the proposed system has an average error of 0.2-2.5 $\mu m$ and 1.8-18 $\mu m$ in normal and abnormal images, respectively. Additionally, the average inner sub-retinal layer thickness in abnormal images is estimated as 275$\mu m (r=0.92)$ with an average error of 9.3 $\mu m$, while the average thickness of the outer layers in abnormal images is estimated as 57.4$\mu m (r=0.74)$ with an average error of 3.5 $\mu m$. The proposed system can be useful for tracking the disease progression for DME over a period of time.

##### Abstract (translated by Google)
本文提出了一种新型自动化系统，从健康患者和糖尿病性黄斑水肿（DME）患者的光学相干断层扫描（OCT）图像堆叠中分割出六个视网膜下层。首先，使用基于傅里叶域的结构误差估计加性散斑噪声方差的维纳反褶积算法对OCT堆栈中的每个图像进行去噪。这种去噪方法将图像信噪比平均提高了12dB。接下来，去噪图像经历迭代多分辨率高通滤波算法，其在六个迭代步骤中检测七个子视网膜表面。然后将来自特定OCT堆栈的所有扫描的每个子视网膜层的厚度与手动标记的groundtruth进行比较。所提出的系统使用自适应阈值来对每个图像进行去噪和分割，因此它对由于DME导致的视网膜微结构的破坏是强有力的。所提出的去噪和分割系统在DME正常和异常图像中分割视网膜下表面的平均误差分别为1.2-5.8微米和3.5-26微米。为了估计视网膜下层厚度，所提出的系统在正常和异常图像中的平均误差分别为0.2-2.5微米和1.8-18微米。此外，异常图像的平均内部视网膜下层厚度估计为275 $ \ mu（r = 0.92）$，平均误差为9.3 $ \ mu $，而异常图像中的外层平均厚度估计为57.4 $ \ mu（r = 0.74）$，平均误差为3.5 $ \ mu $。所提出的系统可用于在一段时间内追踪DME的疾病进展。

##### URL
[https://arxiv.org/abs/1610.07560](https://arxiv.org/abs/1610.07560)

##### PDF
[https://arxiv.org/pdf/1610.07560](https://arxiv.org/pdf/1610.07560)


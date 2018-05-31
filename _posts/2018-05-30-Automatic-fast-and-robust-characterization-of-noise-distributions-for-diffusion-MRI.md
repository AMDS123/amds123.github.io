---
layout: post
title: "Automatic, fast and robust characterization of noise distributions for diffusion MRI"
date: 2018-05-30 16:38:25
categories: arXiv_CV
tags: arXiv_CV Knowledge
author: Samuel St-Jean, Alberto De Luca, Max A. Viergever, Alexander Leemans
mathjax: true
---

* content
{:toc}

##### Abstract
Knowledge of the noise distribution in magnitude diffusion MRI images is the centerpiece to quantify uncertainties arising from the acquisition process. The use of parallel imaging methods, the number of receiver coils and imaging filters applied by the scanner, amongst other factors, dictate the resulting signal distribution. Accurate estimation beyond textbook Rician or noncentral chi distributions often requires information about the acquisition process (e.g. coils sensitivity maps or reconstruction coefficients), which is not usually available. We introduce a new method where a change of variable naturally gives rise to a particular form of the gamma distribution for background signals. The first moments and maximum likelihood estimators of this gamma distribution explicitly depend on the number of coils, making it possible to estimate all unknown parameters using only the magnitude data. A rejection step is used to make the method automatic and robust to artifacts. Experiments on synthetic datasets show that the proposed method can reliably estimate both the degrees of freedom and the standard deviation. The worst case errors range from below 2% (spatially uniform noise) to approximately 10% (spatially variable noise). Repeated acquisitions of in vivo datasets show that the estimated parameters are stable and have lower variances than compared methods.

##### Abstract (translated by Google)
量化扩散MRI图像中噪声分布的知识是量化采集过程中产生的不确定性的核心。并行成像方法的使用，由扫描仪应用的接收器线圈和成像滤波器的数量等因素决定了所产生的信号分布。除教科书之外的精确估计或者非中心辐射分布常常需要关于采集过程的信息（例如线圈灵敏度图或重建系数），这通常是不可用的。我们引入了一种新方法，其中变量的变化自然引起背景信号的特定形式的伽马分布。这种伽玛分布的一阶矩和最大似然估计量明确取决于线圈的数量，从而可以仅使用幅度数据来估计所有未知参数。拒绝步骤用于使方法自动并且对工件有效。在合成数据集上的实验表明，所提出的方法能够可靠地估计自由度和标准偏差。最差情况误差范围从低于2％（空间均匀噪声）到约10％（空间可变噪声）。重复获得的体内数据集显示估计参数比比较方法稳定并且具有更低的方差。

##### URL
[https://arxiv.org/abs/1805.12071](https://arxiv.org/abs/1805.12071)

##### PDF
[https://arxiv.org/pdf/1805.12071](https://arxiv.org/pdf/1805.12071)


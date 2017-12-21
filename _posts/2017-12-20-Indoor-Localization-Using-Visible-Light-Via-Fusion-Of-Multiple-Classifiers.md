---
layout: post
title: "Indoor Localization Using Visible Light Via Fusion Of Multiple Classifiers"
date: 2017-12-20 06:44:32
categories: arXiv_CV
tags: arXiv_CV Prediction Detection
author: Xiansheng Guo, Sihua Shao, Nirwan Ansari, Abdallah Khreishah
mathjax: true
---

* content
{:toc}

##### Abstract
A multiple classifiers fusion localization technique using received signal strengths (RSSs) of visible light is proposed, in which the proposed system transmits different intensity modulated sinusoidal signals by LEDs and the signals received by a Photo Diode (PD) placed at various grid points. First, we obtain some {\emph{approximate}} received signal strengths (RSSs) fingerprints by capturing the peaks of power spectral density (PSD) of the received signals at each given grid point. Unlike the existing RSSs based algorithms, several representative machine learning approaches are adopted to train multiple classifiers based on these RSSs fingerprints. The multiple classifiers localization estimators outperform the classical RSS-based LED localization approaches in accuracy and robustness. To further improve the localization performance, two robust fusion localization algorithms, namely, grid independent least square (GI-LS) and grid dependent least square (GD-LS), are proposed to combine the outputs of these classifiers. We also use a singular value decomposition (SVD) based LS (LS-SVD) method to mitigate the numerical stability problem when the prediction matrix is singular. Experiments conducted on intensity modulated direct detection (IM/DD) systems have demonstrated the effectiveness of the proposed algorithms. The experimental results show that the probability of having mean square positioning error (MSPE) of less than 5cm achieved by GD-LS is improved by 93.03\% and 93.15\%, respectively, as compared to those by the RSS ratio (RSSR) and RSS matching methods with the FFT length of 2000.

##### Abstract (translated by Google)
提出了一种利用可见光的接收信号强度（RSS）的多分类器融合定位技术，该系统利用LED传输不同强度调制的正弦信号，并通过放置在各个网格点的光电二极管（PD）接收信号。首先，我们通过捕获每个给定网格点处的接收信号的功率谱密度（PSD）的峰值来获得一些{近似}接收信号强度（RSS）指纹。与现有的基于RSS的算法不同，采用了几种有代表性的机器学习方法来根据这些RSS指纹对多个分类器进行训练。多分类器定位估计器在精度和鲁棒性方面优于传统的基于RSS的LED定位方法。为了进一步提高定位性能，提出了两种稳健的融合定位算法，即网格独立最小二乘（GI-LS）和网格相关最小二乘（GD-LS）来组合这些分类器的输出。当预测矩阵奇异时，我们还采用基于奇异值分解（LS-SVD）的LS（SVD）方法来缓解数值稳定性问题。在强度调制直接检测（IM / DD）系统上进行的实验证明了所提出算法的有效性。实验结果表明，与RSS比（RSSR）相比，GD-LS的均方差定位误差（MSPE）小于5cm的概率分别提高了93.03％和93.15％ FFT长度为2000的RSS匹配方法。

##### URL
[http://arxiv.org/abs/1703.02184](http://arxiv.org/abs/1703.02184)

##### PDF
[http://arxiv.org/pdf/1703.02184](http://arxiv.org/pdf/1703.02184)


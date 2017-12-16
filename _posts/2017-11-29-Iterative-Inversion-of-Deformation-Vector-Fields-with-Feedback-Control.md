---
layout: post
title: "Iterative Inversion of Deformation Vector Fields with Feedback Control"
date: 2017-11-29 15:42:28
categories: arXiv_CV
tags: arXiv_CV
author: Abhishek Kumar Dubey, Alexandros-Stavros Iliopoulos, Xiaobai Sun, Fang-Fang Yin, Lei Ren
mathjax: true
---

* content
{:toc}

##### Abstract
Purpose: This study aims at improving both accuracy with respect to inverse consistency and efficiency for numerical DVF inversion, by the development of a fixed-point iteration method with feedback control. Method: We introduce an iterative method with active feedback control for DVF inversion, its analysis and adaptation to patient-specific data. The method improves upon and includes two previous fixed-point iteration methods. At each iteration step, we measure the inconsistency, namely the inverse residual, between the iterative inverse estimate and the input DVF. The residual is modulated by a feedback control mechanism before being incorporated into the next iterate. The feedback control design is based on analysis of error propagation in the iteration process. The control design goal is to suppress estimation error progressively to make the convergence region as large as possible, and make estimate errors vanish faster whenever possible. We demonstrate the new method with a constant single-parameter control mechanism and a varying one. The feedback control mechanism is assessed experimentally with analytical deformations and with numerical DVFs between end-of-expiration and end-of-inspiration CT images of 7 patients. Results: The active feedback control is analytically shown to attain a larger convergence region at faster pace in iterative DVF inversion. With the analytical deformation, the iteration becomes convergent over the entire image domain, and the convergence is sped up compared to the precursor methods, which suffer from slow convergence, or even divergence, when displacement is large. With the patient DVF data, the varying control scheme outperforms the precursor methods in inverse consistency and computational efficiency. Conclusion: The formal analysis introduced here provides a new way of understanding and designing efficient iterative methods for DVF inversion.

##### Abstract (translated by Google)
目的：本研究旨在通过开发具有反馈控制的定点迭代方法来提高数值DVF反演的反向一致性和效率方面的精度。方法：我们引入了一种主动反馈控制的DVF反演迭代法，分析和适应患者特定的数据。该方法改进并包括两个先前的定点迭代方法。在每个迭代步骤中，我们测量迭代逆估计和输入DVF之间的不一致性，即逆残差。在被结合到下一次迭代之前，残差被反馈控制机制调制。反馈控制设计基于对迭代过程中误差传播的分析。控制设计的目标是逐步抑制估计误差，使收敛区域尽可能大，并尽可能使估计误差更快地消失。我们用一个不变的单参数控制机制和不同的方法来演示新的方法。对反馈控制机制进行了实验评估，分析变形和7例患者呼气末期和吸气末期CT图像之间的数字DVF。结果：分析表明主动反馈控制在迭代DVF反演中得到更快的收敛区域。随着解析变形的进行，迭代在整个图像域上趋于收敛，收敛速度比前驱方法快，当位移较大时，收敛速度慢，甚至发散。对于患者DVF数据，改变控制方案在反向一致性和计算效率方面优于前驱方法。结论：这里介绍的形式分析为理解和设计DVF反演的高效迭代方法提供了新的途径。

##### URL
[https://arxiv.org/abs/1610.08589](https://arxiv.org/abs/1610.08589)

##### PDF
[https://arxiv.org/pdf/1610.08589](https://arxiv.org/pdf/1610.08589)


---
layout: post
title: "Automatic Optimization of Hardware Accelerators for Image Processing"
date: 2015-02-26 06:16:51
categories: arXiv_CV
tags: arXiv_CV Knowledge Optimization
author: Oliver Reiche, Konrad Häublein, Marc Reichenbach, Frank Hannig, Jürgen Teich, Dietmar Fey
mathjax: true
---

* content
{:toc}

##### Abstract
In the domain of image processing, often real-time constraints are required. In particular, in safety-critical applications, such as X-ray computed tomography in medical imaging or advanced driver assistance systems in the automotive domain, timing is of utmost importance. A common approach to maintain real-time capabilities of compute-intensive applications is to offload those computations to dedicated accelerator hardware, such as Field Programmable Gate Arrays (FPGAs). Programming such architectures is a challenging task, with respect to the typical FPGA-specific design criteria: Achievable overall algorithm latency and resource usage of FPGA primitives (BRAM, FF, LUT, and DSP). High-Level Synthesis (HLS) dramatically simplifies this task by enabling the description of algorithms in well-known higher languages (C/C++) and its automatic synthesis that can be accomplished by HLS tools. However, algorithm developers still need expert knowledge about the target architecture, in order to achieve satisfying results. Therefore, in previous work, we have shown that elevating the description of image algorithms to an even higher abstraction level, by using a Domain-Specific Language (DSL), can significantly cut down the complexity for designing such algorithms for FPGAs. To give the developer even more control over the common trade-off, latency vs. resource usage, we will present an automatic optimization process where these criteria are analyzed and fed back to the DSL compiler, in order to generate code that is closer to the desired design specifications. Finally, we generate code for stereo block matching algorithms and compare it with handwritten implementations to quantify the quality of our results.

##### Abstract (translated by Google)
在图像处理领域，通常需要实时约束。特别是在安全关键的应用领域，例如医疗成像中的X射线计算机断层扫描或汽车领域的高级驾驶员辅助系统，时机至关重要。保持计算密集型应用程序实时功能的常用方法是将这些计算卸载到专用加速器硬件（如现场可编程门阵列（FPGA））中。编程这样的架构是一个具有挑战性的任务，就典型的FPGA特定的设计标准而言：可实现FPGA原语（BRAM，FF，LUT和DSP）的总体算法延迟和资源使用。高层次综合（HLS）通过使用熟知的高级语言（C / C ++）中的算法描述以及可以由HLS工具完成的自动综合而大大简化了这一任务。然而，算法开发人员仍然需要有关目标体系结构的专业知识，才能取得令人满意的结果。因此，在以前的工作中，我们已经表明，通过使用领域专用语言（DSL）将图像算法的描述提升到更高的抽象层次，可以显着降低FPGA的设计算法的复杂度。为了使开发人员能够更好地控制常见的权衡，延迟与资源使用，我们将提供一个自动优化过程，将这些标准进行分析并反馈给DSL编译器，以便生成更接近所需的设计规格。最后，我们生成立体块匹配算法的代码，并将其与手写实现进行比较，以量化我们结果的质量。

##### URL
[https://arxiv.org/abs/1502.07448](https://arxiv.org/abs/1502.07448)

##### PDF
[https://arxiv.org/pdf/1502.07448](https://arxiv.org/pdf/1502.07448)


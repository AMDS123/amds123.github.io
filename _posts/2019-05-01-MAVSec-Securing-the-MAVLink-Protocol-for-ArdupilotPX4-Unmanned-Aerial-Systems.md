---
layout: post
title: "MAVSec: Securing the MAVLink Protocol for Ardupilot/PX4 Unmanned Aerial Systems"
date: 2019-05-01 11:17:36
categories: arXiv_RO
tags: arXiv_RO Drone
author: Azza Allouch, Omar Cheikhrouhou, Anis Koubaa, Mohamed Khalgui, Tarek Abbes
mathjax: true
---

* content
{:toc}

##### Abstract
The MAVLink is a lightweight communication protocol between Unmanned Aerial Vehicles (UAVs) and ground control stations (GCSs). It defines a set of bi-directional messages exchanged between a UAV (aka drone) and a ground station. The messages carry out information about the UAV's states and control commands sent from the ground station. However, the MAVLink protocol is not secure and has several vulnerabilities to different attacks that result in critical threats and safety concerns. Very few studies provided solutions to this problem. In this paper, we discuss the security vulnerabilities of the MAVLink protocol and propose MAVSec, a security-integrated mechanism for MAVLink that leverages the use of encryption algorithms to ensure the protection of exchanged MAVLink messages between UAVs and GCSs. To validate MAVSec, we implemented it in Ardupilot and evaluated the performance of different encryption algorithms (i.e. AES-CBC, AES-CTR, RC4, and ChaCha20) in terms of memory usage and CPU consumption. The experimental results show that ChaCha20 has a better performance and is more efficient than other encryption algorithms. Integrating ChaCha20 into MAVLink can guarantee its messages confidentiality, without affecting its performance, while occupying less memory and CPU consumption, thus, preserving memory and saving the battery for the resource-constrained drone.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1905.00265](http://arxiv.org/abs/1905.00265)

##### PDF
[http://arxiv.org/pdf/1905.00265](http://arxiv.org/pdf/1905.00265)


---
title: An Embarrassingly Simple Approach for Trojan Attack in Deep Neural Networks
date: 2020-10-21T01:31:49.464Z
draft: false
featured: false
authors:
  - Ruixiang Tang
  - Mengnan Du
  - Ninghao Liu
  - Fan Yang
  - Xia Hu
tags:
  - Deep Learning Security; Trojan Attack; Anomaly Detection
image:
  filename: traffic_sign.png
  focal_point: Smart
  preview_only: false
  caption: An example of trojan attack. The traffic sign classifier has been
    injected with trojans. During the inference phase, (a) model works normally
    without triggers, (b) hackers manipulate the prediction by adding different
    triggers.
---
With the widespread use of deep neural networks (DNNs) in highstake applications, the security problem of the DNN models has received extensive attention. In this paper, we investigate a specific security problem called trojan attack, which aims to attack deployed DNN systems relying on the hidden trigger patterns inserted by malicious hackers. We propose a training-free attack approach which is different from previous work, in which trojaned behaviors are injected by retraining model on a poisoned dataset. Specifically, we do not change parameters in the original model but insert a tiny trojan module (TrojanNet) into the target model.
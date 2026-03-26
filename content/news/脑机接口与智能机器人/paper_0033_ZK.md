---
author: 赵奎
title: "期刊 JBHI 发表论文：基于层次化注意力机制和时序卷积网络的多尺度脑电信号解码方法"
date: 2026-02-28
categories: 脑机接口与智能机器人
tags: 脑机接口与智能机器人
authorimage: ../assets/images/global/favicon-32x32.png
language: zh-CN
featured_image: ../assets/images/featured/paper_images/paper_0033_图1.png
summary: 论文“MuST:Multi-Scale Transformer Incorporating Hierarchical Attention and TCN for EEG Decoding”被SCI一区期刊IEEE Journal of Biomedical and Health Informatics接收


---

## <center>论文“MuST:Multi-Scale Transformer Incorporating Hierarchical Attention and TCN for EEG Decoding”被SCI一区期刊IEEE Journal of Biomedical and Health Informatics接收

#### 时间：2026-02-28
#### 关键词：脑机接口与智能机器人，文章接收



&emsp;&emsp;近日，硕士研究生赵奎在 IEEE JBHI（sci一区）发表题为“MuST: Multi-Scale Transformer Incorporating Hierarchical Attention and TCN for EEG Decoding”的文章，通讯作者为张枢教授。


&emsp;&emsp;Electroencephalography (EEG) signals exhibit significant and inherent time scales differences across individuals and tasks. Despite notable successes in decoding EEG signals in single-tasks (e.g., detection of epilepsy), where the time scales are relatively consistent, substantial differences in temporal characteristics among various tasks pose a significant challenge.
To address these limitations, we propose the MuST, which stands for Multi-Scale Transformer, aiming to dynamically learn characteristics of EEG signals on different time scales. Building on the conventional Convolutional Neural Network (CNN)-Transformer model, the MuST introduces two innovations: (1) A hierarchical Transformer structure to dynamically capture global dependencies and long-range information from EEG signals at different scales. (2) A novel temporal convolutional network (TCN) module to replace the original feed forward network (FFN) module in the Transformer, effectively capturing local temporal patterns and short-term dependencies from EEG signals. To validate the performance of the MuST, we conducted experiments on five public EEG datasets with extreme time-scale differences. The experimental results on these datasets demonstrate that we have achieved an average classification accuracy of 91.69% under identical parameter settings. This surpasses the baseline EEGNet by 5.65%, highlighting its superior capability in handling multi-scale EEG signals for diverse tasks. More critically, MuST demonstrates a successful unified modeling of EEG temporal heterogeneity through mixed dataset training (epilepsy detection and sleep staging classification). This breakthrough validates our multi-scale architecture's capability to dynamically reconcile divergent neurophysiological timescales within a single model.

<center><img src="/images/paper_images/paper_0033_图1.png" align="center" alt="图1：框架图" title="图1：框架图" style="zoom:80%;"/>
图1：框架图。</center>






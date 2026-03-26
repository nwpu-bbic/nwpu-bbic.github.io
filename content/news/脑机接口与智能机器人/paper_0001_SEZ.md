---
author: 史恩泽
title: "顶刊NN发表论文：区分大脑状态——基于多段信号随机重组与交互式双向RNN"
date: 2023-07-18
categories: 脑机接口与智能机器人
tags: 脑机接口与智能机器人
authorimage: ../assets/images/global/favicon-32x32.png
language: zh-CN

featured_image: ../assets/images/featured/paper_images/paper_0001_图1.png
summary: 论文“Differentiating brain states via multi-clip random fragment strategy-based interactive bidirectional recurrent neural network”被顶刊Neural Networks接收

---

## <center>论文“Differentiating brain states via multi-clip random fragment strategy-based interactive bidirectional recurrent neural network”被顶刊Neural Networks接收


#### 时间：2023-07-18
#### 关键词：脑机接口与智能机器人，文章接收



&emsp;&emsp;近日，硕士研究生史恩泽在计算机科学领域顶级期刊（Neural Networks，IF = 7.8，JCR Q1）发表题为“Differentiating brain states via multi-clip random fragment strategy-based interactive bidirectional recurrent neural network”的研究性文章，通讯作者为张枢教授和赵世杰教授。


#### Highlights
- McRFS-IBiRNN shows promising characterization ability in brain state differentiation.
- The proposed McRFS suppresses erroneous learning, enhances data structure diversity.
- The proposed interactive BiRNN deeply fuses forward and backward representations.
- The sparse penalty algorithm helps the FC layer extract activated brain regions.


&emsp;&emsp;EEG is widely adopted to study the brain and brain computer interface (BCI) for its non-invasiveness and low costs. Specifically EEG can be applied to differentiate brain states, which is important for better understanding the working mechanisms of the brain. Recurrent neural network (RNN)-based learning strategy has been widely utilized to differentiate brain states, because its optimization architectures improve the classification performance for differentiating brain states at the group level. However, present classification performance is still far from satisfactory. We have identified two major focal points for improvements: one is about organizing the input EEG signals, and the other is related to the design of the RNN architecture. To optimize the above-mentioned issues and achieve better brain state classification performance, we propose a novel multi-clip random fragment strategy-based interactive bidirectional recurrent neural network (McRFS-IBiRNN) model in this work (图1). 

<img src="/images/paper_images/paper_0001_图1.png" align="center" alt="图1.McRFS-IBRNN模型框架" title="图1.McRFS-IBRNN模型框架" style="zoom:80%;"/>
<center>图1：McRFS-IBRNN模型框架</center>


&emsp;&emsp;This model has two advantages over previous methods. First, the McRFS component is designed to re-organize the input EEG signals to make them more suitable for the RNN architecture. Second, the IBiRNN component is an innovative design to model the RNN layers with interaction connections to enhance the fusion of bidirectional features (图2). By adopting the proposed model, promising brain states classification performances are obtained. For example, 96.97% and 99.34% of individual and group level four-category classification accuracies are successfully obtained on the EEG motor/imagery dataset, respectively. A 99.01% accuracy can be observed for four-category classification tasks with new subjects not seen before, which demonstrates the generalization of our proposed method. Compared with existing methods, our model outperforms them with superior results. Overall, the proposed McRFS-IBiRNN model demonstrates great superiority in differentiating brain states on EEG signals.

<center><img src="/images/paper_images/paper_0001_图2.png" align="center" alt="图2：交互式堆叠双向循环神经网络结构" title="图2：交互式堆叠双向循环神经网络结构" style="zoom:50%;"/>
图2：交互式堆叠双向循环神经网络结构</center>



#### 参考文献

Shu Zhang, Enze Shi, Lin Wu, Ruoyang Wang, Sigang Yu, Zhengliang Liu, Shaochen Xu, Tianming Liu, and Shijie Zhao. “Differentiating brain states via multi-clip random fragment strategy-based interactive bidirectional recurrent neural network.” Neural Networks 165 (2023): 1035-1049.





---
author: 杨硕存
title: "会议ICRA 2026发表论文：结构化多样性控制：面向群体感知的多智能体协调双层框架"
date: 2026-01-31
categories: 脑机接口与智能机器人
tags: 脑机接口与智能机器人
authorimage: ../assets/images/global/favicon-32x32.png
language: zh-CN
featured_image: ../assets/images/featured/paper_images/paper_0031_图1.png
summary: 论文“Structured Diversity Control:A Dual-Level Framework for Group-Aware Multi-Agent Coordination”被会议ICRA2026 conference接收

---

## <center>论文“Structured Diversity Control: A Dual-Level Framework for Group-Aware Multi-Agent Coordination”被会议ICRA2026 conference接收

#### 时间：2026-01-31
#### 关键词：脑机接口与智能机器人，集群控制，文章接收



&emsp;&emsp;近日，硕士研究生杨硕存在ICRA2026 conference上发表题为“Structured Diversity Control: A Dual-Level Framework for Group-Aware Multi-Agent Coordination”的文章，通讯作者为张枢教授。


&emsp;&emsp;Controlling the behavioral diversity is a pivotal challenge in multi-agent reinforcement learning (MARL), particularly in complex collaborative scenarios. While existing methods attempt to regulate behavioral diversity by directly differentiating across all agents, they lack deep characterization and learning of multi-agent composition structures. This limitation leads to suboptimal performance or coordination failures when facing more complex or challenging tasks. To bridge this gap, we introduce Structured Diversity Control (SDC), a framework that redefines the system-wide diversity metric as a weighted combination of intra-group diversity, which is minimized for cohesion and inter-group diversity, which is maximized for specialization. The trade-off is governed by a pre-set Diversity Structure Factor (DSF), allowing for fine-grained, group-aware control over the collective strategy. Our method directly constrains the policy architecture without altering reward functions. This structural definition of diversity enables SDC to deliver substantial performance gains across various experiments, including increasing average rewards by up to 47.1% in multi-target pursuit and reducing episode lengths by 12.82% in complex neutralization scenarios. The proposed method offers a novel analytical perspective on the problem of cooperation in group-aware multi-agent systems.


<center><img src="/images/paper_images/paper_0031_图1.png" align="center" alt="图1：框架图" title="图1：框架图" style="zoom:80%;"/>
图1：框架图。Overview of the Structured Diversity Control (SDC) framework within a MARL training loop: (a) Structured Diversity Control: Within the SDC framework, a structured diversity constraint is imposed on the agent policies. (b) Structured Diversity:At each training step, the framework first computes the structured system diversity from the heterogeneous policy components. (c) Policy Factorization: Each agent's final policy is represented as the sum of a parameter-shared, homogeneous component and a rescaled, per-agent heterogeneous component. The computed SNDstruct is then compared to a desired target value SNDdes to generate a scale factor. This factor is used to rescale the heterogeneous components, resulting in the final updated policies.</center>






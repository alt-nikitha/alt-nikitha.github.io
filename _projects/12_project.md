---
layout: page
title: A Mechanistic Comparison of Representations of Deep RL Algorithms
description: What is learnt differently by RL algorithms that make them better or worse than others?
img: assets/img/robot_probe.jpg
importance: 2
category: academic
---

We aim to understand how different reinforcement learning (RL) algorithms shape the internal representations of their policy networks. Specifically, we will analyze and compare the features learned by various algorithms using Sparse Autoencoders (SAEs), to determine whether representation properties such as sparsity, diversity, and interpretability correlate with generalization or learning efficiency.
Prior studies <a href="https://arxiv.org/pdf/2004.04136">(CURL: Contrastive Unsupervised Representations for Reinforcement Learning)</a> have shown that good representations can enhance RL performance and generalization. There has also been work in using post-hoc analysis of RL policies to uncover internal structure <a href="https://arxiv.org/pdf/2411.00867">(Mechanistic Interpretability of Reinforcement Learning Agents 2024)</a>
Unlike prior work that analyzes a single algorithm or task, this project systematically compares multiple RL algorithms through a representational lens. We introduce SAEs as probes to characterize and quantify the latent features across algorithms, tasks, and training stages

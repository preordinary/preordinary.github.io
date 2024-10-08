---
layout: archive
title: "Academic Experience"
permalink: /academicExp/
author_profile: true
---

## Multi-level Checkpoint Cache for LLM Training   
* Supervised by Dr. Pengfei Zuo
* Keywords: LLM Training; In-Memory Checkpoint; Fast Failure Recovery
* * Analyzed the memory, computation, and communication bottlenecks in current parallelized LLM training schemes and the limitations of conventional checkpoint mechanisms. 
* * Developed a novel multi-level checkpoint mechanism where the LLM model weights and training states are saved to memory and disk at different frequencies depending on failure risk. 
* * Used Megatron-Deepspeed to implement prototype, drastically reducing checkpoint overhead and fault recovery efficiency.

## Sublayer Skipping for Accelerating LLM Inference      
* Supervised by Dr. Pengfei Zuo
* Keywords: LLM Inference; Inference Acceleration; Layer-wise Skipping
* * Developed a layer-wise skipping strategy to reduce the high computational cost and latency in large language model (LLM) inference.
* * Performed comprehensive analysis on the importance of Attention and Feed Forward sublayers in transformer layers across a variety of models to devise the skipping algorithm. 
* * Contributed a training-free, auto-adaptive, sublayer-wise skipping method for both the prefilling and decoding phases of LLMs, demonstrating favorable inference performance over the baselines on various benchmarks and datasets. 

## Distributed Large Model Agent Chain
* Collaborated with Dr. Bin Gao
* Keywords: LLM Agent; Distributed Computing
* * In view of the current situation where a single large model agent cannot handle complex tasks, it is necessary to build an agent chain. How to efficiently deploy multiple agent chains in a GPU cluster is a potential problem.
* * An agent chain scheduling algorithm is designed to optimize the agent's resource overhead and task completion time at the same time.
* * Experiments in actual agent tasks show that our scheduling algorithm is superior to other traditional algorithms.


## Domain Generalization in Federated Learning      
* Supervised by Prof. Zhenzhe Zheng
* Keywords: Federated Learning; Domain Generalization
* * Introduced a disentanglement approach to Federated Domain Generalization (FedDG), where the main objective is to generalize into unseen domains under the context of Federated Learning. 
* * Used a global model to extract domain-invariant features and a local model to extract domain-specific style features. 
* * Utilized contrastive learning for separate learning of domain-invariant and domain-specific features, designed one reconstruction loss functions for preserving information among features. 
* * Conducted tests and experiments on various benchmarks, demonstrating outstanding performance and even surpass most centralized DG methods. 


## No-Reference Image Quality Assessment
* Supervised by Prof. Zhenzhe Zheng
* Keywords: Computer Vision; Image Quality Assessment
* * Developed a novel pluggable and lightweight module for No-Reference Image Quality Assessment (NR-IQA), which evaluates the quality of an image against human evaluation criteria without a reference image. 
* * The proposed module (PLS) compliments existing backbone neural network model solutions by simultaneously extract local and global information and amplifying critical details to improve assessment accuracy. 
* * Conducted tests and evaluations on six NR-IQA benchmark datasets and tested PLS with different backbone models, allows flexible generalization of existing backbone models without significant retraining while achieving competitive results. 
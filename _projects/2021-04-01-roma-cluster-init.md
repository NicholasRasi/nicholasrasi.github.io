---
layout: project
title: ROMA Cluster Init
description: ROMA cluster initialization
summary: ROMA cluster initialization
categories: ["IaaC"]
tags: ["Ansible", "Terraform", "Bash", "Kubernetes"]
---

<a target="_blank" class="repolink" href="https://github.com/NicholasRasi/ROMA2-ClusterInit">› Repository ‹</a> - 
<a target="_blank" class="repolink" href="https://doi.org/10.1007/978-3-030-91431-8_15">› Paper ‹</a>

### What is ROMA?
**TensorFlow**, a popular machine learning (ML) platform, allows users to transparently exploit both GPUs and CPUs to run their applications. 

Since GPUs are optimized for compute-intensive workloads (e.g., matrix calculus), they help boost executions, but introduce resource heterogeneity. TensorFlow neither provides efficient heterogeneous resource management nor allows for the enforcement of user-defined constraints on the execution time. Most of the works address these issues in the context of creating models on existing data sets (training phase), and only focus on scheduling algorithms. 

We focused on the inference phase, that is, on the application of created models to predict the outcome on new data interactively, and presented a comprehensive resource management solution called [ROMA](/projects/roma) (Resource Constrained ML Applications). ROMA is an extension of TensorFlow that:
- provides means to easily deploy multiple TensorFlow models in containers using Kubernetes
- allows users to set constraints on response times
- schedules the execution of requests on GPUs and CPUs using heuristics
- dynamically refines the CPU core allocation exploiting control theory.

### ROMA initialization
ROMA needs an infrastructure and a Kubernetes cluster to be executed. This project allows to initiliaze the infrastructure using **Ansible** or **Terraform** with the **Azure** provider. The [repository](https://github.com/NicholasRasi/ROMA2-ClusterInit){:target="_blank"} contains all the required resources for the ROMA cluster initialization.

### Results
A in-depth discussion about ROMA can be found in: [L. Baresi, G. Quattrocchi, N. Rasi. 2021. “Resource Management for TensorFlow Inference”. 2021 International Conference on Service-Oriented Computing (ICSOC).](https://doi.org/10.1007/978-3-030-91431-8_15){:target="_blank"}
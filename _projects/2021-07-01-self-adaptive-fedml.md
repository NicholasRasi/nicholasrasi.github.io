---
layout: project
title: Federated Machine Learning Framework
description: Federated Machine Learning as a Self-Adaptive Problem 
summary: Federated Machine Learning as a Self-Adaptive Problem 
categories: ["Machine Learning"]
tags: ["TensorFlow", "Flask", "Python"]
---

<a target="_blank" class="repolink" href="https://github.com/NicholasRasi/SelfAdaptive-FedML">› Repository ‹</a> - 
<a target="_new" class="repolink" href="https://doi.ieeecomputersociety.org/10.1109/SEAMS51251.2021.00016">› Paper ‹</a>

### Why Federated Learning?
Machine Learning (ML) enables the creation of a new generation of applications that “learn” from collected data, transferred and analyzed on centralized servers. Moving data may imply a significant overhead and may also undermine users' privacy.

**Federated Machine Learning (FedML)** tries to address these issues by means of local training phases on client devices: only lightweight aggregated data are then sent to the centralized server. FedML solutions must offer response times and accuracy similar to traditional ML applications, but their management is distributed on devices that may be heterogeneous, may become unavailable, and are not as powerful as (cloud-based) servers.

### Self Adaptive
This project considers FedML systems a novel example of self-adaptive applications, where clients and servers must cooperate to provide required results.

### The Framework
I worked on an initial prototype that shows the feasibility of the approach. Then I performed a preliminary evaluation that demonstrates the benefit of the proposed solution. Details about the implementation can be found at this [repository](https://github.com/NicholasRasi/SelfAdaptive-FedML){:target="_blank"}.

### Results
The complete results of the project were pubblished in
[L. Baresi, G. Quattrocchi, N. Rasi. 2021. “Federated Machine Learning as a Self-Adaptive Problem”. 2021 International Symposium on Software Engineering for Adaptive and Self-Managing Systems (SEAMS).](https://doi.ieeecomputersociety.org/10.1109/SEAMS51251.2021.00016){:target="_blank"}
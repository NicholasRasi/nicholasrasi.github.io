---
layout: project
title: Containers Comparison and Benchmarking
description: Container implementations performance and overhead comparison in HPC
summary: Container implementations performance and overhead comparison in HPC
categories: ["HPC"]
tags: ["Slurm", "Ansible", "Bash", "Docker", "Singularity", "MPI"]
---

<a target="_blank" class="repolink" href="https://github.com/NicholasRasi/Containers">Repository Containers</a> | 
<a target="_blank" class="repolink" href="https://github.com/NicholasRasi/SlurmCluster">Repository Slurm Cluster</a>

### Containers 
In this project we want to compare the performance offered by different container implementations. We measured, through benchmarks, the overhead introduced by [Containers](https://github.com/NicholasRasi/Containers){:target="_blank"} during the execution of applications. We also focused on MPI benchmarks in a HPC context.

### HPC cluster initialization
For that purpose, we needed a testbed where running the experiments. This project aims to initialize a SLURM cluster with HPC containers and MPI benchmarks. I developed a set of Ansible Playbooks that allow to configure the testbed required (a multinode cluster with Slurm + MPI benchmarks + HPC containers) for the execution of MPI experiments.

### Results
The results obtained after the experiments are available at:
[https://github.com/NicholasRasi/MPIBenchmarksResults](https://github.com/NicholasRasi/MPIBenchmarksResults){:target="_blank"}
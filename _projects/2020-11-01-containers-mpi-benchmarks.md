---
layout: project
title: Containers MPI benchmarks
description: Ansible playbooks to setup a multinode cluster with Slurm + MPI benchmarks + HPC containers
summary: Ansible playbooks to setup a multinode cluster with Slurm + MPI benchmarks + HPC containers
categories: ["HPC"]
tags: ["Slurm", "Ansible", "Bash", "Docker", "Singularity", "MPI"]
---

<a target="_blank" class="repolink" href="https://github.com/NicholasRasi/SlurmCluster">› Repository ‹</a>


### HPC cluster initialization
In this project we want to benchmark the overhead introduced by [Containers](https://github.com/NicholasRasi/containers){:target="_blank"} during the execution of applications. We focus on MPI benchmark in a HPC context.

For that purpose, we needed a testbed where running the experiments. This project aims to initialize a SLURM cluster with HPC containers and MPI benchmarks. I developed a set of Ansible Playbooks that allow to configure the testbed required for the execution of MPI experiments.

### Results
The results obtained after the experiments are available at:
[https://github.com/NicholasRasi/MPIBenchmarksResults](https://github.com/NicholasRasi/MPIBenchmarksResults){:target="_blank"}
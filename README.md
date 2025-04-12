# Cloud Computing - Resource Benchmarking on Containers, VMs, and Bare Metal (CS553 - HW2)

## Overview
This project is focused on benchmarking and analyzing the performance of system resources — CPU, Memory, and Disk — across different environments:
- Bare Metal (Host Machine)
- Docker Containers
- Virtual Machines (VMs)

The objective is to evaluate and compare the efficiency of each environment while running specific resource-intensive workloads using automation Bash scripts.

---

## Technologies Used
- Bash Scripting
- Docker Containers
- Virtual Machines
- Linux Environment
- Performance Benchmarking

---

## Objectives
- Benchmark CPU, Memory, and Disk performance across Bare Metal, Containers, and VMs.
- Compare resource utilization and performance overhead.
- Automate testing using shell scripts for reproducibility.
- Analyze performance results to understand virtualization impact.

---

## Project Structure

```
cs553-spring2024-hw2/
│
├── CPU/                  # CPU Benchmarking Scripts
│  ├── cpubare.sh         # CPU test on Bare Metal
│  ├── cpucontainer.sh    # CPU test inside Docker Container
│  └── cpuvm              # CPU test on Virtual Machine
├── Memory/               # Memory Benchmarking Scripts
│  ├── membare.sh         # Memory test on Bare Metal
│  ├── memcontainer.sh    # Memory test inside Docker Container
│  ├── memvm.sh           # Memory test on Virtual Machine
│  └── efficiency.sh      # Memory Efficiency Analysis Script
├── Disk/                 # Disk Benchmarking Scripts
│  └── diskcontainer.sh   # Disk test inside Docker Container
│
├── README.md             # Project Documentation
├── readme.txt            # Execution Instructions
└── cloud.pdf             # Report

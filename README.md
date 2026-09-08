# Enhanced Ant Colony Optimization for Cloud Task Scheduling

This repository contains the implementation and experiments associated with our published research on enhanced Ant Colony Optimization variants for efficient task scheduling in cloud computing environments.

## 📌 About the Project

This project investigates classical and enhanced Ant Colony Optimization approaches for cloud task scheduling, with the objective of improving scheduling efficiency and workload distribution across virtual machines.

The implemented algorithms include:

- Ant System (AS)
- Ant Colony Optimization (ACO)
- MAX-MIN Ant System (MMAS)
- Enhanced AS
- Enhanced ACO
- Enhanced MMAS

## 📊 Experimental Setup

The experiments were conducted using the GoCJ workload dataset with:

- 100, 200, 300, and 400 tasks
- 10 Virtual Machines (VMs)
- VM capacities ranging from 5,000 to 15,000 MIPS

The scheduling approaches were evaluated using:

- Makespan
- Degree of Imbalance (DI)

## 🏆 Results

The enhanced Ant Colony Optimization variants demonstrated improved scheduling performance compared with their conventional counterparts.

Among the evaluated approaches, Enhanced MMAS achieved the strongest overall performance, providing lower makespan and improved workload balance across the evaluated task sizes.

## 📓 Implementation

The complete experimental implementation is provided in the Jupyter Notebook included in this repository:

`Final_Copy (1).ipynb`

The notebook contains the implementation of the algorithms, experimental configurations, evaluation procedures, and result visualizations.

## 📄 Publication

**Enhanced Ant Colony Optimization Variants for Efficient Task Scheduling in Cloud Environments**

**Authors:** Nouf Alotaibi, Hala Alotaibi, and Hachemi Bennaceur

Published in **Springer Nature – Lecture Notes in Networks and Systems (LNNS), Volume 1916, 2026**, pp. 99–114.

**DOI:** `10.1007/978-3-032-22032-5_6`

> Note: The publication was originally published under the name **Hala Alotaibi**. The author's current name is **Joud Alotaibi**.

## 🛠️ Technologies

- Python
- NumPy
- Matplotlib
- Jupyter Notebook
- Ant Colony Optimization
- Cloud Task Scheduling

## 👥 Authors

- Nouf Alotaibi
- Joud Alotaibi
- Hachemi Bennaceur

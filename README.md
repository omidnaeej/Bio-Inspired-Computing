# Bio-Inspired-Computing
Projects from the "Bio-Inspired Computing" course at the University of Tehran (Spring 2024).

---

## Table of Contents

1. [Introduction](#introduction)
2. [Algorithms Covered](#algorithms-covered)

   * [Genetic Algorithms (GA)](#genetic-algorithms-ga)
   * [Ant Colony Optimization (ACO)](#ant-colony-optimization-aco)
   * [Simulated Annealing (SA)](#simulated-annealing-sa)
   * [Particle Swarm Optimization (PSO)](#particle-swarm-optimization-pso)
   * [Other Topics](#other-topics)
3. [Repository Structure](#repository-structure)
4. [Setup & Usage](#setup--usage)


---

## Introduction

**Bio-inspired computing** refers to computational algorithms modeled after natural processes to solve complex optimization problems. This repository contains implementations and projects exploring such methods, prepared for the course at the University of Tehran.

---

## Algorithms Covered

### Genetic Algorithms (GA)

An evolutionary technique based on biological natural selection—combining selection, crossover, and mutation to evolve solutions over generations.

### Ant Colony Optimization (ACO)

A probabilistic technique inspired by ants foraging behavior, where pheromone trails guide the search for optimal paths.

### Simulated Annealing (SA)

A probabilistic approach that mimics the annealing process in metallurgy, exploring solution spaces and gradually reducing randomness to converge on minima.

### Particle Swarm Optimization (PSO)

An algorithm modeled on bird flocking/swarming where individuals share information to converge toward optimal solutions.

### Other Topics

Projects also span:

* **Quadratic Assignment Problem (QAP)**
* **Set Covering Problem**
* **Travelling Salesman Problem (TSP)**
* **Memetic Algorithms**

---

## Repository Structure
Organized by algorithm, each folder or notebook typically includes:

* Implementation (via Jupyter notebooks)
* Example cases and results
* Visualizations, where applicable

---

## Setup & Usage

1. **Clone the repository:**

   ```bash
   git clone https://github.com/omidnaeej/Bio-Inspired-Computing.git
   cd Bio-Inspired-Computing
   ```

2. **Install required dependencies:**
   If a `requirements.txt` exists, run:

   ```bash
   pip install -r requirements.txt
   ```

   Otherwise, typical dependencies include:

   ```
   numpy
   matplotlib
   scipy
   jupyter
   ```

3. **Run a project:**

   ```bash
   jupyter notebook
   ```

   Then select any algorithm folder or notebook and follow instructions inside.


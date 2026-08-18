---
layout: default
title: About Me
permalink: /about.html
---

# About Me

Hello! I am **{{ site.author.name }}**. I am currently a researcher/student focusing on **Artificial General Intelligence (AGI)**.

My primary research interests lie in the intersection of **Reinforcement Learning** and **Robotics**. I am passionate about solving the "Sim-to-Real" gap, enabling algorithms trained in simulation to work reliably in the physical world.

Previously, I worked as a Full-Stack Developer, which gave me a strong engineering background to build scalable research platforms.

---

## Research & Project Experience

### Autonomous Quadruped Navigation <span class="pub-year">2023.9 - Present</span>

**Lead Researcher**
{:.text-accent}

* Proposed a **hierarchical reinforcement learning** framework to handle long-horizon navigation tasks.
* Utilized **Domain Randomization** techniques to improve the policy's robustness against physical noise.
* Successfully deployed the policy on a **Unitree Go1** robot dog, achieving smooth navigation in cluttered office environments.
* **Tech Stack:** PyTorch, Isaac Gym, ROS2, C++.

### Distributed Multi-Agent Training Platform <span class="project-year">2022.9 - 2023.9</span>

**Core Developer**
{:.text-accent}

* Designed and implemented a high-throughput distributed training system for Multi-Agent Reinforcement Learning (MARL).
* Optimized data transmission using shared memory and Protobuf, reducing latency by **40%** compared to standard baselines.
* Supported large-scale simulations with over **100 agents** interacting simultaneously.
* **Tech Stack:** Python, Ray, Docker, Kubernetes.

---

## Selected Publications

### Example：a paper title <span class="pub-year">20xx</span>

**Your Name**, Advisor Name, Collaborator A
{:.text-accent}

* *ICRA 2024 (Acceptance Rate: 20%)*
* [PDF](#) & [Code](#)

### Another Important Paper Title Here <span class="pub-year">20xx</span>

**Your Name**, Collaborator B
{:.text-accent}

* *NeurIPS 2023 Workshop*
* [PDF](#) & [Code](#)

---

## Technical Skills

<div class="skills-wrapper">
{% assign skills = "Python, PyTorch, CUDA/Triton, C++, ROS/ROS2, Docker, Linux, Git, LaTeX" | split: ", " %}
{% for skill in skills %}
<span class="badge">{{ skill }}</span>
{% endfor %}
</div>
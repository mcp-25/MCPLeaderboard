---
title: "Programmazione di Sistemi Embedded e Multicore"
date: 2024-10-01
draft: false
summary: "Course overview, objectives, and logistics for the 2024/2025 Academic Year."
---

## Welcome to PSEM

Welcome to the **Programmazione di Sistemi Embedded e Multicore** (Embedded and Multicore Systems Programming) course, taught by **Prof. Daniele De Sensi**.

In the current era of technology, we are witnessing an "AI Boom" driven by data availability, complex models, and—crucially—**computational power**. Companies like NVIDIA have seen massive growth because they provide the hardware (GPUs) necessary to train massive models like ChatGPT, which can require over 200,000 GPUs and cost billions in infrastructure and electricity.


### Why Parallel Computing?

Historically, processor performance increased by roughly 50% per year due to transistor density increases. However, since 2003, this growth has slowed significantly due to physical limitations.

We cannot simply make monolithic processors faster anymore because of the **power wall**:
* Faster processors increase power consumption.
* Increased power consumption generates excess heat.
* Excess heat makes processors unreliable.

To solve modern, complex problems—such as Large Language Models (LLMs), climate modeling, and drug discovery—we must rely on **parallel systems** rather than faster serial processors.


### Course Objectives

This course focuses on how to program these systems efficiently. You will learn to write explicitly parallel programs where multiple cores cooperate to solve a problem. We will use **C** as our reference language because of its relevance and efficiency in systems programming.

The course covers the following key topics and libraries:

1.  **Distributed Programming:** Using **MPI** (Message-Passing Interface) for systems where cores have private memory and communicate over a network.
2.  **Shared-Memory Programming:** Using **Pthreads** and **OpenMP** for systems where cores share access to the same memory.
3.  **GPU Programming:** Using **CUDA** for Single-Instruction Multiple-Data (SIMD) architectures.


### Logistics & Schedule

**Class Schedule:**
* **Tuesday:** 13:00 – 15:00 (Aula 1 Castro Laurenziano).
* **Wednesday:** 14:00 – 17:00 (Aula 1 Castro Laurenziano).

**Resources:**
* **Textbook:** *An Introduction to Parallel Programming*, 2nd ed., by Pacheco & Malensek.
* **Moodle:** Slides, exercises, and news are available on the [Course Moodle Page](https://elearning.uniroma1.it/course/view.php?id=18515).

**Assessment:**
The exam consists of a **Project + Oral Exam**.

---

*For specific questions, you can contact the professor at desensi@di.uniroma1.it to book a question time slot.*